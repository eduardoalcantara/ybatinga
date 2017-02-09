# ybatinga
Framework para Plataforma de Microserviços Distribuídos

A palavra ybatinga significa nuvem (a conotação atual da Internet) em tupi-guarani e não foi a escolha inicial, nem a mais aceita para nomear este framework, porém é uma homenagem ao povo da região norte do Brasil e ao potencial que tem para contribuir com ideias sustentáveis.

Este projeto trata da proposta de um novo tipo de Framework, que não é usado para complementar uma linguagem de programação, mas sim para especificar e coordenar o desenvolvimento de Plataformas Cliente/Servidor para Microserviços e Funções Distribuídas, que possam ser desenovlvidas em qualquer linguagem de programação compatível sem perder sua capacidade de comunicação umas com as outras, de forma rápida, econômica e com baixa curva de aprendizagem para sua implementação, configuração e operação, assim como de seus serviços acoplados.

Este é o resultado de meu Trabalho de Conclusão do Curso de Sistemas de Informação, pela Universidade Federal do Pará, em 2017, e trata-se de um sonho antigo, uma visão de que podemos desenvolver sistemas úteis e acopláveis de forma rápida, sem nos preocuparmos com os requisitos não-funcionais, que serão totalmente administrados pela Plataforma de Aplicação.

**RESUMO:**

Os esforços em transformar uma linguagem de programação genérica como Java em uma ferramenta completa para desenvolver aplicações Web tem tornado muito difícil acompanhar sua crescente curva de aprendizado por conta de diversos frameworks acoplados que tem se tornado padrão de desenvolvimento. Um caminho difícil de ser mudado, por conta de sua popularidade em diversos segmentos, reforçada pelo marketing agressivo de gigantes como a Oracle, sua atual proprietária. Este trabalho propõe, em contrapartida, o uso de plataformas distribuídas em microserviços e funções independentes de APIs (inclusive para acesso a bancos de dados) cujas implementações deverão seguir as especificações de um framework projetado para permitir a baixa curva de aprendizagem, o rápido desenvolvimento, maior economia de recursos de TI e a total compatibilidade com todas as plataformas desenvolvidas sob suas diretrizes, independente de quais linguagens de programação serão usadas, tanto para implementação da plataforma quanto para os serviços disponibilizados, que podem pertencer a qualquer categoria padrão de mercado, como gestão de usuários e acesso autenticado, criptografia forte independente de protocolo, repositório de arquivos e gestão inteligente de armazenamento, comunicação distribuída síncrona e assíncrona através de mensageria, modelagem de saída dinâmica de interface ao usuário, streaming multimídia em tempo real e execução de procedures de banco de dados com retorno direto à camada do cliente.

Palavras-Chave: Framework de Implementação. Plataforma de Sistemas Distribuídos. Microserviços. Funções Serverless

**ABSTRACT:**

The efforts to transform a generic programming language like Java in a complete tool to develop Web applications has been turning too hard to keep following its growing learning curve because of its many coupled frameworks which have become standard development. It’s a difficult path to change, due to its popularity in many segments, reinforced by the aggressive marketing of giants like Oracle, its current owner. This paperwork proposes, in counterpart, the use of distributed platforms into Microservices and API independent functions (inclusive for database access) in which the implementations should follow the specifications of a framework designed to have a low learning curve, fast development, higher economy of IT resources and full compatibility with all platforms developed under its guidelines, independently of each programming languages will be used, both for the implementation of the platform and for the services provided, which may belong to any standard market category, such as user management and authenticated access, cryptograph that is strong and protocol independent, file repository and intelligent storage management, synchronous and asynchronous distributed communication through messaging, dynamic user interface modeling, Real-time multimedia streaming and execution of database procedures with a direct return to client layer.

Keywords: Implementation Framework. Distributed Systems Platform. Microservices. Serverless Functions

**LISTA DE ILUSTRAÇÕES**

- Esquema 1	Modelagem de Classes do Gestor de Requisições (Java)	
- Figura 1  Quebra de arquiteturas, de monolítica até serverless
- Figura 2	Analogia entre funções e peças de LEGO e quebra-cabeças	
- Esquema 2	Tabelas do banco e as referências entre elas	
- Código 1	Parte da estrutura da classe $platformScope	
- Código 2	Parte da estrutura da função action.request()	
- Fluxograma 1	A Plataforma em uma arquitetura não-distribuída	
- Fluxograma 2	A Plataforma em uma arquitetura parcialmente distribuída	
- Fluxograma 3	A Plataforma em uma arquitetura totalmente distribuída	
- Figura 3	Telas de login e operação do Sistema Acesso Servidor	
- Figura 4	Telas de operação e configuração do sistema TRE-TV	
- Figura 5	Exemplo de saída do comando /relógio do TRE-TV	
- Gráfico 1	Tamanho do aplicativo e das respostas HTTP	
- Gráfico 2	Tempo mínimo de carregamento da página	
- Gráfico 3	Tempo e tamanho de carregamento dos serviços do TRE-TV	

**LISTA DE QUADROS E TABELAS**

- Quadro 1	Camadas do Java EE e algumas de suas especificações	
- Quadro 2	Diferenças básicas entre protocolos de comunicação	
- Quadro 3	Parâmetros básicos para requisições da plataforma	
- Quadro 4	Estrutura de uma requisição no formato URL	
- Quadro 5	Ordem de passagem de parâmetros via URL limpa	
- Quadro 6	Funcionamento do Gerente de Requisições	
- Quadro 7	Regras para uso do /wsdl de acordo com parâmetros inclusos
- Quadro 8	Convenções e Configurações do Framework	
- Quadro 9	Tabelas básicas e obrigatórias do Framework	
- Quadro 10	Tabelas de gestão e operação de serviços do Framework	
- Quadro 11	Tabelas de controle e configuração de licenças	
- Quadro 12	Tabelas para serviços específicos na Plataforma	
- Quadro 13	Tabelas com listagens tipo ENUM	
- Quadro 14	Estrutura principal do objeto $platformScope	
- Quadro 15	Funções JavaScript para acesso à Plataforma	
- Quadro 16	Funções JavaScript para criptografia de dados	
- Quadro 17	Linguagens de programação para a camada cliente	
- Quadro 18	Módulos do Gestor de Requisições
- Tabela 1	Especificações do Projeto de Framework de Plataformas

**SIGLAS E ABREVIAÇÕES**

- AJAX	Asynchronous Javascript and XML
- AMQP	Advanced Message Queuing Protocol
- ANSI	American National Standards Institute
- API		Application Programming Interface
- ASCOM	Assessoria de Comunicação
- ASP		Active Server Pages
- BD		Banco de Dados
- BIN		Binary File
- CDN		Content Delivery Network
- CGI		Computer Generated Imagery
- CoC		Convention Over Configuration
- CORS	Cross-Origin Resource Sharing
- CPU		Central Process Unit
- CRM		Customer Relationship Management
- CRUD	Create, Read, Update, Delete
- CSS		Cascading Style Sheets
- CSV		Comma-Separated Values
- DAO		Data Access Object
- DB		Data Base
- DBA		Data Base Administrator
- DDoS	Distributed DoS Attack
- DDNS 	Dynamic Domain Name Server
- DHTML	Dynamic HTML
- DI		Dependency Injection
- DLL		Dinamic Link Library
- DOM		Document Object Model
- DoM		Deny of Service
- DOS		Disk Operational System
- EE		Enterprise Edition
- EJB		Enterprise JavaBeans
- EPP		Empresa de Pequeno Porte
- EX		Exemplo
- EXE		Executable File
- FAQ		Frequently Asked Questions
- FK		Foreign Key
- FTP		File Transfer Protocol
- GPS		Global Positioning System
- GRP		Gerente de Requisições da Plataforma
- HTML	HyperText Markup Language
- HTTP	HyperText Transfer Protocol
- HTTPS	HTTP Secure / HTTP over SSL
- IDE		Integrated Development Environment
- IDX		Index
- IP		Internet Protocol
- IoC		Inversion of Control
- J2EE	Java 2 Platform Enterprise Edition
- JAAS	Java Authentication and Authorization Service
- JAX		Java API for XML
- JDBC	Java Database Connectivity
- JDK		Java Development Kit
- JMS		Java Message Service
- JPA		Java Persistence API
- JPQL	Java Persistence Query Language
- JRE		Java Runtime Environment
- JS		JavaScript
- JSF		JavaServer Faces
- JSON	JavaScript Object Notation
- JSONP	JSON with Padding
- JSP		JavaServer Pages
- JSTL	JavaServer Pages Standard Tag Library
- KB		Kilobyte
- LOG		Arquivo com histórico de atividades de um sistema
- MIN		Minutos
- MOM		Middleware Oriented Message
- MPE		Micro e Pequena Empresa
- MPS.BR	Melhoria do Processo de Software Brasileiro
- MS		Microsoft
- ms		milesegundos
- MVC		Model, View, Controller 
- MVVM	Model–view–viewmodel
- NAT		Network Address Translation
- OCCI	Open Cloud Computing Interface
- ORM		Object-Relational Mapping
- P2P		Peer-To-Peer
- PBQP-Sw	Programa Brasileiro da Qualidade e Produtividade em Software
- PC		Personal Computer
- PDF		Portable Document Format File
- PHP		Personal Home Page/forms interpreter
- PK		Primary Key
- QoS		Quality of Service
- RAD		Rapid Application Development
- RC4		Rivest Cipher 4
- RDBMS	Relational database management system
- RFC		Request For Comments
- RIA		Rich Internet Application
- RMI		Remote Method Invocation
- RPC		Remote Procedure Call
- RTCP	RTP Control Protocol
- RTF		Rich Text File
- RTP		Real-time Transport Protocol
- RTSP	Real Time Streaming Protocol
- SCV		Sistema de Controle de Versionamento
- SGBD	Sistema Gerenciador de Bancos de Dados
- SLA		Service Level Agreement
- SO		Sistema Operacional
- SOAP	Simple Object Access Protocol
- SP		Stored Procedure
- SQL		Structured Query Language
- SRTP	Secure Real-time Transport Protocol
- SSH		Secure Shell
- SSL		Secure Sockets Layer
- TCP		Transmission Control Protocol
- TCU		Tribunal de Contas da União
- TLS		Transport Layer Security
- TRE-PA	Tribunal Regional Eleitoral do Pará
- TV		Television
- TXT		Text File
- UDP		User Datagram Protocol
- UML		Unified Modeling Language
- UOL		Universo Online
- URI		Uniform Resource Identifier
- URL		Uniform Resource Locator
- URN		Uniform Resource Name
- VoIP	Voice Over IP
- W3C		World Wide Web Consortium
- WAR		Web application ARchive
- WML		Website Meta Language
- WS		Web Service
- WSDL	Web Services Description Language
- WWW		World Wide Web
- XHTML	Extensible HTML
- XLS		Arquivo no formato do Microsoft Excel
- XML		Extensible Markup Language
- XSLT	Extensible Stylesheet Language Transformations
- ZIP		Arquivo compactado no formato ZIP (conotativo de Zipper)

**REFERÊNCIAS**

ALURA. Curso de Java e Orientação a Objetos. Caelum. São Paulo, 2016.
Disponível em <https://goo.gl/co4SnM>. Acesso em: 09 Set 2016.

______. Java para Desenvolvimento Web. Caelum. São Paulo, 2016. Disponível em
<https://goo.gl/0swlst>. Acesso em: 10 Set 2016.

______. Laboratório Java com Testes, JSF e Design Patterns. Caelum. São Paulo,
2016. Disponível em <https://goo.gl/k0Rf19>. Acesso em: 10 Set 2016.

______. SOA na prática: Integração com Web Services e Mensageria. Curso
Intensivo em Belém sob demanda do TRE-PA: Caelum, v. FJ-36, 2015.

AQUINO JR, Gibeon S de. Desenvolvimento de Sistemas Web em Java:
Frameworks, Padrões de Projeto e Diretrizes para a Camada de Apresentação.
Recife, 2002. 129 p. Disertação (Pós Ciência da Computação)-UFPE

BORKAR, Shekhar; CHIEN, Andrew A. The Future of Microprocessors. Hillsboro:
ACM, 2011. Disponível em <https://goo.gl/QMSF0S>. Acesso em: 10 Set 2016.

BRUCE A, Tate. Beyond Java. Sebastopol: O'Reilly, 2005. 185 p.

BYRNE, David. Is the Information Technology Revolution Over?. Federal Reserve.
Washington, 2013. Disponível em <https://goo.gl/pYj6bf>. Acesso em: 06 Set 2016.

CAMPBELL-KELLY, Martin. From Airline Reservations to Sonic the Hedgehog: A
History of the Software Industry. Cambridge: The MIT Press, 2003. 372 p.

DE ROSA, Aurélio. Learning Curve: What it is and How it Applies to Information
Technology. Web Developer Blog. London, 2013. Disponível em
<https://goo.gl/GiRVA6>. Acesso em: 10 Set 2016.

DEITEL, Paul e Harvey. JAVA: Como Programar. Tradução Carlos Arthur Lang
Lisboa. 8. ed. Porto Alegre: Prentice Hall, 2010. 1152 p.

DMITRUK, Hilda Beatriz(Org). Cadernos metodológicos: diretrizes da metodologia
científica. 5. ed. Chapecó: Argos, 2001. 123 p.

FLANAGAN, David. JavaScript: O guia definitivo. 6. ed. Porto Alegre: Bookman, 2013. 1062 p.

FORRISTAL, Jeff. Site Seguro e Aplicações Web. Rio de Janeiro: Alta Books, 2002. 490 p.

GONÇALVEZ, Edson. Desenvolvendo Aplicações Java com JSP, Servlets, JSF,
Hibernate, EJB 3 Persistence e Ajax. São Paulo: Ciência Moderna, 2007. 776 p.

GUPTA, Arun. Monolithic to Microservices: Refactoring for Java EE Applications.
Miles to go 3.0. São Francisco, 2015. Disponível em <https://goo.gl/TQXq46>. Acesso em: 20 Nov 2016.

IBM. Who uses mainframes and why do they do it?. 2010. Disponível em
<https://goo.gl/jg5uqq>. Acesso em: 08 Jan 2017.

KUROSE, Jim; ROSS, Keith. Computer Network: A Top Down Approach. 6. ed.
Boston: Addison-Wesley, v. Slides, 2012.

LOBO, Edson. Curso de Engenharia de Software. São Paulo: Digerati, 2008.

LUCKOW, Décio Heinzelmann; MELO, Alexandre Altair de. Programação Java
para a Web. 2. ed. São Paulo: Novatec, 2015. 640 p.

MACVITTIE, Lori. Braceyourselves. Serverless is coming. F5 Networks. Seattle,
06/2016. Disponível em <https://goo.gl/foZ6ZA>. Acesso em: 09 Set 2016.

______. Cookies, Sessions, and Persistence. F5 Networks. Seattle, 07/2008.
Disponível em <https://goo.gl/bsO6Rr>. Acesso em: 09 Set 2016.

MALAVASI, Eike. Orquestração e Coreografia em SOA. Sensedia. Campinas, 2008.
Disponível em <https://goo.gl/rE5Cm8>. Acesso em: 12 Jan 2017.

MASSOL, Vincent; ZYL, Jason van. Better Builds with Maven: Um guia para
Maven 2.0. South California: Mergere Library Press, 2007. 301 p.

MELO, Ana Cristina Vieira de; SILVA, Flávio Soares Corrêa da. Princípios de
Linguagens de Programação. São Paulo: EdgardBlücher Ltda, 2003. 211 p.

NORTON, Peter; AITKEN, Peter; WILTON, Richard. Peter Norton: A Bíblia do
Programador. Tradução Geraldo Costa Filho. 3. ed. Rio de Janeiro: Campus, 1993.
640 p. Tradução de: PC Programmer's Bible.

NOYES, Katherine. 10 Reasons Open Source Is Good for Business. PC World. San
Francisco, 2010. Disponível em <https://goo.gl/900PeS>. Acesso em: 09 Set 2016.

O'BRIEN, James A. Sistemas de Informação. São Paulo: Saraiva, 2011. 430 p.

OLIVEIRA, Valéria. Desmistificando a pesquisa científica. Belém: EDUFPA, 2008.

PRESSMAN, Roger. Engenharia de Software. São Paulo: Makron, 1995. 1056 p.

RICHARDSON, Chris. Eventuate Platform: Solving DDM problems in a microservice
architecture. Eventuate.IO. 2016. Disponível em <http://eventuate.io/>. Acesso em: 09 Jan 2017.

______. Pattern: Microservices Architecture. Microservices.IO. 2014. Disponível em
<https://goo.gl/idyDAG>. Acesso em: 09 Jan 2017.

RIEHLE, Dirk. Framework Design: A Role Modeling Approach. Zürich, 2000. 230 p.
Tese (Doutorado em Ciências Técnicas)-Universität Hamburg

SARKUNI, Sehrope. How I Write SQL: Naming Conventions. Launch by Lunch.
Cranbury, 2014. Disponível em <https://goo.gl/4oAI5K>. Acesso em: 02 Jun 2016.

SESHADRI, Shyam; GREEN, Brad. Desenvolvendo com AngularJS: Aumento de
produtividade com aplicações Web estruturadas. São Paulo: Novatec, 2014. 349 p.

SILVA, Maurício Samy. Ajax com jQuery: Requisições Ajax com a simplicidade de
jQuery. São Paulo: Novatec, 2009. 327 p.

SMITH, Roger. Why Java is the nº 1 programming language. The Server Side.
Newton, 2016. Disponível em <https://goo.gl/0XAgNS>. Acesso em: 20 Nov 2016.

SOARES, Sérgio. Des. Progressivo de Programas Concorrentes Orientados a
Objetos. Recife, 2001. 121 p. Disertação (Ciência da Computação)-UFPE

SOMMERVILLE, Ian. Software Engineering. Harlow: Addison-W, 2011. 792 p.

TANENBAUM, Andrew S.; STEEN, Maarten van. Sistemas Distribuídos: Princípios
e Paradigmas. 2. ed. São Paulo: Pearson, 2007. 416 p.

TANENBAUM, Andrew S.; WETHERALL, David. Redes de Computadores. 5. ed.
São Paulo: Pearson, 2011. 600 p.

TANENBAUM, Andrew S; WOODHULL, Albert S. Operating Systems Design and
Implementation. 3. ed. Londres: Pearson, 2008. 1080 p.

TCU. Levantamento acerca da Governança de Tecnologia da Informação na
Administração Pública Federal. Brasília, 2008. 48 p.

TERRA. Multas de trânsito serão integradas nos 27 Estados. Terra Notícias. 2007.
Disponível em <https://goo.gl/q6Tg3c>. Acesso em: 18 Jan 2017.

W3TECHS. Usage of web servers for websites. W3Techs. Canadá, 2017. Disponível
em <https://goo.gl/g7pNmD>. Acesso em: 11 Jan 2017.

WIKIPÉDIA. Apache Maven. 2016. Disponível em <https://goo.gl/9mqGjj>. Acesso em: 11 Out 2016.

______. Comparison of web server software. 2017. Disponível em
<https://goo.gl/dFOiu4>. Acesso em: 10 Jan 2017.

______. Java EE Version History. 2016. Disponível em <https://goo.gl/iyOOxN>. Acesso em: 06 Out 2016.

______. Microservices. 2016. Disponível em <https://goo.gl/E3puJk>. Acesso em: 09 Jan 2017.

______. URL. 2016. Disponível em <https://goo.gl/atdtka>. Acesso em: 14 Dez 2016.
