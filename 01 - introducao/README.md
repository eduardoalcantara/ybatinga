# 1 INTRODUÇÃO

Desde a concepção dos primeiros computadores como o ENIAC (1946), do
tamanho de uma casa, até a atualidade dos dispositivos móveis, o software esteve
presente como a interface principal que nos permite programar as ações destas
complexas máquinas. No início utilizaram rudimentares cartões perfurados para
passar instruções ao hardware, mas depois foram criando e evoluindo as linguagens
de programação para refletir à alta disponibilidade e poder de processamento que os
computadores modernos alcançaram (CAMPBELL-KELLY, 2003).

A velocidade desta evolução, nos parâmetros da Lei de Moore, fez com que
os paradigmas sofressem várias alterações durante as últimas décadas. Passaram
de computadores exclusivos, cujo software era desenvolvido especificamente para
tal unidade, para microcomputadores feitos em larga escala, cuja arquitetura
padronizada permitiu o desenvolvimento de aplicativos que agora podiam ser
executados em milhões de computadores com o mesmo código de máquina. As
linguagens de programação seguiram o mesmo caminho, padronizando-se para
atender a demanda mundial por novas soluções para proprietários residenciais e
corporativos (BORKAR; CHIEN, 2011).

Entretanto, com os impulsos da globalização e da Internet, os sistemas de
informação sofreram outra mudança de paradigma. Se antes eles eram
desenvolvidos em sua totalidade para executar localmente em arquiteturas de
hardware específicas, e utilizadas por apenas um usuário por máquina, agora eles
residem, na sua maioria, em servidores remotos, para serem executados por um
número indefinido de usuários, de forma paralela, utilizando as mais variadas
plataformas de hardware e software para acessar esses aplicativos (BYRNE, 2013).
Desta vez, as linguagens de programação e suas camadas de apoio não
tiveram total êxito em acompanhar esta evolução, e o que se vê é o uso exagerado
de bibliotecas, frameworks de linguagens de programação e muitas camadas
intermediárias de software, só para permitir que a criação de aplicativos modernos
usando a mesma infraestrutura e padrões estabelecidos nas décadas de 80 e 90,
como HTML e HTTP, que foram concebidos para transmitir dados estáticos, mas
que hoje são a base para aplicações dinâmicas remotas (BORKAR; CHIEN, 2011).

Neste ambiente, vem se destacando cada vez mais a linguagem Java, por ter
código aberto, ser constantemente evoluída por uma comunidade internacional de
empresas e desenvolvedores autônomos, e principalmente por ser executado em
múltiplas plataformas de hardware e software sem mudança no código fonte das
aplicações já que os aplicativos são executados por um interpretador ao invés de
serem compilados em código de máquinas específicas (DEITEL, 2010).

Porém até mesmo o Java foi baseado em uma linguagem bem mais antiga: o
C, e sua biblioteca base possui apenas um suporte primitivo a requisições remotas,
e nenhum outro suporte nativo ao que é necessário para desenvolver aplicações
Web. Por isso, somente oito anos depois da criação da linguagem, foi desenvolvida
a plataforma chamada de J2EE, que continha um framework de bibliotecas para
Web e um servidor de aplicações corporativas escaláveis. Dezesseis anos depois,
em sua oitava versão, a plataforma Java ainda depende de vários outros frameworks
oficiais e outros desenvolvidos pela comunidade, para resolver problemas de
segurança, rede, consistência de sessões de usuário, camadas de aplicativo e de
negócio, abstração de dados e desenvolvimento de interface com o usuário.

Atualmente, a lei de Moore está emperrada em fatores físicos, como o calor,
que limitam o aumento da velocidade dos processadores. Apesar disso, foram
atingidas velocidades de processamento tão altas, que aplicações residenciais e
corporativas de médio porte não encontram dificuldades para funcionar nem mesmo
em pequenos smartphones. Segundo Borkar e Chien (2011), esta zona de conforto
tem mudado o foco dos projetistas de software, da antiga preocupação com o
desempenho e consumo de memória, para o alto investimento em interface com o
usuário – efeitos visuais e sonoros – que individualmente parecem inofensivos, mas
que podem engessar o funcionamento de hardware e software em termos de
escalabilidade. O grande número de frameworks utilizados um sobre o outro também
é um fator de perda de desempenho, pois inclui, em cada novo projeto, milhões de
linhas de código em recursos que nem sempre são utilizados em sua totalidade.
Este desperdício pode ser, em alguns casos, humanamente impossível de detectar,
necessitando de ferramentas que atestem o consumo de hardware necessário para
executar a aplicação, assim como aumento no consumo de energia e
consequentemente o aquecimento de todo o sistema.

Neste processo, o que é plenamente notável ao entrar na comunidade Java, é
o aumento da curva de aprendizagem, que de acordo com De ROSA (2013) , é a
constatação do aumento da dificuldade de aprender ou dominar plenamente todos
os processos e normas de desenvolvimento, todas as ferramentas e recursos
disponibilizados à equipe de desenvolvimento e ao indivíduo, considerando o grande
número de tecnologias e frameworks inseridos na demanda, cada um com suas
regras, peculiaridades e configurações individuais e os resultados do entrelaçamento
entre todos eles. É possível comparar isso à diferença entre operar um carro
automático e operar um avião intercontinental moderno.
Pode-se imaginar que quanto mais complexos e poderosos os sistemas
computacionais se tornaram, mais difícil seria o desenvolvimento de aplicações. Mas
se fosse verdadeira esta premissa, também poderia ser mais complexa a sua
operação, mas o que acontece é o contrário. Também percebe-se que o
desenvolvimento de código aberto tem oferecido trégua aos desenvolvedores do
mundo todo ao compartilharem suas soluções, evitando o retrabalho no
desenvolvimento das funções mais genéricas às mais específicas (NOYES, 2010).

É possível dar o próximo passo na evolução do software, desprendendo as
aplicações da Web e criando novas tecnologias mais condizentes com a arquitetura
de sistemas, ao invés de usar o uma antiga tecnologia para texto com hiper-ligações.
Porém o mundo de hoje está tão imerso na Web, que uma mudança drástica nos
paradigmas poderia custar fortunas, dividir opiniões, e demoraria muito tempo para
se fazer uma migração completa.

Enquanto isso, é possível pensar em soluções melhores para desenvolver
aplicativos Web mais ecológicos – que não consumam mais recursos de hardware
do que deveriam, e cuja curva de aprendizado para seu projeto e desenvolvimento
seja mais baixa – acessível a programadores novatos e experientes.

##1.1 OBJETIVO GERAL

É no contexto destas problemáticas, que surge a proposta contida neste
trabalho, cujo objetivo geral é projetar uma nova arquitetura de plataforma Web,
modelada em forma de framework padronizado, para que possa ser implementada
em qualquer linguagem de programação e banco de dados desejado, mantendo-se
as características principais, que são:

- Programar e executar aplicativos como Microserviços independentes entre si;
- Permitir o projeto e criação de software focado no modelo de negócio;
- Oferecer camada dupla de segurança independente do protocolo utilizado;
- Oferecer métodos de comunicação via HTTP, TCP e UDP entre cliente e servidor e entre os próprios Microserviços através da plataforma;
- Permitir gerenciamento padronizado de usuários, pela plataforma;
- Permitir a redundância de servidores e espelhamento de configurações e bases de dados, bem como distribuir seu conteúdo em qualquer modelo;
- Permitir uma baixa curva de aprendizado no desenvolvimento, configuração e operação da plataforma;
- Permitir o baixo consumo de recursos energéticos e de hardware;
- Permitir a inversão de controle dos requisitos não funcionais, da aplicação para a plataforma.

##1.2 OBJETIVOS ESPECÍFICOS

Para este projeto, será necessário modelar várias tecnologias, todas
convergindo para o propósito principal, mas que pareçam uma só entidade,
transparente para os desenvolvedores, operadores e usuário final. Portanto, para os
objetivos específicos deste trabalho, tem-se:

- Projetar um serviço para gerenciar sessões de usuário, transportar dados e mediar serviços da plataforma;
- Projetar um modelo de comunicação criptografada independente de protocolo;
- Criar três modelos de bancos de dados, um para a configuração da plataforma, um para gerência de usuários e outro para a o modelos de negócio e serviços disponíveis;
- Projetar um modelo administrativo flexível que permita tanto opções de customização, como o métodos de Convenção sobre Configuração, que permitam uma boa curva de aprendizado para todos os níveis profissionais;
- Apresentar cenários de aplicação destas propostas;
- Disponibilizar o projeto em repositórios públicos, para ser compartilhado e melhorado pela comunidade internacional;

##1.3 METODOLOGIA

Este projeto é resultado de longas reflexões teóricas, observações técnicas, 
desenvolvimento prático, coleta de requisitos, conversas em fóruns profissionais e
tem como base mais de quinze anos de trabalho do autor em desenvolvimento de
sistemas para computadores, web e dispositivos móveis, incluindo pesquisas
bibliográficas e cursos nas áreas de gerência de projetos e desenvolvimento Web.

Serão detalhadas as especificações para o desenvolvimento deste
Framework, bem como o comportamento padrão dos objetos desenvolvidos, que
poderão ser desenvolvidos em qualquer linguagem de programação compatível com
a arquitetura cliente/servidor e qualquer Sistema Gerenciador de Banco de Dados
(SGBD) que permita a criação de stored procedures, e que seja regrada a fim de que
qualquer versão desenvolvida da Plataforma tenha capacidade de se comunicar e
compartilhar recursos e serviços entre si. Serão sugeridas tecnologias open-source
gratuitas para facilitar sua replicação pela comunidade de desenvolvimento.

##1.4 ORGANIZAÇÃO

Este trabalho foi dividido em três capítulos, além da Introdução e Conclusão,
e são organizados de acordo com as necessidades informacionais de um projeto de
desenvolvimento de sistemas. São eles:

1. Introdução;
2. Fundamentação e Conceitos: enumera-se as fundamentações teóricas, justificativas técnicas e conceitos introdutórios necessários ao entendimento científico das intenções deste trabalho;
3. Desenvolvimento do Projeto: desenvolvem-se os modelos e as soluções de projeto de cada objeto do framework, necessários à criação de plataforma de microserviços, enumerando vantagens técnicas e efetivas, seus contextos, problemas, vantagens, estrutura lógica, dependências, padrões relacionados e exemplos de funcionamento e diagramas necessários;
4. Aplicações e Resultados: demonstra-se a usabilidade deste modelo de serviço no mundo real, aplicando situações de concorrência de usuários, escalabilidade, segurança, disponibilidade, além de serviços, instituições, indivíduos e outras tecnologias que podem beneficiar-se deste modelo de plataforma e desenvolvimento de sistemas, comparando-o tecnicamente com os paradigmas utilizados atualmente;
5. Conclusão.

##1.5 TRABALHOS RELACIONADOS

Em 2014, Chris Richardson estava publicando um artigo intitulado Pattern:
Microservices Architecture, e o resultado deste trabalho foi a criação de sua
própria plataforma chamada Eventuate, onde ele aplica os conceitos de
microserviços para resolver problemas de gerenciamento de dados distribuídos. No
mesmo ano, a Amazon Cloud Computing começou a dar suporte ao chamado
Serverless Computing, que apesar do nome, utiliza servidores para executar
funções sob demanda, o que é algo muito parecido com a ideia de executar
procedures, mas seu objetivo era poder cobrar os usuários por cada chamada a
estas funções, ao invés de cobrar por tráfego ou tempo de uso. Em 2016 a IBM
lançou o produto OpenWhisk, que é uma plataforma serverless com código aberto,
assim como a Google Cloud Functions, que segue a mesma ideia da IBM.

Todos estes trabalhos seguem uma filosofia de baixo acoplamento, economia
de recursos, independência de serviços e distribuição de processamento. Mas não
foram encontrados, até agora, trabalhos concorrentes ao que se propõe este Projeto
de Framework, considerando suas especificações e serviços oferecidos em
conjunto, especialmente na forma como o Framework sugere o uso de bancos de
dados como fonte de funções acessíveis sem APIs.

##1.6 RESULTADOS ESPERADOS

Após o desenvolvimento do projeto deste framework, espera-se que as
plataformas desenvolvidas com ele sejam capazes de:

* Transformar o paradigma de desenvolvimento de sistemas ao estimular a quebra de sistemas monolíticos (fortemente acoplados) em Microserviços distribuíveis pela rede, mudando o foco do desenvolvimento na camada de controle da aplicação e descentralizando-a para processar os modelos de negócio diretamente nos bancos de dados, assim como processar a interface de usuário totalmente na camada do cliente;
* Diminuir o tamanho do servidor (serverless);
* Diminuição da curva de aprendizagem, tanto para configurar, quanto para desenvolver novos serviços;
* Diminuição do consumo dos recursos de hardware e software na execução da Plataforma e seus serviços instalados;
* Padronização do acesso aos recursos de serviços acoplados;
* Padronização da administração de recursos, serviços e usuários;
* Aumento da segurança e integridade dos bancos de dados envolvidos;
* Aumento da segurança na troca de informações entre clientes e servidores;
* Aumento da produtividade no desenvolvimento de aplicações.
