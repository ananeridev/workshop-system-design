# Blob Storage

Nos fundamentos de system design de hoje irei te explicar sobre blob storage, 

Sabe quando você precisa de uma flexivel para armazenar seus dados, escalável e economica não estruturados em uma nuvem? 

Pois bem todas essas necessidades é algo que o blob storage ve m pra resolver.

A palava “Blob” é uma abrerviação de Binary Large Object, que se refere a qualquer tipo de dado que não seja estruturado de maneira tradicional, como texto ou numeros em um banco de dados.

**O armazenamento de blob é um tipo de armazenamento em nuvem que é projeto especificamente para armazenar dados nao estruturados (como XML, ou dados muito grandes, vídeos, documentos, imagens).**

Pense nisso como um grande conttainer onde você pode armazenar qualquer tipo de objeto digital.

Você pode acessar esses objetos de qualquer lugar do mundo usando uma URL exclusiva gerada pelo serviço de armazenamento provido. 

Blob Storage é perfeito para hospedar imagens para sites, armazenar arquivos de log e muito mais de forma mais ecnonmica.

Nesse exemplo que aparece na tela, um servidor que hospeda logs que são armazenados no serviço de armazenamento do mesmo. Um analisador de log recupera os arquivos de log do armazenamentos de blob e analisa os dados.

<img width="225" alt="blob storage" src="https://github.com/ananeridev/workshop-system-design/assets/42419543/d19e18b6-4408-4639-8857-71686e846f8f">


Os resultados são exibidos em um painel de infos para análise posterior e tomada de decisão caso necessário.

