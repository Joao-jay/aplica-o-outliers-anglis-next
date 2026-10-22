# Outliers × ANGLIS — Cada Segundo Conta

Mini site interativo desenvolvido pelo time **Outliers** para apresentação da campanha **Cada Segundo Conta**, criada para a **ANGLIS**.

## Sobre o projeto

Este projeto é uma experiência digital touch-friendly pensada para ser usada em estandes, apresentações ou tablets durante eventos. Ele traduz a estratégia de comunicação da ANGLIS em uma navegação por três frentes:

1. **Ser encontrada** — presença digital e SEO
2. **Gerar confiança** — conteúdo, influenciadores e privacidade
3. **Ser experimentada** — ativação física e campanha Cada Segundo Conta

## Tecnologias

- HTML5
- CSS3 (com variáveis de identidade visual)
- JavaScript vanilla
- Não depende de frameworks externos

## Estrutura de arquivos

```
outliers-anglis-next/
├── index.html          # Aplicação principal
├── README.md           # Este arquivo
└── media/              # Pasta com os vídeos das frentes (não incluída no repositório)
    ├── ser-encontrada.mp4
    ├── gerar-confianca.mp4
    └── ser-experimentada.mp4
```

> A pasta `media/` está listada no `.gitignore` porque os arquivos de vídeo costumam ser grandes demais para o upload direto pelo GitHub.

## Como hospedar

### 1. GitHub
- Crie um repositório público ou privado no GitHub.
- Envie os arquivos `index.html`, `README.md` e `.gitignore`.
- Não envie a pasta `media/` pelo site do GitHub para evitar erro de arquivo muito grande.

### 2. Vercel
- Acesse [vercel.com](https://vercel.com) e faça login com GitHub.
- Importe o repositório criado.
- Em **Framework Preset**, selecione **Other**.
- Deixe **Build Command** em branco.
- Clique em **Deploy**.

A Vercel gerará um link como:
```
https://outliers-anglis-next.vercel.app
```

## Como adicionar os vídeos

Como os vídeos não são enviados para o GitHub, você tem duas opções:

### Opção A — Hospedar em serviço externo
Suba os vídeos no YouTube, Vimeo, Google Drive (público), Cloudinary ou outro serviço de streaming. Depois edite o arquivo `index.html` e altere as URLs no objeto `details`, dentro da tag `<script>`.

```javascript
video: 'https://seu-servidor.com/ser-encontrada.mp4'
```

### Opção B — Git Large File Storage (LFS)
Se preferir manter os vídeos no GitHub, use o Git LFS. Isso exige instalar o Git no computador.

## Identidade visual

- **Cores principais:** azul `#154EED`, verde `#1ECFB8`, amarelo `#FFDD00`, roxo `#6967FF`
- **Tipografia:** Poppins (títulos) e Lato (textos)
- **Logos:** `logo-outliers.png` e `logo-anglis.png`

## Autores

**Outliers × ANGLIS**  
Projeto desenvolvido para a disciplina NEXT da FIAP.

---

© 2026 ANGLIS · Projeto Outliers. Todos os direitos reservados.  
*Apenas dados. Sem imagens. Sempre.*