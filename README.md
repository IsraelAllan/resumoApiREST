# resumoApiREST
Atividade BackEnd - lista 1
# Api REST e RESTFul
Primeiro, APIs é um conjunto de regras, instruções ou padrões que fazem parte
de uma interface de um dispositivo.
API REST é interface que segue em compatibilidade com as restições de acordo com estilo 
da arquitetura REST, que irá permitir uma certa comunicação com o RESTFUL.
RESTFul é uma interface que dois ou mais computadores usam para trocar informação de 
uma maneira mais segura pela web, pelos padrões de comunicação seguidos pela mesma.

##Diferenças entre REST e RESTFul
As APIs REST e  RESTFul são basicamente as mesma, toda RESTFul é uma REST, mas nunca o 
inverso. A REST pode não seguir a risca todos conceitos da arquitetura REST, como a RESTFul 
prioriza. A RESTFul possue uma implementação mais completa sobre esses principios .

## HTTP verbs
GET 
Retorna apenas dados da requisição.
HEAD
Solicita uma resposta de forma idêntica ao método GET, porém sem conter o corpo da resposta.
POST
É utilizado para submeter uma entidade a um recurso específicor.
PUT
Substitui todas as atuais representações do recurso de destino pela carga de dados da requisição.
DELETE
Apaga um recurso específico.
CONNECT
Estabelece um túnel para o servidor identificado pelo recurso de destino.
OPTIONS
É usado para descrever as opções de comunicação com o recurso de destino.
TRACE
Executa um teste de chamada loop-back junto com o caminho para o recurso de destino.
PATCH
É utilizado para aplicar modificações parciais em um recurso.

 ## HTTP Status Code
Esses códigos indicam se a resposta HTTP indicam se uma solicitação foi concluida de forma correta.

Respostas de informação (100-199)
Indica que a requisição foi recebida e entendida. Serve de alerta para o cliente que espere a resposta final.

Respostas bem-sucedidas (200 - 299)
ndica que a ação solicitada pelo cliente foi recebida, compreendida, aceita e processada com êxito.

Mensagens de redirecionamento (300-399) Indica que a ação ainda precisa ser levada pelo agente de usuário, a fim de atender à solicitação.

Respostas de erro do cliente (400-499)
Classe destinada para os casos em que o cliente parece ter cometido um erro. 
    
Respostas de erro do servidor (500-599)
Indica casos na qual o servidor está ciente do erro e é incapaz de performar a requisição. 

Autor do resumo: Israel Viegas - 01433868
