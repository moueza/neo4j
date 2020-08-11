# neo4j

match (n)-[r]->(m) where id(r)=10 delete(r)

match (n) where id(n)=21
delete(n)

multiple properties:
match (n) where id(n)=17
CREATE (Stendhal:exemple{name:"Stendhal2",poub:"Stendhal2"})-[:precise]->(n)
