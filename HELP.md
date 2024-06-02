# Let it Save Money

* Here is the tech details that i used via docker-compose.yml

|                | port      | username/db   | password |
|----------------|-----------|---------------|----------|
| **postgresql** | 5432:5432 | user/postgres | 123      |
| **redis**      | 6379      |               |          |

* Microservices links

| apigateway           | http://localhost:8765/     |
|----------------------|----------------------------|
| **service-registry** | **http://localhost:8761/** |
| **auth**             | **http://localhost:8011/** |
| **income-expense**   | **http://localhost:8021/** |
| **saving**           | **http://localhost:8031/** |


