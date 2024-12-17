# Prova-APOO-Estudo-de-caso

# Caso de uso: Abrir pedido

- **Ator principal**: Garçom
- **Resumo**: O garçom abre um pedido para um cliente, associando-o a uma mesa específica.
- **Pré-condição**: O garçom deve está cadastrado no sistema e a mesa deve está disponível para a abertura do pedido
- **Pós-Condição**: Um pedido é criado e armazenado no sistema com as informações da mesa, data e hora.


## Fluxo Principal
| Ações do ator | Ações do sistema |
| :-----------------: | :-----------------: | 
| 1 - O garçom seleciona "Abrir Pedido".||  
|| 2 - Exibe a tela para entrada do número da mesa.| 
|3 - O garçom anota o pedido da mesa e seu número ||
|| 4 - O sistema valida o número da mesa |
|5- O garçom confirma a abertura do pedido ||
|| 6 - O sistema registra data e hora e exibe mensagem de que o pedido foi cadastrado ao garçom |

## Fluxo Alternativo I - [Cancelamento de pedido]
| Ações do ator | Ações do sistema |
| :-----------------: | :-----------------: | 
| 1 - O garçom seleciona "Abrir Pedido".||  
|| 2 - Exibe a tela para entrada do número da mesa.| 
|3 - O garçom anota o pedido da mesa e seu número ||
|| 4 - O sistema valida o número da mesa |
|5- O garçom decide cancelar a abertura do pedido. ||
|| 6 - O sistema cancela a operação e retorna à tela inicial.|


## Fluxo de Exceção I - [Mesa já ocupada]
| Ações do ator | Ações do sistema |
| :-----------------: | :-----------------: | 
| 1 - O garçom insere o número de uma mesa||  
|| 2 -  sistema detecta que a mesa está ocupada e o notifica disso| 
|3 - O garçom escolhe outra mesa disponível.||

