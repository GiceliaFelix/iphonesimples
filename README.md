# Diagramando as funcionalidades básicas de um Iphone.
Projeto do Bootcamp da Dio em parceria com a Santander. Módulo de diagramação. 

O objetivo deste artigo é apresentar uma modelagem UML para representar as funcionalidades do iPhone, abordando três principais componentes: Reprodutor Musical, Aparelho Telefônico e Navegador de Internet. A modelagem UML (Unified Modeling Language) é uma linguagem padrão para especificar, visualizar, construir e documentar artefatos de sistemas de software.
Descrição das Funcionalidades
Reprodutor Musical

O Reprodutor Musical é responsável por gerenciar a reprodução de músicas no iPhone. Suas principais funcionalidades são:

    tocar(): Inicia a reprodução da música.
    pausar(): Pausa a reprodução da música.
    selecionarMusica(string Musica): Seleciona uma música específica para reprodução.

Aparelho Telefônico

O Aparelho Telefônico gerencia as chamadas e o correio de voz no iPhone. Suas funcionalidades incluem:

    ligar(string Numero): Realiza uma chamada para o número especificado.
    atender(): Atende uma chamada recebida.
    iniciarCorreioVoz(): Inicia o correio de voz.

Navegador de Internet

O Navegador de Internet permite a navegação na web. Suas principais funcionalidades são:

    exibirPagina(string url): Exibe a página web do URL especificado.
    adicionarNovaAba(): Adiciona uma nova aba no navegador.
    atualizarPagina(): Atualiza a página web atual.

Diagrama de Classes UML

A seguir, apresentamos o diagrama de classes UML que modela as funcionalidades descritas acima.


![Telephone (Use of Association) Class Diagram Example](https://github.com/GiceliaFelix/umliphonesimples/assets/159393898/5e77d442-6935-464d-aef3-b072f3c7cc61)

Descrição do Diagrama

O diagrama de classes acima representa a estrutura e o comportamento das funcionalidades do iPhone.

    iPhone: Classe principal que compõe os componentes Reprodutor Musical, Aparelho Telefônico e Navegador de Internet. Esta classe agrega as funcionalidades de cada um desses componentes.

    Reprodutor Musical: Classe que representa o reprodutor de músicas, contendo métodos para tocar, pausar e selecionar músicas.

    Aparelho Telefônico: Classe que gerencia as funções telefônicas do iPhone, incluindo realizar chamadas, atender chamadas e iniciar o correio de voz.

    Navegador de Internet: Classe que representa o navegador web, permitindo exibir páginas, adicionar novas abas e atualizar a página atual.

Conclusão

A modelagem UML apresentada fornece uma visão clara e organizada das funcionalidades principais do iPhone, permitindo um entendimento abrangente de como essas funcionalidades são estruturadas e interagem entre si. Essa modelagem é essencial para o desenvolvimento e a manutenção do software, garantindo que todas as partes do sistema estejam bem definidas e documentadas.
