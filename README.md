# modelagem-neo4j

CREATE (Mateus:`Usuário`)-[:ASSISTIU {rating: 5}]->(`Gente Grande`:Filme)-[:PERTENCE]->(:`Gênero`)<-[:PERTENCE]-(:`Série`)<-[:ASSISTIU {rating: 4.9}]-(Mateus),
(:Ator)-[:ATUOU]->(`Gente Grande`)<-[:DIRIGIU]-(:Diretor)

<img width="749" height="524" alt="Untitled graph" src="https://github.com/user-attachments/assets/4eac17de-3eba-4808-9f3f-36789b9c8b62" />
