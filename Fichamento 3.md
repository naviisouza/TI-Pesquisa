# OUI-UX Design Using User Centred Design (UCD) Method

G. Goel, P. Tanwar and S. Sharma, "UI-UX Design Using User Centred Design (UCD) Method," 2022 International Conference on Computer Communication and Informatics (ICCCI), Coimbatore, India, 2022, pp. 1-8, doi: 10.1109/ICCCI54379.2022.9740997.

## 1. Fichamento de Conteúdo

O artigo trata da economia de energia na execução de aplicações _Bag-Of-Tasks_ (BoT) em infraestrutura de computação distribuída que usa o poder computacional de computadores que não estão em uso pelos seus usuários. Esse é o caso das grades computacionais oportunistas. Quando são submetidas, aplicações BoT usam muitos computadores da infraestrutura, cada um para executar uma tarefa da aplicação. Quando não há uma aplicação a ser executada, tais computadores ficam ociosos esperando a chegada de uma nova aplicação. Nesses momentos eles consomem energia em fazer qualquer computação útil. Diante desse problema, o artigo investiga o uso de três grupos de estratégias de economia de energia: 1) _sleeping states_, que são standby e hibernate; 2) _wake-up strategies_, que são Most Recently Sleeping (MRS) e Energy Aware (EA); e, 3) _scheduling strategies_, que são First Come First Served (FCFS), Fastest Processor to Largest Task (FPLT), Most Energy-Efficiency First (MEEF), Most Energy-Efficient to Largest Task (MEELT). São refeitas simulações da grade com até 350 máquinas e medindo economia de energia e o _slowdown_ em comparação ao _baseline_, que é manter as máquinas ociosas. Os resultados mostram que: 1) as estratégias são equivalentes quanto ao reduzido impacto no tempo de resposta, e 2) todas as _wake-up strategies_ geram economia de energia, sendo a EA gera maior economia que o MRS em cenário de alta contenção; 3) o _sleeping state_ hibernate também gera maior economia que o estado standby, sendo que ambos geram economia em relação ao estado ocioso.

## 2. Fichamento Bibliográfico
* _Bag-of-Tasks_ (BoT, aplicação do tipo saco-de-tarefas): aplicação composta por uma grande quantidade de tarefas que não se comunicam entre si e que podem ser executadas de forma independente uma das outras (página 1)
* _Wake-up strategy_ (estratégia de escolha do recurso a ser acordado): usada para escolher qual máquina acordar primeiro quando chegar uma nova aplicação para ser executada (página 5)
* _Sleeping states_ (estratégia de dormência): definidas pela Advanced Configuration and Power Interface (ACPI) e em que partes da máquina são desligadas, gerando economia de energia em relação a manter a máquina ociosa (página 5) 
* _Scheduling strategy_ (estratégia de escalonamento): usada para escolher qual máquina deve executar cada tarefa. (página 5)


## 3. Fichamento de Citações
* _"According to seasoned product designers, good research drives design decisions, and doing research early in the process may save a lot of time and money in the long run."_
* _"Because of the product's complexity, time, resources available, and a number of other considerations, the product research phase is possibly the most changeable of all project phases."_ 
* _"To finish this project, a UCD model was employed. The preliminary review of requirements will be doneby querying and collecting user informationthroughout the requirements formulation process."_
* _"For 30 participants, a brief survey was conducted using Google Form. Only 26 people were qualified since they replied yes to the first question. No personal information was taken from participants and the survey was only for research purpose. The goal of this survey is to learn about UI-UX evaluations and testing for the implemented design from users who have had similar experiences."_
* _"We get all the responses for the questions concerning the app's design elements, the main menu pageand its experience, and the overall UI-UX of the app, with the most common responses being 4,5 and 5 points respectively. This indicates that the responders appreciated the app's UI in these three areas and found it to be seamless to use."_
