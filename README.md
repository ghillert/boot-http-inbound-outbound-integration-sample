http-inbound-outbound-integration-sample
========================================


## Requirements

* Java 8
* Maven

## REST Api

* Plain MVC + Gateway: GET /api/weather/{query} - Query is e.g. `Berlin,de`
* Spring Integration HTTP Inbound Adapter: GET /weather-inbound/{query} - Query is e.g. `Berlin,de`

E.g.:

* http://localhost:8080/weather-inbound/berlin,de
* http://localhost:8080/api/weather/berlin,de

## Execution

	$ mvn clean spring-boot:run
