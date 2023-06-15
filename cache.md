# Cache

Cache é um componente fundamental no design de sistemas para melhorar o desempenho e a eficiência. Ele é uma camada de armazenamento rápido que armazena dados temporariamente, com o objetivo de acelerar o acesso a esses dados frequentemente utilizados.


Quando um sistema precisa buscar dados, ele pode primeiro verificar se esses dados estão presentes no cache. Se estiverem, o sistema pode recuperá-los diretamente do cache, que é muito mais rápido do que buscar os dados da fonte original, como um banco de dados ou um serviço externo. Isso reduz o tempo de latência e melhora a experiência do usuário.


O cache opera com base no princípio de localidade, que é a tendência de que dados recentemente acessados sejam acessados novamente no futuro próximo. Ele armazena os dados em uma estrutura de dados rápida, como uma tabela hash ou uma estrutura de dados em árvore, que permite um acesso rápido aos dados por meio de uma chave de pesquisa.


Além disso, o cache pode ser implementado em diferentes camadas de um sistema. Por exemplo, um cache de nível de aplicativo pode ser colocado entre a camada de aplicativo e o banco de dados, enquanto um cache de nível de cliente pode ser usado no navegador ou no aplicativo do cliente.


No entanto, o cache também apresenta alguns desafios. Um deles é a sincronização e a consistência dos dados no cache. Quando os dados são atualizados na fonte original, é necessário garantir que o cache seja atualizado para refletir essas alterações e evitar inconsistências. Isso pode ser feito por meio de técnicas como invalidação de cache ou expiração baseada em tempo.


Outro desafio é o gerenciamento do tamanho do cache e a substituição de dados menos frequentemente usados. É importante garantir que o cache não cresça indefinidamente e que os dados mais relevantes e frequentemente acessados sejam mantidos no cache.

<img width="477" alt="cache" src="https://github.com/ananeridev/workshop-system-design/assets/42419543/f349eabe-5eb9-47f4-a570-ff4d020bcf96">


O cache é uma camada de armazenamento rápido que armazena dados temporariamente para acelerar o acesso a esses dados frequentemente utilizados. Ele aproveita o princípio da localidade e pode ser implementado em diferentes camadas do sistema. No entanto, é necessário lidar com desafios como sincronização de dados e gerenciamento de tamanho para garantir a eficácia do cache.



