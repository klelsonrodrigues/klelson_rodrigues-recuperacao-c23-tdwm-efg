Casos de Teste
CT01 - Realizar Cadastro de Novo Usuário

    ID: CT01 

    Funcionalidade: Cadastro 

    Pré-condições: Usuário não deve estar logado; possuir um e-mail válido.

    Passos: 

        Acessar a página de cadastro.

        Preencher nome, e-mail e senha.

        Clicar no botão "Cadastrar".

    Resultado Esperado: O sistema deve exibir a mensagem "Cadastro realizado com sucesso" e redirecionar para a home.

CT02 - Realizar Login com Sucesso

    ID: CT02 

    Funcionalidade: Login 

    Pré-condições: Usuário deve possuir cadastro prévio no sistema.

    Passos: 

        Acessar a página de login.

        Inserir e-mail e senha válidos.

        Clicar em "Entrar".

    Resultado Esperado: O sistema deve autenticar o usuário e exibir o nome do perfil no menu superior.

CT03 - Buscar Produto Existente

    ID: CT03 

    Funcionalidade: Busca 

    Pré-condições: O sistema deve possuir produtos cadastrados no banco de dados.

    Passos: 

        Clicar na barra de busca.

        Digitar "Smartphone".

        Pressionar "Enter" ou clicar no ícone de lupa.

    Resultado Esperado: A página deve exibir uma lista de produtos relacionados ao termo pesquisado.

CT04 - Enviar Formulário de Contato

    ID: CT04 

    Funcionalidade: Formulário de Contato 

    Pré-condições: Acesso à internet estável.

    Passos: 

        Navegar até a página "Contato".

        Preencher nome, e-mail e o campo "Assunto".

        Clicar em "Enviar Mensagem".

    Resultado Esperado: O sistema deve limpar os campos e exibir o aviso "Mensagem enviada com sucesso".