# Jogos ATD — 2026/2027

Recursos de estudo para a unidade curricular de **Aprendizagem e Tecnologias Digitais (ATD)** do Mestrado em Psicologia da Educação e Aconselhamento, no ano letivo de 2026/2027.

O recurso principal é o **AprenderDigital**, um jogo de escolha múltipla com **88 questões distribuídas por oito módulos**, explicações e revisão de dificuldades. O repositório inclui também a chave de respostas para o docente, o documento de apoio ao teste e a Ficha da Unidade Curricular (FUC).

## Começar a jogar

1. Descarrega o repositório e extrai os ficheiros, se estiverem num ZIP.
2. Abre [`Aprendizagem_Tecnologias_Digitais_Arcade.html`](Aprendizagem_Tecnologias_Digitais_Arcade.html) num navegador atualizado, com JavaScript ativado.
3. Seleciona **Começar percurso** ou escolhe um módulo no mapa de missões.
4. Escolhe uma das quatro respostas e carrega em **Confirmar** para consultar a explicação.

O jogo funciona diretamente a partir do ficheiro HTML, **sem instalação, servidor ou ligação à Internet**. O código, os estilos e as questões estão incluídos no próprio ficheiro. Não é necessário criar uma conta.

## Modos e funcionalidades

- **Percurso por módulos:** todos os módulos estão disponíveis desde o início. Permite consultar pistas, o caderno de apoio e a solução.
- **Rever dificuldades:** reúne questões já exploradas cuja última resposta não foi correta sem ajuda.
- **Desafio final:** seleciona 16 questões, duas de cada módulo, sem pistas e com correção apenas no fim.
- **Progresso:** apresenta XP, questões exploradas, respostas sem ajuda, acertos autónomos à primeira e distintivos de módulo.
- **Impressão:** o botão **Imprimir módulo**, disponível durante uma missão, prepara as questões para papel. A opção **Incluir soluções na impressão** acrescenta a chave com explicações.
- **Apresentação:** inclui temas claro e escuro e uma interface adaptável a diferentes tamanhos de ecrã.

Não há limite de tempo. As alternativas são baralhadas em cada sessão.

### Pontuação

Cada questão permite acumular até **10 XP**: uma resposta correta sem ajuda vale 10 XP; com pista ou caderno, 5 XP. Consultar a solução não atribui pontos. Repetir uma questão não permite ultrapassar os 10 XP dessa questão, num total máximo de **880 XP**.

O distintivo de um módulo é obtido quando todas as suas questões têm a última resposta correta sem ajuda. Um erro posterior volta a colocar a questão na revisão.

## Conteúdos

| Módulo | Missão | Tema | Questões |
| --- | --- | --- | ---: |
| 01 | Investigar antes de adotar | Ciência da aprendizagem e qualidade da evidência | 8 |
| 02 | Dar espaço ao pensamento | Arquitetura cognitiva e design instrucional | 8 |
| 03 | Desenhar para compreender | Aprendizagem multimédia e vídeo educativo | 16 |
| 04 | Construir significado | Envolvimento cognitivo e aprendizagem generativa | 8 |
| 05 | Recordar para aprender | Prática, retenção e feedback | 8 |
| 06 | Aprender e apoiar à distância | Autorregulação e ensino online ou misto | 16 |
| 07 | Jogar com propósito | Jogos e simulações para aprender | 8 |
| 08 | Usar IA, preservar autonomia | Tutores inteligentes e IA generativa | 16 |
| | | **Total** | **88** |

## Guardar e transportar o progresso

O progresso, a sessão em curso e o tema são guardados no armazenamento local do navegador (`localStorage`). As respostas não são enviadas para um servidor.

Na secção **Guardar, transportar e imprimir**:

- **Exportar progresso** descarrega o ficheiro `aprenderdigital-progresso.json`, que permite guardar uma cópia ou transportar o progresso para outro navegador ou dispositivo.
- **Importar progresso** lê uma exportação do jogo e, após confirmação, substitui o progresso atual e termina a sessão em curso.
- **Apagar progresso** elimina o progresso e a sessão em curso, após confirmação.

A exportação contém os registos de progresso, mas **não inclui a sessão em curso**. Se o navegador impedir o armazenamento local, o jogo apresenta um aviso; exporta o progresso antes de fechar. Guarda também uma exportação antes de limpar os dados do navegador.

## Ficheiros do repositório

| Ficheiro | Conteúdo |
| --- | --- |
| [`Aprendizagem_Tecnologias_Digitais_Arcade.html`](Aprendizagem_Tecnologias_Digitais_Arcade.html) | Jogo autónomo AprenderDigital, com as 88 questões e todas as funcionalidades. |
| [`ATD_Chave_Respostas_Docente.html`](ATD_Chave_Respostas_Docente.html) | Chave de respostas para consulta no navegador, com pesquisa, filtro por módulo, justificações e impressão. |
| [`ATD_Chave_Respostas_Docente.docx`](ATD_Chave_Respostas_Docente.docx) | Chave de respostas em formato Word. |
| [Apoio à preparação para o teste escrito — PDF](A%20-%20Aprendizagem_Tecnologias_Digitais_Apoio_Teste_2026%20a%202027.pdf) | Documento de apoio com o banco de questões e respostas usado como base. |
| [Ficha da Unidade Curricular — PDF](FUC%20-%20Ficha%20da%20Unidade%20CurricularATD%20igitais_2026-27_revista.pdf) | FUC de 2026/2027 que enquadra a organização dos oito módulos. |

## Utilização pelo docente

Abre a [chave de respostas HTML](ATD_Chave_Respostas_Docente.html) para pesquisar palavras do enunciado ou da resposta e filtrar por módulo. Usa **Mostrar justificações** para expandir as explicações e **Imprimir chave** para imprimir a seleção apresentada. A impressão respeita os filtros e inclui as justificações quando estão ativadas.

A chave identifica as respostas pelo **texto da alternativa correta**, pois as letras das opções variam com o baralhamento no jogo. A sua consulta não altera o progresso do estudante.

## Enquadramento pedagógico

Os conteúdos seguem os oito módulos da FUC. As explicações indicam a origem das questões, incluindo secções e páginas do documento de apoio quando aplicável. Os itens assinalados como **Complemento FUC** desenvolvem outros conteúdos do programa; não são transcrições do documento de apoio nem uma previsão do teste.

O recurso destina-se à prática e à avaliação formativa. O banco adaptado não foi sujeito a validação psicométrica; pontos e distintivos são indicadores de prática. As soluções estão acessíveis no código do HTML, pelo que o desafio final não constitui uma avaliação protegida.

## Manutenção

O jogo utiliza HTML, CSS e JavaScript, sem dependências externas ou etapa de compilação. Para o editar, abre o HTML num editor de texto e mantém a codificação UTF-8.

- `DATA.mods` contém a descrição, os objetivos e as notas dos módulos.
- `DATA.qs` contém as questões, alternativas, explicações, pistas e referências.
- Em cada questão, `m` identifica o módulo a partir de zero e `opts[0]` contém a resposta correta; a ordem apresentada ao utilizador é baralhada pelo jogo.
- Ao alterar questões, atualiza também as chaves do docente em HTML e DOCX. Se alterares o número de questões ou módulos, revê os totais apresentados na interface e neste README.
