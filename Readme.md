#  Projeto: Banco NoSQL Chave-Valor — Redis

Este projeto demonstra o uso do **Redis** como um banco de dados **NoSQL baseado no modelo Chave-Valor (Key-Value)**.  
Implementamos operações essenciais (CRUD), TTL, atomicidade com operações transacionais e pub/sub, simulando cenários reais de uso.

O objetivo é mostrar como Redis funciona como uma solução extremamente rápida para armazenamento, cache, sessões e contadores — aplicações perfeitas para o modelo K-V.

---

Por ser um banco **in-memory**, o Redis realiza operações de leitura e escrita em milissegundos, o que o torna ideal para aplicações que exigem respostas rápidas.

Neste projeto, utilizamos o Redis como uma loja K-V para armazenar dados como:

- usuários (`user:1001`)  
- sessões com expiração (TTL)  
- configurações rápidas  
- contadores atômicos  

O Redis oferece:

- **TTL (Time To Live)** → chaves que expiram automaticamente  
- **Atomicidade** → comandos como `INCR`, `DECR`, `WATCH`, `MULTI`, `EXEC`  
- **Pub/Sub** → sistema de mensagens em tempo real  
- **Persistência opcional** → modos RDB e AOF  

Esses recursos tornam o Redis ideal para casos como cache, autenticação, filas simples e sistemas que precisam de muita performance.

**Resumo:** o Redis fornece rapidez extrema, simplicidade no modelo chave-valor, suporte a TTL, operações atômicas e uma grande variedade de estruturas de dados, sendo uma solução moderna e eficiente para armazenar informações de forma leve e com alta performance.
