# Resources:

## SQL vs NoSQL
- https://www.mongodb.com/nosql-explained/nosql-vs-sql

## CAP Theorem
- https://www.youtube.com/watch?v=R_Fxz14tr2M
- https://www.youtube.com/watch?v=KmGy3sU6Xw8

## API Gateway

An API gateway takes all API calls from clients, then routes them to the appropriate microservice with request routing, composition, and protocol translation. Typically it handles a request by invoking multiple microservices and aggregating the results, to determine the best path. It can translate between web protocols and web‑unfriendly protocols that are used internally.

An e‑commerce site might use an API gateway to provide mobile clients with an endpoint for retrieving all product details with a single request. It invokes various services, like product info and reviews, and combines the results.

Youtube video:
- https://www.youtube.com/watch?v=6ULyxuHKxg8
- https://www.youtube.com/watch?v=hWRRdICvMNs

Docs:
- https://microservices.io/patterns/apigateway.html
- https://www.nginx.com/learn/api-gateway/


## Back-of-the-Envelope Estimation/Capacity Planning

A back-of-the-envelope calculation uses estimated or rounded numbers to develop a ballpark figure quickly. The result should be more accurate than a guess, as it involves putting thought to paper, but it will be less accurate than a formal calculation performed using precise numbers and a spreadsheet or calculator.

Youtube Video:

- https://www.youtube.com/watch?v=UC5xf8FbdJc


## CQRS(Command Query Responsibility Segregation)

Youtube video:
- https://www.youtube.com/watch?v=DQ3D_mplIgY

Docs:
- https://martinfowler.com/bliki/CQRS.html

## Bloom Filters

- It is a probabilistic data structure designed to answer the set membership question- Is this element present in the Set?
- It is highly space efficient and does not store the actual items.
- It can tell very quickly if an item does not exist in a set or if it may be existing in the Set.
- However, it cannot tell if an item is definitely present in a Set.

Youtube video:
- https://www.youtube.com/watch?v=V3pzxngeLqw
- [Bloom Filters Explained by Example](https://www.youtube.com/watch?v=gBygn3cVP80)

Docs:
- [What is a Bloom Filter?](https://www.educative.io/answers/what-is-a-bloom-filter)

## Message Queues & PubSub Systems

YouTube Vidoes:
- [Publish-Subscribe Architecture (Explained by Example)](https://www.youtube.com/watch?v=O1PgqUqZKTA)
- [What is Kafka and How does it work?](https://www.youtube.com/watch?v=LN_HcJVbySw)
- [RabbitMQ Crash Course](https://www.youtube.com/watch?v=Cie5v59mrTg)

## Interesting Engineering blogs

- [HOW DISCORD STORES BILLIONS OF MESSAGES](https://discord.com/blog/how-discord-stores-billions-of-messages)
- [Why Uber Engineering Switched from Postgres to MySQL](https://www.uber.com/blog/postgres-to-mysql-migration/)
