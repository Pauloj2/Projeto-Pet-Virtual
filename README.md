# PROJETO 1 – 10 pontos
## 1. DESCRIÇÃO

Os alunos deverão ser organizados em equipes de no mínimo 3 pessoas e no máximo 4 pessoas. Equipes com menos ou mais membros autorizados nota zero na atividade. Cada equipe deverá escolher um nome de “tempo de desenvolvimento”. Essa equipe deverá ter um líder integrante, que fará a entrega do trabalho final.
# 
       _=,_         
    o_/6 /#\        
    \__ |##/        
      ='|--\         
       /   #'-.     
       \#|_   _'-. /
        |/ \_( # |" 
       C/ ,--___/
   
   Apresentado no dia 23 de novembro de 1996, o Tamagotchi era uma espécie de chaveiro que abrigava um bichinho virtual que pedia por doses regulares de comida virtual, atenção virtual e carinho virtual. Agora, você! Isso mesmo, você, junto com seu tempo de desenvolvimento, terá a honra de implementar uma versão dessa febre dos anos 90.

O animal de estimação virtual terá as seguintes informações atreladas a ele:

 **Tempo de vida**: inicia com 0 dias vivo, a cada 24 horas, envelhece um dia. O tempo de vida máximo é de 7 dias.

 . **Felicidade**: começa em 5. Comer ao estar com fome, brincar e dormir, aumenta esse atributo. Ser solicitado a comer ou ficar muito tempo sujo e sem diversão (jogar), diminuir esse atributo. O valor máximo para esse atributo é 10. Caso o atributo felicidade chegue a zero, o bichinho virtual morre de tristeza 😕 .

 . **Limpeza**: Esse atributo inicia com 10 pontos. Ao passar o tempo sem tomar banho, esse atributo diminui. Um bichinho super sujo morre por sujeira. Tomar banho aumenta esse atributo. Tomar banho estando limpo diminui o atributo felicidade.

 . **Fome**: Esse atributo inicia com 0. Ao passar o tempo, esse atributo aumenta. Um pet faminto morre de fome. Como diminuir esse atributo, até chegar ao máximo de zero. Tentar alimentar um animal de estimação contra sua vontade ou deixá-lo triste.

 . **Doente**: Esse atributo indicará se o animal está ou não doente. Ele poderá ficar doente ao acaso (de maneira pesquisada). Caso ele esteja doente, a cada 8 horas ele deverá ter chance de se curar sozinho. Isso aconteceu com 33,3% de chance após 8 horas do início da doença. Após 16 horas ele terá 66,6% de chance de ser curado e após 24 horas ele estará curado.

O projeto deve conter todas as funcionalidades incluídas na seção do menu a seguir. Além disso, ao iniciar o programa pela primeira vez, o usuário deverá escolher o nome para seu ‘animal de estimação virtual’. A partir daí, todas as frases devem ser personalizadas para chamar o bichinho pelo nome escolhido.

O trabalho consiste em desenvolver um projeto funcional de um bichinho virtual. O algoritmo deve ter um menu inicial, com as seguintes opções:

###

Projeto Virtual Pet 2023
<(^_^)>    (•_•)    _(x.x)_
Escolha uma opção a seguir: 
1.	Avançar o tempo
2.	Alimentar
3.	Jogar
4.	Dar banho
5.	Ver status
6.	Desligar


## 1.1 Detalhamento de funções

**Avançar o tempo**: Ao escolher essa função, o jogador faz o pet “avançar 8 horas de vida” em seu tempo. Isso impactará em diversas das funcionalidades do bichinho virtual. A cada 24 horas passadas, o animal envelhece um dia. O tempo de vida máximo para o pet é de 7 dias, após isso, ele morre de velhice. Nesse caso, o jogador 'ganha o jogo', pois fez com que seu bichinho vivesse feliz até o fim. A cada vez que o tempo avança, o animal modifica os seguintes status: A fome aumenta em 3. A felicidade diminui em 2. A Limpeza diminui em 2.

**Alimentar**: Ao alimentar o pet, sua fome diminuirá em 4 pontos. Chegando ao máximo de fome 0. Tentar alimentar um animal de estimação que está com fome 0, fará com que sua felicidade diminua em 2 pontos.

**Jogar**: Ao escolher a função jogar, o pet e o usuário farão uma partida de pedra, papel e tesoura. Caso o pet vença, sua felicidade aumentou em 5 pontos. Caso ele perca, sua felicidade aumentou em 3 pontos.

**Dar banho**: A função de dar banho fará com que a limpeza do seu pet chegue a 10 pontos. A cada 8 horas, o animal perde 2 pontos em limpeza. Tentar dar banho em um pet com 10 pontos de limpeza, fará com que ele reduza a felicidade em 6 pontos.

**Ver status**: A função ver status deve mostrar ao usuário todas as informações pertinentes para que o usuário possa cuidar de seu animal de estimação da maneira adequada. Também deve mostrar a idade atual do animal de estimação. Extra: O programador pode disparar mensagens fora dessa função para alertar ao usuário quando seu animal de estimação precisar de cuidado urgente, para tentar evitar sua morte precoce.

Caso o animal morra de fome, tristeza ou sujeira, o programa deverá encerrar, mostrando uma mensagem para o usuário do tempo de vida do animal e informando a causa de sua morte precoce.

## 2. APRESENTAÇÃO
O trabalho deverá ser entregue até dia 16/10 . Apresentações acontecerão na próxima aula a partir desse dia.
O trabalho deve estar no github. O LINK do repositório deve ser enviado via email pelo líder da equipe (Não é necessário enviar o código pelo email.). O restante do grupo não deve enviar NADA.
Arquivos com problemas de compilação confiança nota zero. O professor não receberá outro arquivo no momento da entrevista, o arquivo que será compilado será o arquivo enviado ao professor.
Ao aluno que não enviar o código fonte, será atribuída nota zero.
Não serão recebidos trabalhos atrasados. Caso o aluno não submeta o trabalho até o limite de dados, uma nota zero será atribuída aos alunos.
FLAGRANTES DE CÓPIAS DE TRABALHOS OCASIONARÃO EM NOTA ZERO PARA TODOS OS TRABALHOS SEMELHANTES.
O trabalho deverá ser apresentado ao professor em dados e horários definidos. A não comparação de um dos membros do grupo resultará em nota zero para o aluno que faltar. O questionamento será feito de forma direcionada aos alunos do grupo entrevistado. A nota de cada aluno é individual, sendo esta dada por:
notafinal = notaProjeto * notaEntrevista

Onde a notaEntrevista pode variar de 0 a 1.
A endentação de código, comentários e qualidade da solução farão parte da avaliação do projeto.
Observações⚠️
 O professor em hipótese alguma ajudará na construção do código.
 O professor poderá tirar dúvidas sobre o enunciado do problema as funcionalidades pretendidas.
