# otel-zipkin-postgres-mysql_distributed-tracing
Script do Docker Compose para a subida de ambiente para a coleta de traces de aplicações que fazem uso do projeto Zipkin, do OpenTelemetry Collector, além de bases MySQL e PostgreSQL.

Aplicações:
- [**API de Contagem de acessos (.NET 9 + ASP.NET Core)**](https://github.com/renatogroffe/aspnetcore9-otel-jaeger-postgres-mysql_apicontagem)
- [**API Saudações (Node.js)**](https://github.com/renatogroffe/nodejs-otel-jaeger_apisaudacoes)
- [**Consumer das APIs (Java + Spring + Apache Camel)**](https://github.com/renatogroffe/java-spring-camel-otel-jaeger-postgres-mysql_consumoapis)
