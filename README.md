# neo4j



//Graph database

//create (n),(m),(n)-[:related]->(m)

match(m)-[r]->(n)delete(r)delete(m)delete(n);
create (n)-[:related]->(m);
//match(n)return(n)





match (n)-[r]->(m) where id(r)=10 delete(r)

match (n) where id(n)=21
delete(n)

//multiple properties:
match (n) where id(n)=17
CREATE (Stendhal:exemple{name:"Stendhal2",poub:"Stendhal2"})-[:precise]->(n)




match(m)-[r]->(n)delete(r)delete(m)delete(n);
create (:Metaheuristiques{name:'Metaheuristiques'})-[:relatedTo]->(:Pareto{name:'Pareto'});
match(n)return(n)
