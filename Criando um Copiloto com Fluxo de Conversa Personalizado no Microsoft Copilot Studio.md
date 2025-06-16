
# Criando seu primeiro Copiloto no Microsoft Copilot Studio



## Requisitos
Para utilizar o Microsoft Copilot Studio, primeiramente será preciso ter ou criar uma conta no Microsoft 365, umas das opções é acessar copilotstudio.microsoft.com ou mesmo procurar o site através do Google. No site de Copilot é possível adquirir uma assinatura trial para fins de estudos, se o seu objetivo é se familiarizar com a ferramenta. Vale lembrar também que o programa de desenvolvedor da Microsoft também permite acesso a ferramenta para fins de teste e desenvolvimento. 


## Criar um Copilot em Branco
Para criar um Copilot em Branco isto é do zero, deve-se acessar o  [copilotstudio.microsoft.com](http://copilotstudio.microsoft.com) Clica-se em criar Novo Agente. A Microsoft em alguns casos trás uma ferramenta semelhante ao Teams onde a IA da Microsoft conversará pedindo as instruções para a criação do bot. É possível pular essa tela e ir para a tela de criação em branco, onde poderão ser definidas as características como nome, logo, idioma, etc. Também é importante se adicionar uma descrição e uma base de conhecimentos, mas é mais interessante adicionar essa base mais para frente. Nesse momento o que está sendo criado é a estrutura. Vale lembrar que se foi criado uma Solução é possível vincular esse copiloto a essa Solução. Tudo definido, clica-se em criar e aguarda-se a criação do copiloto.
Como o foco aqui é o uso da IA Generativa se recomenda que a criação do agente seja feita em inglês.
## Customizar um Tópico
Para customizar um tópico, deve-se ir em tópicos e em adicionar um novo tópico. Ali será possivel adicionar um tópico de acordo com uma descrição ou adicionar um tópico em branco. 
Escolhemos tópico em branco, adiciona-se as frases de gatilho que combinem com o tema desejado. Feito isso em nova ação clica-se nas opções avançadas e em respostas generativas. Define-se o imput que será a íutima mensagem do usuário e pode-se apontar uma base de conhecimentos também. Clica-se em salvar e reaiiza-se testes. É importante resetar o chat ao fazer o testes.  
## Personalizar Uma Mensagem de Erro de Tópico
Essa customização é importante porque ocasionalmente o chat pode não conseguir uma resposta coerente ou pode não entender a pergunta. ele caíra então ou no conversation bot ou então no fall back. 
Nessa situação é possível criar uma mensagem de erro personalizada e direcionar o usuário para algum canal de atendimento, criando uma derivação dentro das configurações do bot. 

## Controlar a Qualidade da Resposta 
Quando se utiliza a resposta generativa existem algumas formas de melhorar a qualidade das respostas. Uma delas é dentro dos tópicos em data sources no conversation boor é possivel editar as bases de conhecimentos utilizadas. Também existe a opção de autorizar ou não o uso dos conhecimentos gerais da própria IA do bot que atualmente utiliza o GPT4.
Outra possibilidade é editar os prompts criando um prompt que utiliza a própria pergunta do usuário como forma de refinar a pesquisa. 
Entretanto é preciso algum cuidado porque o chat tem um limite de caracteres máximo que ele pode usar nas variáveis de pesquisa.
Também é possível limitar a "criatividade" da IA de forma que a IA procure as respostas mais próximas do esperado, limitando a criatividade das respostas tendemos a ter respostas mais precisas.
Essa comfiguração de criatividade pode ser feita também no agente como um todo e não somente dentro do tópico. 
