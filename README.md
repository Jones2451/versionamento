# Continuação


## Protocolo de comunicação

HTTP: Esse sem dúvidas é conhecido por muitos. Afinal, quem nunca viu na frente do endereço de uma homepage esse nome? ex: http://google.com/. O Hyper Text Transfer Protocol é o protocolo responsável por transmitir textos, imagens e multimídia na Internet. Sempre que você abre uma homepage (mesmo que ela só contenha textos), você está usando esseprotocolo. Achei interessante comentar sobre ele para que ele se entenda melhor como a Internet não funciona isolada com um só protocolo HTTP, FTP, TELNET entre muitos outros, e muitas vezes  trabalham em conjunto e nem conseguimos perceber. Quando você for baixar um arquivo, preste atenção ao link. É muito provavel que de uma página navegada por HTTP, se envie a um Servidor FTP, e em muitos de golpistas se usando de "Falsos Links" para o roubo de dados daqueles que são bem disprevindos, ou seja, caso não esteja com o firewall em dia pode sabe que na primeira oportunidade você pode acabar tendo seus dados vazados.

REST: (REpresentational State Transfer), ou REST, é um conjuto de regras que garantem um sistema escalavel, facilmente extensível e tolerante a falhas. A world-wide-web é um exemplo desse tipo de sistema (e o maior exemplo possivel). REST por si só, não é uma nova invenção, mas é a documentação para sistemas como a the world-wide-web.

Web API: Uma Web API, por outro lado, é uma API que utiliza o protocolo HTTP (Hypertext Transfer Protocol) para permitir que aplicativos se comuniquem pela internet. Ela define endpoints (pontos de extremidade) e URLs que os aplicativos podem acessar para obter ou enviar dados. As Web API’s são comuns na construção de aplicativos web e móveis, permitindo que eles obtenham dados de servidores remotos ou realizem ações em sistemas externos.

Metódos e finalidades:

GET: O método GET solicita a representação de um recurso específico. Requisições utilizando o método GET devem retornar apenas dados.

HEAD: O método HEAD solicita uma resposta de forma idêntica ao método GET, porém sem conter o corpo da resposta.

POST: O método POST é utilizado para submeter uma entidade a um recurso específico, frequentemente causando uma mudança no estado do recurso ou efeitos colaterais no servidor.

PUT: O método PUT substitui todas as atuais representações do recurso de destino pela carga de dados da requisição.

DELETE: O método DELETE remove um recurso específico.

CONNECT: O método CONNECT estabelece um túnel para o servidor identificado pelo recurso de destino.

OPTIONS: O método OPTIONS é usado para descrever as opções de comunicação com o recurso de destino.

TRACE: O método TRACE executa um teste de chamada loop-back junto com o caminho para o recurso de destino.

PATCH: O método PATCH é utilizado para aplicar modificações parciais em um recurso.