# P2 - Sistemas Distribuidos

Aluno: Gabriel Ribeiro de Oliveira
Professora: Simone Tatiane do Canto
Data: 18/11/2026

## 1. Situação - problemas

O Sistema anda permitindo mais processamentos simultanêos do que o limite estabelico, sendo assim o estoque da replica não esta sendo atualizado corretamente, então o servidor principal fica indisponivel e o sistema não consegue utilizar a replica.

# 2. Evidencia 1
<img width="470" height="174" alt="711391777-3716bc21-05ae-4b9a-801e-61669fe8f8cd" src="https://github.com/user-attachments/assets/ea1bcaa5-42d7-4c04-a629-fc9470f705ef" />

# EVIDENCIA 2<img width="1279" height="1023" alt="EVIDENCIA2" src="https://github.com/user-attachments/assets/7dc6837d-3336-4d45-a156-a22b8e73259f" />

EVIDENCIA 3:

QUESTÕES:


1 - O semáforo controla o número de threads que podem ser executadas ao mesmo tempo, evitando que o sistema fique sobrecarregado.
2 -É necessário porque, se o servidor principal apresentar alguma falha, a réplica poderá assumir seu lugar, mesmo que não esteja totalmente atualizada.
3 - Significa que, mesmo quando ocorre alguma falha, o programa continua em execução. Nesse código, isso foi demonstrado pelo uso da réplica, que continuou funcionando mesmo apresentando informações incorretas.
4- Sua função é garantir que apenas uma thread possa modificar o estoque por vez, evitando erros e inconsistências nos valores.
Isso acontece porque é necessário manter o estoque atualizado:
Os pedidos são processados no servidor principal.
5- O estoque é atualizado de acordo com os pedidos realizados.
Depois da atualização, a sincronização envia o novo valor do estoque para a réplica.

Conclusão

Com essa atividade, aprendi a interpretar o código, identificar e corrigir os problemas apresentados pela empresa e compreender melhor o funcionamento de uma réplica e como ela pode assumir o lugar do servidor principal caso ele apresente alguma falha.
