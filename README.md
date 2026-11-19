# P2 - Sistemas Distribuidos

Aluno: Gabriel Ribeiro de Oliveira
Professora: Simone Tatiane do Canto
Data: 18/11/2026

## 1. Situação - problemas

O Sistema anda permitindo mais processamentos simultanêos do que o limite estabelico, sendo assim o estoque da replica não esta sendo atualizado corretamente, então o servidor principal fica indisponivel e o sistema não consegue utilizar a replica.

# 2. Evidencia 1
<img width="480" height="178" alt="711393139-92687f04-cdda-4cbf-a766-5c4d15101246" src="https://github.com/user-attachments/assets/e29b9799-4e0f-42f9-996e-b9bacfa92fef" />
# Problema A
<img width="470" height="174" alt="711391777-3716bc21-05ae-4b9a-801e-61669fe8f8cd" src="https://github.com/user-attachments/assets/5bd8b5f4-0af4-422f-bf86-6c54169d0875" />


#Controle de concorrencia MAXIMO_SIMULTANEO = 2 - foi alterado de numero 3 para 2



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

# Conclusão

Com essa atividade, aprendi a interpretar o código, identificar e corrigir os problemas apresentados pela empresa e compreender melhor o funcionamento de uma réplica e como ela pode assumir o lugar do servidor principal caso ele apresente alguma falha.
