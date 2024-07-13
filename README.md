Este repositório abriga o frontend do projeto NJ-cadTechs, uma aplicação voltada para o gerenciamento de usuários, desenvolvida com React e configurada através do Vite. A interface é intuitiva e responsiva, proporcionando uma experiência de usuário eficiente e agradável.

### Tecnologias Utilizadas:
- **React**: Para a construção da interface de usuário dinâmica e reativa.
- **Vite**: Para a configuração e otimização do ambiente de desenvolvimento.
- **CSS**: Para a estilização e layout, garantindo uma aparência moderna e atraente.
- **Axios**: Para a comunicação com a API backend.

### Funcionalidades:
- **Cadastro de Usuários**: Formulário para inserir novos usuários com nome, idade e e-mail.
- **Listagem de Usuários**: Exibição de todos os usuários cadastrados em cartões estilizados.
- **Edição de Usuários**: Capacidade de atualizar informações dos usuários.
- **Exclusão de Usuários**: Remoção de usuários com feedback visual.

### Estrutura do Projeto:
- **index.html**: Ponto de entrada da aplicação, configurando o título e fontes.
- **vite.config.js**: Configurações do Vite para a utilização de plugins React.
- **index.jsx**: Componente principal que renderiza a aplicação React.
- **Home.jsx**: Componente que gerencia a lógica de interação com os usuários e a API.
- **style.css**: Arquivo de estilos que define a aparência dos componentes da aplicação.

### Conexão com o Backend:
O frontend se comunica com a API backend, responsável pela manipulação dos dados de usuários, que se encontra em um repositório separado. A integração é feita através de requisições HTTP utilizando a biblioteca Axios.

Este projeto foi desenvolvido com o objetivo de facilitar o gerenciamento de usuários, oferecendo uma interface amigável e funcionalidades completas para administração de dados. A separação entre frontend e backend promove uma arquitetura modular e escalável, facilitando a manutenção e evolução do sistema.
