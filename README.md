# mssc-beer-inventory-failover


# Notes
* Created for fail-over for beer-inventory-service
* Used webflux and reactive spring to setup rest end point
* Always responds with same inventory information
* * zipkin is disabled in application.properties, spring.zipkin.enabled=false, use 'local' profile(from spring cloud config/repo) to enable zipkin.
* Other props in application-local.properties(mysql related) in Spring cloud config repo are not relevant for this service.

# Dependencies
* spring-cloud-starter-netflix-eureka-client -> Eureka service registration