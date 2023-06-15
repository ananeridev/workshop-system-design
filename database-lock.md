# Database lock

Database lock, ou bloqueio de banco de dados, é um conceito utilizado em System Design para garantir a consistência e integridade dos dados em um sistema que permite acesso simultâneo a um banco de dados por múltiplos usuários ou processos.

Quando múltiplos usuários ou processos estão tentando acessar e modificar os mesmos dados simultaneamente, pode ocorrer um problema chamado de "concorrência" ou "conflito". Isso pode levar a situações indesejáveis, como leitura de dados inconsistentes ou gravação de dados duplicados.

O bloqueio de banco de dados é uma técnica que lida com esse problema, fornecendo mecanismos para controlar o acesso concorrente aos dados. Existem dois tipos principais de bloqueio de banco de dados:

* **Bloqueio de leitura (Read Lock):** Permite que múltiplas transações realizem leituras simultâneas em um dado, mas impede que uma transação realize uma escrita até que todas as leituras sejam concluídas. Isso garante que as leituras sejam consistentes e evita leituras de dados modificados por outras transações em andamento.

* **Bloqueio de escrita (Write Lock):** Permite que apenas uma transação por vez realize uma escrita em um dado, bloqueando qualquer outra transação de leitura ou escrita. Isso garante que somente uma transação modifique os dados por vez, evitando conflitos e mantendo a integridade dos dados.

Ao utilizar bloqueio de banco de dados, é importante considerar o escopo dos bloqueios, como o tempo que um bloqueio é mantido, a granularidade (se é aplicado a um registro, a uma tabela ou a um conjunto de tabelas) e a estratégia de concessão de bloqueio (se é concedido imediatamente ou se há uma fila de espera).


No entanto, o uso excessivo de bloqueios pode resultar em problemas de desempenho, como bloqueios em cascata e bloqueios em fila. Portanto, é necessário encontrar um equilíbrio entre garantir a consistência dos dados e manter a eficiência do sistema.


<img width="346" alt="database-lock" src="https://github.com/ananeridev/workshop-system-design/assets/42419543/b81f42d1-bd2f-402e-9662-c5777c3be2e8">


O bloqueio de banco de dados é uma técnica usada para controlar o acesso concorrente a um banco de dados, garantindo a consistência e integridade dos dados. Ele utiliza bloqueios de leitura e escrita para coordenar o acesso às informações, evitando conflitos e assegurando a correta manipulação dos dados em um ambiente com acesso simultâneo.

