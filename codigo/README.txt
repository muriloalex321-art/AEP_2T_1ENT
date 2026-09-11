#PSEUDOCÓDIGO/ Menu principal
INÍCIO

    inicializar vetor de ações
    quantidade <- 0

    REPITA

        exibir menu principal
        ler opção

        SE opção = 1 ENTÃO
            cadastrarAção()

        SENÃO SE opção = 2 ENTÃO
            listarAções()

        SENÃO SE opção = 3 ENTÃO
            pesquisarAções()

        SENÃO SE opção = 4 ENTÃO
            atualizarAção()

        SENÃO SE opção = 5 ENTÃO
            gerarResumo()

        SENÃO SE opção = 0 ENTÃO
            exibir mensagem de encerramento

        SENÃO
            exibir "Opção inválida"

        FIM SE

    ATÉ opção = 0

FIM
