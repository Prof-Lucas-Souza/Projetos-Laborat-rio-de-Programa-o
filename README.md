# Site do Laboratório de Programação — versão 2

Site estático, com página inicial e **7 páginas individuais**, pronto para GitHub Pages.

## Como atualizar seu repositório
1. Extraia o ZIP.
2. No GitHub, abra o repositório do site e envie **todos os arquivos desta pasta para a raiz**, substituindo os arquivos existentes.
3. Mantenha `index.html`, `projetos.json`, `assets/` e as sete páginas `.html` na raiz.
4. Se ainda não habilitou a publicação: **Settings → Pages → Deploy from a branch → main → / (root)**.
5. Aguarde o deploy. Os links das páginas individuais funcionarão em repositórios de projeto e de usuário.

## Como editar os projetos
- Para **editar o conteúdo exibido**, abra o arquivo `nome-do-projeto.html` correspondente e altere o texto dentro das tags HTML.
- `projetos.json` contém uma **cópia estruturada dos cadastros** para futuras versões. Nesta versão, as páginas HTML são estáticas e **não são atualizadas automaticamente** quando você edita o JSON. Se alterar uma informação, atualize também o JSON para mantê-lo sincronizado.
- Para mudar as cores, fontes ou espaçamentos: `assets/style.css`.
- Para alterar os cards da página inicial: `index.html`.

## Dados ausentes
Campos não informados foram omitidos nas páginas, sem textos inventados. A idade não informada de Rafael Krebs fica vazia. Não há seção de autores na página de Gamificação da Educação nem seções de prêmios ou próximos passos quando não foram fornecidos.

## Privacidade
Os nomes e idades de estudantes são exibidos publicamente. Confirme as autorizações institucionais e dos responsáveis antes de publicar.
