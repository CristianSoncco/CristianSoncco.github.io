---
title: "Sistemas Web Empresariales - NTT DATA"
date: 2021-02-01
draft: false
description: "Desarrollo de dos sistemas web con Angular 12, C# .NET CORE y PostgreSQL/Oracle. Mejoras de performance del 40% y arquitectura de microservicios."
tags: ["Angular 12", "C# .NET CORE", "PostgreSQL", "Oracle", "Microservicios"]
categories: ["Desarrollo Web", "Arquitectura"]
image: "/images/portfolio/proyecto-ntt.jpg"
---

# Sistemas Web Empresariales - NTT DATA Europe & Latam

## Descripción del Proyecto

Como **Center Senior Developer** en NTT DATA, lideré el desarrollo de dos sistemas web empresariales críticos utilizando **Angular 12** para el frontend, **C# .NET CORE** para el backend y **PostgreSQL/Oracle** como bases de datos.

## Tecnologías Utilizadas

### Frontend
- **Angular 12** - Framework principal
- **TypeScript** - Lenguaje de programación tipado
- **Angular Material** - Biblioteca de componentes UI
- **RxJS** - Programación reactiva

### Backend
- **C# .NET CORE** - Framework principal del backend
- **ASP.NET Core Web API** - APIs RESTful
- **Entity Framework Core** - ORM para acceso a datos
- **Microservicios** - Arquitectura distribuida

### Base de Datos
- **PostgreSQL** - Base de datos principal
- **Oracle Database** - Sistema legacy integrado

## Logros Principales

### Mejora de Performance del 40%
- **Optimización de consultas** complejas
- **Implementación de caché** distribuido
- **Modularización** con sistema legado
- **Arquitectura de microservicios** escalable

## Resultados
- ✅ **40% mejora** en tiempo de carga
- ✅ **99.9% disponibilidad** del sistema
- ✅ **90% cobertura** de unit tests
- ✅ **Modernización exitosa** de sistemas críticos

## Características Técnicas

### Desarrollo .NET Framework Legacy
- **Mantenimiento y soporte** de sistemas .NET Framework
- **Implementación de patrones Proxy y Fabric** para abstracción
- **Refactoring gradual** hacia .NET Core
- **Integración con servicios** modernos

### Escalabilidad y Performance
- **Horizontal scaling** de microservicios
- **Load balancing** automático
- **Database sharding** para grandes volúmenes
- **Monitoring y alertas** en tiempo real

### Seguridad Implementada
- **JWT Authentication** con refresh tokens
- **OAuth 2.0** para integración con terceros
- **Role-based access control** (RBAC)
- **Data encryption** en tránsito y reposo
- **API rate limiting** y throttling

## Arquitectura del Sistema

### Patrón de Microservicios
```
┌─────────────────┐    ┌─────────────────┐    ┌─────────────────┐
│   Angular 12    │    │   API Gateway   │    │  User Service   │
│   Frontend      │◄──►│   .NET Core     │◄──►│   .NET Core     │
└─────────────────┘    └─────────────────┘    └─────────────────┘
                                │                       │
                                ▼                       ▼
                       ┌─────────────────┐    ┌─────────────────┐
                       │ Business Service│    │  Data Service   │
                       │   .NET Core     │    │   PostgreSQL    │
                       └─────────────────┘    └─────────────────┘
```

### Integración con Legacy
- **Adapter pattern** para sistemas Oracle legacy
- **Message transformation** entre formatos
- **Gradual migration** strategy
- **Backward compatibility** garantizada

## Metodología de Desarrollo

- **Agile/Scrum** con sprints de 2 semanas
- **Test-Driven Development** (TDD)
- **Continuous Integration/Continuous Deployment** (CI/CD)
- **Code reviews** obligatorios
- **Pair programming** para conocimiento compartido

## Herramientas y DevOps

### Control de Versiones
- **Git** con GitFlow workflow
- **Azure DevOps** para gestión de proyectos
- **Pull requests** con revisión de código

### CI/CD Pipeline
- **Azure Pipelines** para automatización
- **Docker** containerization
- **Kubernetes** para orquestación
- **Automated testing** en múltiples entornos

### Monitoring y Logging
- **Application Insights** para telemetría
- **ELK Stack** para logging centralizado
- **Prometheus** y **Grafana** para métricas
- **Health checks** automatizados

---

*Este proyecto demuestra mi experiencia en liderar equipos de desarrollo, implementar arquitecturas complejas y entregar soluciones empresariales de alta calidad que generan valor real para el negocio.* 