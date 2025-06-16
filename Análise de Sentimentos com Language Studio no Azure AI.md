
# Análise de Sentimentos com Language Studio no Azure AI


## Análise de Texto e Resposta a Perguntas
O Language Studio é uma plataforma que analisa mensagens de textos procurando extrair diversas informações como por exemplo idioma, sentimentos, local, tempo, entre outras informações por meio de palavras chaves. 
Ele também permite prever, mensurar o sentimento presente no texto, procurando avaliar as motivações do autor do texto até mesmo aquelas involuntárias que transparecem na forma como o texto foi escrito.
## Serviço de Boot do Azure
O serviço de boot do Azure utiliza a Análise de linguagem do Azure e o boot para fornecer respostas ao cliente. Entretanto como acontece com todos os serviços de IA a qualidade de suas respostas depende do volume de informações que ele tem acesso.
Ele pode ser alimentado de diversas formas como um chat, voz ou outros meios. 
Um ponto importante é que esse serviço precisa ser constantemente testado e avaliado para comprovar que o bot de fato consegue atender o usuário ou mesmo que o serviço se mantém atualizado com o serviço que ele atende.
Também essa ferramenta é extremamente versátil podendo ser alimentada por diversos meios e e trabalhar com diversas ferramentas adaotando seus scripts à ferramenta e cliente a que ela se direciona. 
## Compreensão de Linguagem Coloquial
A linguagem coloquial é a linguagem do dia a dia, menos formal e flexível. Ainda que em certos contextos é necessário que a Inteligência Artificial seja mais formal no dia a dia muitas vezes ela precisa compreender uma linguagem menos formal. 
Para que isso seja possível entram em jogo três fatores a declaração isto é o que pode ser dito, o que é para ser feito; a entidade, isto é quem ou o que faz a ação e por fim a intencionalidade, que indica a ação a intenção do usuário. 
O intuíto é que o usuário possa "dar ordens" aos dispositivos por meio da IA. Nesse contexto algumas questões se tornam importantes como o reconhecimento de voz, se é interessante ou não limitar o acesso por meio de uma assinatura vocal por exemplo. 
Também ainda pensando em reconhecimento e recursos de fala também temos a conversão de textos escritos para fala ou o inverso a conversão da fala em textos. Tal funcionalidade torna-se importante em contextos de acessibilidade, mas não somente, pode-se pensar em atendimentos automáticos de mensagens quando por algum motivo o usuário não pode utilizar um telefone por exemplo.
## Conhecendo o Estufio de Fala
O Estúdio de Fala permite a conversão de texto em fala ou vice e versa. Para isso devemos entrar em http://speeche.microsoft.com logar com o mesmo login da criação do portal do Azure. 
Dentro do Language Studio em configurações clica-se em criar  novo recurso, selecione a assinatura do Azure, dê um nome para o recurso, selecione a região, padrão S0 e um grupo de recursos, por fim clica-se em ok.
Depois pode-se ir em conversão de fala em texto, em tempo real. É preciso selecionar o idioma do arquivo que queremos transcrever para que o Studio possa trabalhar. 
No próprio Estúdio tem uma farta documentação de como utlizar os recursos do Estúdio. 
É importante ao utlizar o serviço mensurar os custos já que os serviços de IA possuem custos de utilização.  
## Conhecendo o Language Studio
O Language Studio permite fazer uma análise estratégica da linguagem, ele permite rastrear informçaões embutidas em um grande quantidade de texto como por exemplo a análise de uma caixa de comentários de um serviço por exemplo.
Da memsma forma dentro do Studio criamos um novo recurso, escolhemos um nome, valida-se os campos, seleciona-se a assinatura e aguarda-se a criação do recurso. 
seleciona-se a subscrição que será o recurso criado, escolhe-se a caixa de classificação de texto e análise de textos e sentimentos, seleciona-se o idioma e clica-se em examinar. 
Um ponto interessante na análise são as palavras chave que permitem identificar as bases da análise.
Da mesma forma que o Estúdio de Fala o Language Studio tem uma farta documentação apresentando recursos e funcionalidades. 
