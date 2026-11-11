# Jefferson Silva Advocacia - Site Institucional & Calculadoras Trabalhistas

Projeto unificado contendo o site institucional do escritório **Jefferson Silva Advocacia** e o sistema de **16 Calculadoras Trabalhistas**.

- **Sem Banco de Dados:** Todos os dados ficam 100% seguros e armazenados apenas no próprio navegador via `localStorage`.
- **Imagens Embutidas:** O logotipo e a foto profissional foram convertidos para Base64 diretamente no código HTML, eliminando falhas de carregamento.
- **Botão do Blog:** Link direto na barra superior e no rodapé para `https://advocaciajeffersonsilva.blogspot.com/`.

---

## Passo a Passo Completo para Publicar no Render (Gratuito)

### Passo 1: Descompactar e subir no GitHub
1. Baixe e descompacte o arquivo `js-advocacia-render-deploy.zip`.
2. No seu [GitHub](https://github.com/), crie um novo repositório público ou privado chamado `js-advocacia`.
3. Envie para esse repositório os arquivos descompactados (`render.yaml`, `README.md` e a pasta `public/` contendo o `index.html`).

### Passo 2: Criar o site no Render
1. Acesse o seu painel no [Render](https://render.com/).
2. Clique no botão azul **New +** no topo da página e escolha a opção **Static Site**.
3. Selecione a opção para conectar com a sua conta do GitHub e escolha o repositório `js-advocacia`.

### Passo 3: Preencher as configurações
- **Name:** `js-advocacia`
- **Build Command:** *(deixe este campo totalmente em branco)*
- **Publish Directory:** `public`

### Passo 4: Finalizar e acessar
Clique em **Create Static Site**. Em poucos segundos o Render compilará e disponibilizará o link HTTPS gratuito da sua página (exemplo: `https://js-advocacia.onrender.com`).
