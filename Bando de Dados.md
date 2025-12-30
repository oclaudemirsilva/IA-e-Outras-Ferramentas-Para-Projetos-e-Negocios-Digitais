




[INtrodução a Banco de dados](https://www.youtube.com/watch?v=VbNDTOGjt4o)


**A**tomecity
**C**onscistency
**I**solation
**D**urability


[Download phppgAdmin, um versão visual para postgreSQL](https://sourceforge.net/projects/phppgadmin/)


### Banco de dados relacionais
chaves primárias-->id


**SQL**

**GQL**

[Quando não usar SQL e usar noSQL](https://www.youtube.com/watch?v=o8HEfReQ6co)

noSQL--> quando eu não tenho a minha estrutura bem definida

noSQL:
- flexibilidade
- desnormalização
- modelagem dimensional
- tabela fato e dimensão
- data analytics


### diferença entre nSQL e SQL:
**noSQL:**
- schema flexível
- escabalibilidade horizontal
- modelos de dados especializados
- big data
- performance


**SQL:**
- ACID
- Transacional
- robustes/maturidade
- queries complexas
- schema fixo
- consitência







# Grafos
Quando há grande necessidade de recuperar e manipular dados com muitas conexões, como redes sociais.
Em banco de dados de grafos os relacionamentos são unidimensionais, sermpre de um nó para outro.
Quando você vê essa representação <---------> não quer dizer que é bidimensional, mas sim que há dois relacionamentos.

graph db ---> recomendação e antifraude

  
Em noSQL a gente tem um campo flexível como JSON (documento) ao invés de tabelas com infinitas colunas estruturadas para representar a mesma informação.






cypher


**Minicurso de Banco de Dados Orientado a Grafos com Neo4j**

[parte 1](https://www.youtube.com/watch?v=RABFPxXXQqM)

[parte 2](https://www.youtube.com/watch?v=YJ6tUBjSe-I)


[Exemplos/demos de banco de dados orientados a grafos em neo4j](https://neo4j.com/developer/demos/)

<br>


O Google Cloud oferece soluções de banco de dados de grafos por meio do Spanner Graph e parcerias com fornecedores como o Neo4j. 
Opções de Banco de Dados de Grafos no Google Cloud
Spanner Graph: Esta é a solução nativa do Google Cloud, que adiciona recursos de banco de dados de grafos ao seu banco de dados relacional distribuído globalmente, o Spanner.
Características: Oferece escalabilidade massiva, consistência global e alta disponibilidade. Permite a interoperabilidade total entre modelos relacionais e de grafos, o que significa que você pode usar tanto GQL (Graph Query Language, o padrão ISO) quanto SQL para consultar os mesmos dados sem a necessidade de migração. É ideal para casos de uso que exigem análise de grafos em dados transacionais de missão crítica, como detecção de fraudes e gerenciamento de inventário.
Neo4j Aura: O Google Cloud tem uma parceria com o Neo4j, um dos principais fornecedores de bancos de dados de grafos dedicados.
Características: O Neo4j Aura é um serviço de banco de dados de grafo totalmente gerenciado e otimizado, disponível diretamente no Google Cloud Marketplace. É uma opção robusta para a criação de grafos de conhecimento, mecanismos de recomendação e aplicações de IA generativa, oferecendo uma plataforma completa que inclui algoritmos de ciência de dados de grafos e ferramentas de visualização. 
Casos de Uso Comuns
Ambas as soluções são adequadas para uma variedade de aplicações, incluindo: 
Detecção de fraudes
Mecanismos de recomendação
Criação de grafos de conhecimento corporativos
Visualização de relacionamentos complexos de dados 
A escolha entre Spanner Graph e Neo4j dependerá dos seus requisitos específicos de escalabilidade, tipo de consulta e integração com outros serviços do Google Cloud. 


















