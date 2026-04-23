Detalhes da Execução de Testes

    Data da Execução: 23 de Abril de 2026.

    Ambiente: Google Chrome (Desktop).
    
Resultados por Caso de Teste

    CT01 - Cadastro de Usuário

        Resultado: Passou.

        Evidência: O sistema redirecionou para a home e exibiu o alerta de sucesso após o preenchimento dos dados.

    CT02 - Login com Sucesso

        Resultado: Passou.

        Evidência: Acesso concedido corretamente e o nome "Usuário Teste" ficou visível no cabeçalho do site.

    CT03 - Buscar Produto

        Resultado: Falhou.

        Evidência: A barra de busca não retornou resultados para termos que utilizam acentuação (ex: "Câmera").

    CT04 - Formulário de Contato

        Resultado: Passou.

        Evidência: A mensagem foi enviada com sucesso e os campos do formulário foram limpos automaticamente.

Notas 

    Sucesso no Fluxo Principal: Os processos de criação de conta e autenticação estão íntegros.

    Falha Identificada: Foi detectado um defeito funcional na lógica de busca, onde caracteres especiais impedem o retorno de itens do banco de dados.