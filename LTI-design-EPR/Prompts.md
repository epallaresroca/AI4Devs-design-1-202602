PROMPT1-Product Definition 

# Role
Actúa como Product Manager y Software Architect senior con más de 5 años de experiencia diseñando plataformas SaaS empresariales y sistemas ATS (Applicant Tracking Systems).

# Context
Una startup llamada LTI quiere desarrollar un ATS moderno orientado a mejorar los procesos de selección de personal mediante automatización, colaboración en tiempo real e Inteligencia Artificial.

El sistema será utilizado principalmente por:
- Recruiters
- Hiring Managers
- Equipos de Recursos Humanos
- Administradores

# Objective
Ayúdame a diseñar la primera versión del producto LTI ATS.

# Tasks

## 1. Descripción del producto
Describe:
- Qué es LTI ATS
- Qué problema resuelve
- Público objetivo
- Objetivos principales del sistema

## 2. Propuesta de valor
Explica:
- Qué hace diferente a LTI ATS frente a otros ATS tradicionales
- Cómo mejora la experiencia de recruiters y managers
- Cómo utiliza automatización e IA

## 3. Ventajas competitivas
Incluye ventajas relacionadas con:
- Inteligencia Artificial
- Automatización
- UX/UI moderna
- Analítica y métricas
- Escalabilidad cloud
- Colaboración entre equipos

## 4. Funcionalidades principales
Define las funcionalidades principales de la primera versión MVP:
- Gestión de ofertas
- Gestión de candidatos
- Pipeline de selección
- Entrevistas
- Evaluaciones
- Reporting
- IA y automatizaciones

## 5. Lean Canvas
Genera un Lean Canvas completo incluyendo:
- Problemas
- Segmentos de clientes
- Propuesta única de valor
- Solución
- Canales
- Fuentes de ingresos
- Costes
- Métricas clave
- Ventaja competitiva

# Output format
Responde en formato Markdown profesional y estructurado con títulos y subtítulos claros.




PROMPT2 - Use-Cases
# Role
Actúa como Business Analyst y Software Architect senior especializado en plataformas SaaS de Recursos Humanos y Applicant Tracking Systems (ATS).

# Context
Estamos diseñando el MVP de un sistema ATS moderno llamado LTI ATS. La documentación adjunta a este proyeto también puede ayudarte. 

Los principales usuarios del sistema son:
- Recruiters
- Hiring Managers
- Equipos de RRHH
- Administradores

El sistema incluye funcionalidades como:
- Gestión de candidatos
- Pipeline Kanban de selección
- Gestión de entrevistas
- Evaluaciones colaborativas
- Automatización de workflows
- Parsing de CVs mediante IA
- Reporting y métricas

# Objective
Define los 3 casos de uso más importantes del MVP de LTI ATS centrados en recruiters y hiring managers.

# Instructions

Para cada caso de uso incluye:

## 1. Nombre del caso de uso

## 2. Objetivo
Explica brevemente qué resuelve el caso de uso.

## 3. Actor principal
Indica el usuario principal involucrado.

## 4. Actores secundarios
Indica otros actores o sistemas implicados.

## 5. Precondiciones
Qué debe cumplirse antes de ejecutar el caso de uso.

## 6. Flujo principal
Describe paso a paso el flujo exitoso principal.

## 7. Flujos alternativos o excepciones
Incluye posibles errores, validaciones o caminos alternativos.

## 8. Postcondiciones
Qué ocurre al finalizar correctamente el caso de uso.

## 9. Reglas de negocio relevantes
Incluye restricciones o validaciones importantes.

## 10. Diagrama Mermaid
Genera un diagrama Mermaid válido del flujo del caso de uso.

# Additional Requirements

- Usa enfoque profesional de análisis funcional.
- Prioriza funcionalidades MVP realistas.
- Mantén claridad y estructura técnica.
- Los diagramas Mermaid deben ser compatibles con Markdown.
- Usa terminología moderna de plataformas ATS.
- Incluye automatización e IA cuando aporte valor.f
Usa diagramas Mermaid tipo flowchart TD.
Los diagramas Mermaid deben representar interacción entre actor, sistema y resultados.


PROMPT3-DATA MODEL 
# Role
Actúa como Software Architect y Data Modeler senior especializado en plataformas SaaS de Recursos Humanos y Applicant Tracking Systems (ATS).

# Context
Estamos diseñando el MVP de un ATS moderno llamado LTI ATS.

La plataforma será utilizada por:
- Recruiters
- Hiring Managers
- Equipos de RRHH
- Administradores

El sistema incluye funcionalidades como:
- Gestión de ofertas de empleo
- Gestión de candidatos
- Pipeline visual tipo Kanban
- Gestión de entrevistas
- Evaluaciones colaborativas
- Parsing automático de CVs mediante IA
- Automatización de workflows
- Notificaciones automáticas
- Reporting y métricas
- Auditoría e histórico de actividad
También puedes apoyarte en al documentación de este proyecto. 
La arquitectura objetivo es:
- SaaS cloud-native
- API-first
- Escalable
- Preparada para futuras integraciones
- Multiusuario con roles y permisos

# Objective
Diseña un modelo de datos conceptual y lógico para el MVP de LTI ATS.

# Instructions

## 1. Entidades principales
Define las entidades principales del sistema.

Incluye al menos:
- User
- Role
- Candidate
- JobOffer
- Application
- PipelineStage
- Interview
- Evaluation
- Skill
- CandidateSkill
- Document
- Notification
- ActivityLog
- AutomationRule

Puedes añadir o modificar entidades si lo consideras necesario.

---

## 2. Atributos
Para cada entidad incluye:
- Nombre del atributo
- Tipo de dato
- Obligatorio u opcional
- Descripción breve

Ejemplo:
- id: UUID (PK)
- createdAt: DateTime
- updatedAt: DateTime

---

## 3. Relaciones
Define:
- Relaciones 1:1
- Relaciones 1:N
- Relaciones N:M

Incluye:
- Primary Keys
- Foreign Keys

Explica brevemente las relaciones más importantes.

---

## 4. Reglas de negocio
Incluye reglas como:
- Un candidato puede aplicar a varias ofertas.
- Una oferta puede tener muchos candidatos.
- Una candidatura pertenece a una etapa del pipeline.
- Una entrevista pertenece a una candidatura.
- Una evaluación pertenece a una entrevista y a un evaluador.
- El email del candidato debe ser único.
- Los cambios relevantes deben quedar auditados.

Añade otras reglas si son necesarias.

---

## 5. Diagrama entidad-relación
Genera un diagrama ER completo usando Mermaid con sintaxis `erDiagram`.

---

## 6. Escalabilidad futura
Explica cómo este modelo podría evolucionar para soportar:
- Multi-tenant
- Integraciones externas
- IA avanzada
- Analytics avanzados
- Arquitectura basada en microservicios

# Output format
Organiza la respuesta en secciones claras y profesionales orientadas a documentación técnica y académica.


PROMPT4-ARQUITECTURE
Role

Actúa como Software Architect senior especializado en plataformas SaaS cloud-native, sistemas HRTech y Applicant Tracking Systems (ATS).

Context

Estamos diseñando el MVP de LTI ATS, un sistema SaaS moderno para gestión de candidatos y procesos de selección.

El sistema debe soportar:

Gestión de usuarios, roles y permisos

Gestión de ofertas de empleo

Gestión de candidatos

Parsing automático de CVs mediante IA

Pipeline visual tipo Kanban

Gestión de entrevistas

Evaluaciones colaborativas

Notificaciones automáticas

Automatización de workflows

Reporting y métricas

Auditoría e histórico de actividad

Los usuarios principales son:

Recruiters

Hiring Managers

Equipos de RRHH

Administradores

El sistema debe estar preparado para:

Escalabilidad futura

Arquitectura API-first

Integraciones externas

Multi-tenant SaaS en futuras versiones

Cumplimiento básico de seguridad y protección de datos

También puedes apoyarte en la documentación asociada a este proyecto.

Objective

Diseña la arquitectura de alto nivel del MVP de LTI ATS.

Tasks

1. Enfoque arquitectónico recomendado

Explica qué tipo de arquitectura recomiendas para el MVP:

Monolito modular

Microservicios

Arquitectura por capas

Arquitectura hexagonal

Event-driven parcial

Justifica cuál elegirías para una primera versión y por qué.

2. Componentes principales

Describe los componentes principales del sistema y sus responsabilidades:

Frontend Web App

API Backend

Módulo de autenticación y autorización

Módulo de candidatos

Módulo de ofertas

Módulo de candidaturas y pipeline

Módulo de entrevistas

Módulo de evaluaciones

Servicio de parsing IA

Servicio de notificaciones

Motor de automatizaciones

Módulo de reporting

Base de datos transaccional

Almacenamiento de documentos

Auditoría / activity log

Integraciones externas futuras

3. Responsabilidades por capa

Explica la arquitectura por capas:

Capa de presentación

Capa API / aplicación

Capa de dominio

Capa de infraestructura

Capa de datos

Servicios externos

4. Comunicación entre componentes

Describe cómo se comunican los módulos:

Peticiones HTTP/REST

Eventos internos

Procesamiento asíncrono

Webhooks futuros

Jobs programados

Integración con servicios externos

5. Seguridad y permisos

Incluye consideraciones de seguridad:

Autenticación

Autorización por roles

Control de acceso a candidatos y ofertas

Protección de documentos

Auditoría de acciones relevantes

Protección de datos personales

Buenas prácticas GDPR

6. Escalabilidad y evolución futura

Explica cómo podría evolucionar la arquitectura:

De monolito modular a microservicios o la arquitectura que consideres.

Separación futura del servicio de IA

Separación futura de reporting/analytics

Multi-tenant SaaS

Integraciones con LinkedIn, calendarios, Slack, Teams o HRIS

Uso futuro de colas de mensajes

7. Diagrama Mermaid

Genera un diagrama de arquitectura de alto nivel en Mermaid.

El diagrama debe mostrar:

Usuarios

Frontend

API Backend

Módulos principales

Base de datos

Almacenamiento de documentos

Servicio IA

Servicio de notificaciones

Reporting

Integraciones externas futuras

Usa flowchart TD o flowchart LR.

8. Decisiones arquitectónicas clave

Incluye una tabla con las principales decisiones técnicas:

Decisión

Opción elegida

Justificación

Alternativa descartada

9. Resumen final

Cierra con una explicación breve de por qué esta arquitectura es adecuada para el MVP de LTI ATS.

10. Formato de salida

Genera toda la respuesta en formato Markdown bien estructurado.

Requisitos

Usa títulos jerárquicos (#, ##, ###)

Usa tablas Markdown

Usa listas y bullets claros

Usa bloques de código para Mermaid

Mantén estilo profesional y técnico

El contenido debe parecer documentación real de arquitectura software

Explica de forma clara pero no excesivamente académica

Prioriza claridad visual y legibilidad

El resultado debe poder copiarse directamente a:

README.md

Notion

Obsidian

GitHub/GitLab

Documentación técnica de proyecto

Incluye:

Introducción

Arquitectura propuesta

Componentes

Flujo de comunicación

Seguridad

Escalabilidad

Decisiones técnicas

Diagrama Mermaid

Conclusiones

11. Estilo visual

Usa emojis moderados en títulos principales para mejorar legibilidad visual.

Ejemplo:

# 🏗 Arquitectura de Alto Nivel — LTI ATS
## 🔐 Seguridad
## 🤖 Servicio IA
## 📊 Reporting & Analytics 


PROMPT5 - C4 DIAGRAMS
Arquitectura C4 de LTI ATS

## Role

Actúa como Software Architect senior especializado en plataformas SaaS cloud-native, sistemas HRTech y Applicant Tracking Systems (ATS), con experiencia en arquitectura distribuida, modelado C4, IA aplicada al reclutamiento y diseño API-first.

---

## Context

Estamos diseñando el MVP de un ATS moderno llamado **LTI ATS**.

La plataforma será utilizada por:

* Recruiters
* Hiring Managers
* Equipos de RRHH
* Administradores

El sistema incluye funcionalidades como:

* Gestión de ofertas de empleo
* Gestión de candidatos
* Pipeline visual tipo Kanban
* Gestión de entrevistas
* Evaluaciones colaborativas
* Parsing automático de CVs mediante IA
* Matching inteligente candidato-oferta
* Automatización de workflows
* Notificaciones automáticas
* Reporting y métricas
* Auditoría e histórico de actividad

La arquitectura objetivo debe ser:

* SaaS cloud-native
* API-first
* Escalable
* Modular
* Preparada para evolucionar a microservicios
* Preparada para integraciones externas
* Multi-tenant en futuras versiones
* Orientada a eventos en ciertos procesos

También puedes apoyarte en la documentación funcional y de modelo de datos previamente definida para LTI ATS.   

---

# Objective

Diseñar la arquitectura C4 completa del MVP de LTI ATS, profundizando especialmente en el módulo de evaluación de candidatos con asistencia de IA.

---

# Instructions

## 1. Genera los siguientes niveles del modelo C4

### Nivel 1 — System Context Diagram

Incluye:

* Usuarios principales
* Sistemas externos
* Integraciones futuras
* Relación entre actores y plataforma

Actores mínimos:

* Recruiter
* Hiring Manager
* HR Admin
* Candidate

Sistemas externos sugeridos:

* LinkedIn
* Email Service
* Calendar Service
* AI Parsing Service
* Identity Provider (SSO)
* Storage Service

---

### Nivel 2 — Container Diagram

Define los principales contenedores del sistema.

Incluye al menos:

* Frontend Web App
* Backend API
* Authentication Service
* Candidate Management Service
* Evaluation Service
* AI Evaluation Engine
* Notification Service
* Workflow Automation Engine
* Reporting Service
* PostgreSQL Database
* Object Storage
* Message Broker/Event Bus

Para cada contenedor especifica:

* Responsabilidad
* Tecnología sugerida
* Tipo de comunicación
* Datos gestionados

---

### Nivel 3 — Component Diagram

Profundiza específicamente en:

# Módulo de evaluación de candidatos con IA

Incluye componentes como:

* Evaluation Controller
* Evaluation Service
* Scorecard Engine
* AI Recommendation Engine
* Candidate Scoring Engine
* Feedback Aggregator
* Audit Logger
* Notification Publisher
* Prompt Management Component
* Explainability Component

Describe:

* Responsabilidades
* Relaciones entre componentes
* Flujo de datos
* Eventos emitidos
* APIs internas

---

## 2. Describe el flujo completo de evaluación IA

Explica paso a paso:

1. El recruiter inicia evaluación
2. El hiring manager completa scorecards
3. El sistema consolida feedback
4. El motor IA calcula scoring
5. El sistema genera recomendaciones
6. Se actualiza el pipeline
7. Se generan métricas y auditoría
8. Se notifican usuarios

Incluye:

* Inputs
* Outputs
* Eventos
* Persistencia
* Automatizaciones

---

## 3. Arquitectura técnica

Explica:

* Por qué usar monolito modular en el MVP
* Cómo evolucionar a microservicios
* Estrategia API-first
* Uso de eventos asíncronos
* Seguridad y RBAC
* Escalabilidad horizontal
* Observabilidad y logging
* Gestión documental de CVs
* Integración futura con IA generativa

---

## 4. Tecnologías sugeridas

Propón stack moderno para:

* Frontend
* Backend
* Base de datos
* IA
* Mensajería
* Cloud
* Observabilidad
* CI/CD

Justifica brevemente cada decisión.

---

## 5. Diagramas

Genera todos los diagramas en:

* Mermaid
* Structurizr DSL (opcional pero recomendado)

Los diagramas deben ser:

* Claros
* Profesionales
* Escalables
* Bien organizados
* Consistentes con el modelo C4 oficial

---

## 6. Buenas prácticas

Aplica:

* Domain-Driven Design (DDD)
* Separation of Concerns
* Clean Architecture
* Event-Driven Architecture
* SOLID
* Security by Design
* Observabilidad
* Preparación para multi-tenant

---

# Output esperado

Entrega:

1. Explicación arquitectónica
2. Diagramas C4 completos
3. Decisiones técnicas justificadas
4. Flujo de evaluación IA detallado
5. Riesgos técnicos y mitigaciones
6. Roadmap evolutivo de arquitectura

---
