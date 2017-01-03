# Status Request

2xx     Sucesso
3xx     Redirecionamento
4xx     Erro de cliente
5xx     Outros erros ou erro de Servidor

Definições sobre os status:
<table>
  <tr>
    <th>#Codigo</th>
    <th>#Descrição</th>
  </tr>
  <tr>
    <td>200 OK</td>
    <td>Requisição efetuada com sucesso.</td>
  </tr>
  <tr>
    <td>201 Created</td>
    <td>
      Requisição efetuado com sucesso. No REST, esse código indica que um novo recurso foi salvo no                                 banco de dados.
    </td>
  </tr>
  <tr>
    <td>204 No Content</td>
    <td> Requisição efetuado com sucesso, porém nao existe nenhum retorno. Isso pode acontecer se você                                  tiver requisitado um objeto e ele não tiver sido encontrado.</td>
  </tr>
  <tr>
    <td>301 Moved Permanently</td>
    <td>Requisição com sucesso, mas fez um redirecionamento para outra página.</td>
  </tr>
  <tr>
    <td>400 Bad Request</td>
    <td>Requisição inválida. Por exemplo, caso enviou parâmetros inválidos.</td>
  </tr>
  <tr>
    <td>401 Unauthorized</td>
    <td>
      Indica uma falha na autentiticação do serviço ou se a autenticação ainda nao foi feita. Utilizando                           em web services seguros.
    </td>
  </tr>
  <tr>
    <td>403 Forbidden</td>
    <td>Indica que o acesso a essa página foi negada por questões de segurança</td>
  </tr>
  <tr>
    <td>404 Not Found</td>
    <td>Página ou recurso não encontrado.</td>
  </tr>
  <tr>
    <td>405 Method Not Allowed</td>
    <td>
      Erro caso o método HTTP solicitado não puder ser encontrado na página. Por exemplo, se o cliente                             tiver solicitado uma requisição do tipo DELETE, mas web services nao a suportar.</td>
  </tr>
  <tr>
    <td>500 Internal Server Error</td>
    <td>
      Indica um erro no servidor. Neste caso, provalvelmente, o servidor não conseguiu atender à                                   requisição por alguma falha global e está com problemas.</td>
  </tr>
  <tr>
    <td>504 Gateway Timeout</td>
    <td>Erro de timeout caso a requisição nao retorne no tempo estipulado.</td>
  </tr>
</table>
