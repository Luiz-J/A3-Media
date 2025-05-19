# 🧪 Teste Web Designer - A3 Media

Este projeto foi desenvolvido como parte do teste técnico da A3 Media, utilizando a stack solicitada: **Astro** + **TinaCMS**.

---

## ✅ Objetivo do Teste

- Replicar com fidelidade duas páginas de concorrentes.
- Transformar essas páginas em templates dinâmicos.
- Criar **1000 cópias únicas de cada template** com CMS integrado.
- Permitir edição de conteúdo via TinaCMS.
- Utilizar conteúdo gerado com **faker-js** para diferenciar cada página.

---

## 🛠️ Stack Utilizada

- [Astro](https://astro.build)
- [TinaCMS](https://tina.io)
- [faker-js](https://fakerjs.dev)

---

## ▶️ Como Rodar o Projeto Localmente

1. Instale as dependências:

```bash
npm install
```

2. Inicie o servidor de desenvolvimento:

```bash
npm run dev
```

3. Acesse no navegador:

- Site: [http://localhost:4321](http://localhost:4321)
- CMS: [http://localhost:4321/admin](http://localhost:4321/admin)

---

## 🌐 Rotas Disponíveis

### Template 1
- Caminho: `/paginatemplate1/[id]`
- Exemplo: `/paginatemplate1/1` até `/paginatemplate1/1000`

### Template 2
- Caminho: `/paginatemplate2/[id]`
- Exemplo: `/paginatemplate2/1` até `/paginatemplate2/1000`

---

## 🗂️ Estrutura de Conteúdo

O conteúdo de cada página é gerado via arquivos `.json` e pode ser editado no CMS.

- Diretórios:
  - `content/paginatemplate1/`
  - `content/paginatemplate2/`

---

## 📦 O Que Está Incluído

- Páginas replicadas fielmente conforme os modelos fornecidos.
- Sistema de templates dinâmicos com roteamento automático.
- CMS funcional com conteúdo gerado via faker-js.
- 1000 páginas únicas para cada template.
- Slugs organizados no formato: `/paginatemplate1/{1...1000}`

---

## 📌 Observações Finais

- O projeto está pronto para deploy (ex: Vercel).
- O conteúdo pode ser editado via CMS em tempo real.
- Qualquer dúvida ou ajuste, estou à disposição.

---
