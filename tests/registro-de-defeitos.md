Registro de Defeitos (Bugs)

Este documento detalha as falhas encontradas durante a execução dos testes.
Defeito 01 - Falha na Busca com Caracteres Especiais

    ID do Defeito: DEF01 

    Descrição: A barra de busca do site não consegue processar termos que contenham acentuação ou caracteres especiais, retornando "0 resultados", mesmo quando o produto existe no banco de dados.

    Passos para Reprodução: 

        Acessar a página inicial do site.

        Clicar no campo de busca.

        Digitar a palavra "Câmera" (com acento).

        Clicar em pesquisar.

    Resultado Esperado: O sistema deve exibir todos os produtos que contenham a palavra "Câmera".

    Resultado Atual: O sistema exibe a mensagem: "Nenhum produto encontrado para 'Câmera'".

    Severidade: Média (afeta a experiência de compra, mas o usuário pode tentar digitar sem acento).

    Status: Aberto.