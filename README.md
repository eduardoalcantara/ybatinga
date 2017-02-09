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
