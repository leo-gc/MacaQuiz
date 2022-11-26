# Macaquiz
Projeto desenvolvido utilizando Java e MySQL durante meu primeiro semestre de graduação em Ciência da Computação, no ano de 2022. Só estou postando em meu GitHub agora porque ainda não havia notado a importância do GitHub no mercado de trabalho referente ao ramo da computação.

Projeto Integrador Interdisciplinar - Macaquiz: um jogo educativo sobre programação em python com temática de macacos.

Foram criados os projetos Macaquiz e Macacada, sendo que Macaquiz contém o quiz em si, o qual foi inteiramente desenvolvido por mim. O projeto Macacada contém um jogo com personagem e movimentação desenvolvido por meu colega no mesmo projeto, porém não conseguimos integrar esse projeto ao principal, que é o Macaquiz.

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------

Histórico de Updates:

Macaquiz versão alfa 0.0.1 - 12/05/2022 Criação das classes Jogador e Administrador com getters, setters e métodos CRUD que interagem com o banco de dados projetado. Criação da classe ConnectionFactory, utilizada exclusivamente para gerenciamento da conexão entre programas java e o banco de dados. Criação do programa TesteBD, utilizado para testar as interações entre as classes e o banco de dados.

Macaquiz versão alfa 0.0.2 - 22/05/2022 Criação das interfaces e funcionalidades do jogo na classe Macaquiz, através de subclasses e métodos da classe javax.swing.JFrame, com interfaces funcionais para login, cadastro, introdução, menu do jogador com foto, menu do administrador (sem funções nessa versão), ranking, configurações e perfil. Criação da classe DAO (Data Acess Object), com a função de validar a existência de jogadores/administradores no banco de dados, sendo utilizada no login.

Macaquiz versão alfa 0.0.3 - 22/05/2022 Criação da classe GeradorDeQuestao que contém e gera as questões utilizadas pela classe Macaquiz. Criação dos painéis de interface: Nível Fácil, Questão Fácil, Resposta Correta e Resposta Incorreta, incluindo funcionalidades para estes. Criação de novas patentes, as quais são determinadas conforme a pontuação máxima atingida pelo jogador e representadas por imagens do tipo gif.

Macaquiz versão alfa 0.0.4 - 24/05/2022 Criação da classe Questao, substituindo funções da classe GeradorDeQuestao, a qual não mais existe no projeto. Os painéis de interface adicionados na versão 0.0.3 foram excluídos, pois foi decidido criar apenas um painel de interface inicial do quiz e um painel de pergunta que pode mostrar qualquer pergunta. Criação dos painéis de interface que aparecem caso o usuário perca todas as vidas e caso este chegue ao final do quiz, com pontuação final e patente. Criação da pasta "Banco de dados" que contém o script que deve ser usado para a criação do banco de dados necessário ao funcionamento do jogo.

Macaquiz versão alfa 0.0.5 - 25/05/2022 Inserção de todas as 15 questões do jogo no banco de dados, tornando o quiz realmente funcional. Criação do painel de interface Alterar Jogador que pode ser acessado por um administrador, possibilitando a alteração da pontuação de qualquer jogador.

Macaquiz versão alfa 0.0.6 - 29/05/2022 Criação do painel de Conquistas, que pode ser acessado através do menu e contém uma conquista para cada patente acima da inicial. As conquistas são mostradas de acordo com a patente do jogador.

Macaquiz versão alfa 0.0.7 - 02/06/2022 Correção de bug (ao abrir o painel de Conquistas, estas não apareciam caso o jogador houvesse conquistado a patente mais alta). A partir desta versão, além da possibilidade de alterar seu apelido, o jogador também pode alterar sua senha por meio do mesmo painel de Perfil.
