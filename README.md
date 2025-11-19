# 👋 David Cortaberría Fernández

**Arquitecto de Software | Especialista en Microservicios | Spring Boot & Kubernetes**

---

## 👤 Sobre Mí

Software Architect con **más de 10 años en desarrollo empresarial**, 
evolucionando desde desarrollador Spring Boot hasta arquitecto de soluciones cloud-native.

**Experiencia en Producción:**
- Arquitecto en modernización de sistemas Legacy (10+ años) → Spring Boot + Angular
- Evolución desde monolitos en capas (Controller-Service-Repository) hasta microservicios distribuidos
- Microservicios Spring Cloud Netflix en producción (Eureka, Config Server, Hystrix, Feign)
- Soluciones Spring Boot para clientes enterprise (Vaillant, sector público)

**R&D & Arquitectura de Referencia:**
- Spring Cloud Kubernetes - POC enterprise con 5 microservicios, service discovery, circuit breakers
- Event-Driven Architecture - Implementación SAGA, Outbox, Event Sourcing con Kafka
- Security Stack - OAuth2/OIDC, JWT, Cookies, Spring Security, en progreso con Keycloak
- Clean Architecture - DDD, Hexagonal Architecture, patrones empresariales

**Objetivo:** Liderar proyectos de **microservicios de grado de producción** y guiar equipos en la transición desde arquitecturas monolíticas/legacy hacia soluciones distribuidas cloud-native.

---

## 📌 Proyectos Destacados (Pinned)

### Tier-1: Sistemas de Producción

### **[☸️ Spring Cloud Kubernetes](https://github.com/Cortadai/POC-03-SCK)** ⭐⭐⭐
**Arquitectura Empresarial de Microservicios con Spring Cloud Kubernetes**
- 5 microservicios productivos: Gateway, Admin, Employee, Department, Organization con comunicación orquestada
- Service Discovery nativo de Kubernetes eliminando dependencias de Eureka/Consul
- Circuit Breakers con Resilience4j implementando patron de resiliencia fallback
- Distributed Tracing completo con Zipkin para trazabilidad end-to-end de peticiones
- Arquitectura dual ejecutable: Modo desarrollo local (sin K8s) + Deployment completo en Minikube/K8s
- Gestión de configuración externa mediante ConfigMaps, Secrets y SealedSecrets

### **[🎯 Clean Architecture & DDD](https://github.com/Cortadai/food-ordering-system)** ⭐⭐⭐
**Microservicios con DDD, SAGA, Kafka & Arquitectura Orientada a Eventos**
- Spring Boot 17, Apache Kafka, PostgreSQL.
- Implementa: Arquitectura Hexagonal, patrón SAGA, patrón Outbox, Event Sourcing.
- 4 microservicios: Órdenes, Cliente, Pagos, Restaurante.
- Patrones reales para transacciones distribuidas.

### **[🛡️ Security Architecture](https://github.com/Cortadai/spring-security-poc)** ⭐⭐⭐
**Sistema de Autenticación Empresarial con Integración SSO**
- 3 implementaciones arquitectónicas: Básica (main), Basada en Cookies (option1), Híbrida (option2)
- Arquitectura completa de 4 capas: Fake SSO → Middleware de Seguridad → API Backend → Angular SPA
- Implementa 7 endpoints de seguridad con JWT RS256, encriptación AES, certificados X.509
- Patrones de producción: Protección CSRF, renovación automática de tokens, sesiones distribuidas

### **[⬡ Hexagonal Architecture Lite](https://github.com/Cortadai/poc-hexagon-lite)** ⭐⭐
**Arquitectura Hexagonal (Puertos & Adaptadores) con Java 17**
- 5 módulos Maven con separación estricta de responsabilidades
- Demostración de Arquitectura Limpia
- Patrones de Domain-Driven Design

### **[🗄️ jOOQ Type-Safe SQL](https://github.com/Cortadai/poc-01-jooq)** ⭐⭐
**SQL Type-Safe con JOOQ**
- Comparación JOOQ vs JPA
- Integración con SQL Server & PostgreSQL
- Arquitectura hexagonal con migraciones Flyway

---

## 📚 Colecciones de Aprendizaje

### Tier-2: He organizado mis proyectos en hubs de aprendizaje curados con documentación comprehensiva

### 🏗️ [Arquitectura de Microservicios](https://github.com/Cortadai/microservices-architecture)
Ecosistema completo de microservicios con Eureka, Config Server, API Gateway y patrones de resiliencia.
- **4 Proyectos** | Spring Cloud, patrones Netflix, Sistemas Distribuidos

### 🚀 [Event-Driven & Messaging](https://github.com/Cortadai/event-driven-messaging-architecture)
Desde tutoriales de Kafka hasta pipelines de streaming en tiempo real.
- **6 Proyectos** | Kafka, RabbitMQ, patrones Producer-Consumer, Streaming en tiempo real

### ⚡ [Fundamentos Spring Boot](https://github.com/Cortadai/spring-boot-basics)
Conceptos fundamentales para APIs REST y microservicios.
- **5 Proyectos** | CRUD, JPA, Transacciones, APIs de búsqueda

### 🔐 [Seguridad & Autenticación](https://github.com/Cortadai/spring-security-course)
19 proyectos comprehensivos cubriendo Spring Security desde lo básico hasta OAuth2.
- JWT, OAuth2, OpenID Connect, integración con Keycloak

### 🌐 [Servicios Web & SOAP](https://github.com/Cortadai/web-services-soap)
SOAP, XML, WSDL - patrones de integración empresarial.
- **6 Proyectos** | Implementaciones Cliente/Servidor, desarrollo Contract-first

### 🎓 [Aprendizaje Angular](https://github.com/Cortadai/angular-learning)
13 proyectos de Angular cubriendo desde fundamentos hasta patrones avanzados.
- Formularios, Directivas, Componentes, RxJS, Material Design

### 🔧 [Herramientas de Generación de Código](https://github.com/Cortadai/code-generation-tools)
Generación automática de código desde esquemas y contratos.
- JSON2Java, XSD2Java, Swagger2Java, WSDL2Java

---

## 🛠️ Stack Tecnológico

**Backend & Arquitectura**
- Spring Boot (2.x, 3.x)
- Spring Cloud (Eureka, Config, Gateway, Resilience4J)
- Spring Cloud Kubernetes
- Java 11, 17, 21
- Arquitectura Hexagonal, DDD, patrones SAGA

**Seguridad & Autenticación**
- Spring Security
- JWT (RS256/RS512)
- Keycloak (en progreso)
- X.509 Certificates
- AES Encryption

**Mensajería & Eventos**
- Apache Kafka
- RabbitMQ
- Event Sourcing, CQRS

**Bases de Datos**
- PostgreSQL
- MySQL
- SQL Server
- MongoDB

**DevOps & Infraestructura**
- Docker & Docker Compose
- Kubernetes (on-premise)
- Minikube
- SealedSecrets 
- Maven, Git

**Observabilidad & Monitorización**
- Zipkin (Distributed Tracing)
- Micrometer
- Spring Boot Admin
- Spring Boot Actuator

**Frontend**
- Angular 14+
- TypeScript
- RxJS
- Angular Material

**Herramientas & Frameworks**
- JOOQ (SQL Type-safe)
- JPA/Hibernate
- Flyway (Migraciones)
- MapStruct (Mapeo)
- OpenFeign
- Testcontainers 

---

## 📊 Por Los Números

- **55+ repositorios** organizados por ruta de aprendizaje
- **6 hubs de aprendizaje curados** con documentación comprehensiva
- **4 proyectos de portfolio de grado de producción**
- **10+ años** de experiencia en arquitectura empresarial
- **Especialista en:** Microservicios y Ecosistema Spring

---

## 🎓 Enfoque de Aprendizaje

Creo en el **aprendizaje práctico y hands-on**. Cada hub incluye:

- ✅ Dificultad progresiva (Principiante → Avanzado)
- ✅ Casos de uso y patrones reales
- ✅ Ejemplos de trabajo completo
- ✅ Documentación comprehensiva

---

## 🔗 Enlaces Rápidos

- 📧 **Email:** David.Cortabarria@gmail.com
- 🔗 **LinkedIn:** [David Cortaberría](https://www.linkedin.com/in/david-cortaberr%C3%ADa-fern%C3%A1ndez-747903117/)
- 📍 **Ubicación:** Bilbao y alrededores, España

---

## 🗺️ Foco Actual

**Roadmap de Aprendizaje**
- ✅ **Spring Cloud Kubernetes** - POC completado con 5 microservicios enterprise-grade
- 🔄 **Keycloak** - Implementando SSO, OAuth2/OIDC y gestión centralizada de identidades
- 📋 **Apache Camel** - Próximo: Integración empresarial y patrones EIP (Enterprise Integration Patterns)
- 🎯 Objetivo: Stack completo de integración y seguridad enterprise grade

---

## 💡 Filosofía

> *"La arquitectura no se trata de ser inteligente. Se trata de resolver problemas reales con soluciones simples y mantenibles."*

Me interesa:
- ✅ Código limpio y mantenible
- ✅ Sistemas distribuidos escalables
- ✅ Aprendizaje continuo y mejora
- ✅ Compartir conocimiento

---

## 📈 Próximos Pasos

Actualmente preparando:
- 📚 Patrones avanzados de Kubernetes
- 🔍 Guías de troubleshooting en microservicios
- 💼 Sitio web de portfolio con Hugo
- 📝 Artículos técnicos sobre patrones de arquitectura

---

**Siempre aprendiendo. Siempre construyendo. Siempre mejorando.** 🚀

*Última actualización: Noviembre 2025*
