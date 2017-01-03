# Status Request

2xx     Sucesso
3xx     Redirecionamento
4xx     Erro de cliente
5xx     Outros erros ou erro de Servidor

Definições sobre os status:

#Codigo                   #Descrição
<p>200 OK                    Requisição efetuada com sucesso.</p>
<p>201 Created               Requisição efetuado com sucesso. No REST, esse código indica que um novo recurso foi salvo no                                  banco de dados.</p>
<p>204 No Content            Requisição efetuado com sucesso, porém nao existe nenhum retorno. Isso pode acontecer se você                                  tiver requisitado um objeto e ele não tiver sido encontrado.</p>

<p>301 Moved Permanently     Requisição com sucesso, mas fez um redirecionamento para outra página.</p>

<p>400 Bad Request           Requisição inválida. Por exemplo, caso enviou parâmetros inválidos.</p>
<p>401 Unauthorized          Indica uma falha na autentiticação do serviço ou se a autenticação ainda nao foi feita. Utilizando                              em web services seguros.</p>
<p>403 Forbidden             Indica que o acesso a essa página foi negada por questões de segurança;
<p>404 Not Found             Página ou recurso não encontrado.</p>
<p>405 Method Not Allowed    Erro caso o método HTTP solicitado não puder ser encontrado na página. Por exemplo, se o cliente                                tiver solicitado uma requisição do tipo DELETE, mas web services nao a suportar.</p>
<p>500 Internal Server Error Indica um erro no servidor. Neste caso, provalvelmente, o servidor não conseguiu atender à                                      requisição por alguma falha global e está com problemas.</p>
<p>504 Gateway Timeout       Erro de timeout caso a requisição nao retorne no tempo estipulado.</p>

<table>
  <tr>
    <th>#Codigo</th>
    <th>#Descrição</th>
  </tr>
</table>
