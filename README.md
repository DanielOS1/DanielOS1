<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/header-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="assets/header-light.svg">
  <img alt="Daniel Olivares Salazar — Full Stack Developer" src="assets/header-dark.svg" width="100%">
</picture>

<br>

Ingeniero Civil en Computación e Informática por la Universidad Católica del Norte. Construyo
aplicaciones web de extremo a extremo: interfaces en React, Next.js y Angular
sobre APIs REST y GraphQL en NestJS y Java Spring Boot.

En **RedSalud** levanté ocho módulos de un CRM que hoy opera en nueve centros
médicos del país. También desarrollé productos frontend en Angular 18 para
**Thoughtworks** y actualmente construyo herramientas propias de automatización
y aplicaciones full stack.

<img src="assets/rule.svg" width="100%" alt="">

## Proyectos

### CRM Importante Empresa del área de la salud — Gestión de Cartera Hospitalaria

CRM interno para la gestión de cartera de deuda hospitalaria, desarrollado para
una importante empresa del área de la salud y actualmente utilizado en nueve centros médicos del país.
Participé en el levantamiento de ocho módulos que cubren el flujo completo desde
la carga masiva de información clínica y financiera hasta la prefacturación,
facturación, cobranza y asignación de cartera a ejecutivos.

El frontend está construido en React y consume una API en Spring Boot. La
arquitectura está organizada por dominios funcionales y utiliza React Query para
el estado del servidor, Zustand para estado global y rutas protegidas según los
roles de cada usuario. También incluye procesamiento y validación de archivos
Excel/CSV, flujos de validación antes de persistir información, wizards para
procesos de facturación y dashboards con indicadores de cartera y cobranza.

<img src="https://img.shields.io/badge/React-161B22?style=flat-square&logo=react&logoColor=C9A227" alt="React">
<img src="https://img.shields.io/badge/TypeScript-161B22?style=flat-square&logo=typescript&logoColor=C9A227" alt="TypeScript">
<img src="https://img.shields.io/badge/Vite-161B22?style=flat-square&logo=vite&logoColor=C9A227" alt="Vite">
<img src="https://img.shields.io/badge/Tailwind%20CSS-161B22?style=flat-square&logo=tailwindcss&logoColor=C9A227" alt="Tailwind CSS">
<img src="https://img.shields.io/badge/Zustand-161B22?style=flat-square&logo=react&logoColor=C9A227" alt="Zustand">
<img src="https://img.shields.io/badge/TanStack%20Query-161B22?style=flat-square&logo=reactquery&logoColor=C9A227" alt="TanStack Query">
<img src="https://img.shields.io/badge/Docker-161B22?style=flat-square&logo=docker&logoColor=C9A227" alt="Docker">


<br>

### LolosApp — Gestión de Grupos

App de gestión para organizaciones estudiantiles, en uso real por una
organización juvenil. El backend es una API REST en NestJS con modelo de datos
en PostgreSQL (Neon); el cliente móvil está construido en React Native /
Expo, con cinco módulos: autenticación, grupos, tareas, finanzas y metas.

Desplegada en Google Cloud Run, con Google Secret Manager y Cloud Build para
el pipeline, y la base de datos en Neon. Antes del despliegue pasó por una
auditoría de seguridad propia: guards de autorización, control de acceso por
grupo, migraciones versionadas en vez de sincronización automática de
esquema, validación de configuración y separación de secretos del control de
versiones.

<img src="https://img.shields.io/badge/React%20Native-161B22?style=flat-square&logo=react&logoColor=C9A227" alt="React Native">
<img src="https://img.shields.io/badge/Expo-161B22?style=flat-square&logo=expo&logoColor=C9A227" alt="Expo">
<img src="https://img.shields.io/badge/NestJS-161B22?style=flat-square&logo=nestjs&logoColor=C9A227" alt="NestJS">
<img src="https://img.shields.io/badge/PostgreSQL-161B22?style=flat-square&logo=postgresql&logoColor=C9A227" alt="PostgreSQL">
<img src="https://img.shields.io/badge/Google%20Cloud-161B22?style=flat-square&logo=googlecloud&logoColor=C9A227" alt="Google Cloud">

  → [Backend](https://github.com/DanielOS1/l-server)  ·  [App móvil](https://github.com/DanielOS1/l-client)

<br>

### Sigma — Gestión de Centros de Acuicultura

Frontend desarrollado en **Angular 18** para Sigma, un sistema de gestión para
centros de acuicultura. El proyecto permite administrar usuarios y roles,
centros de cultivo, pozas o estanques, sensores y dispositivos.

Incluye un flujo de autenticación basado en RUT chileno, detección dinámica del
tipo de inicio de sesión y verificación en dos pasos. La aplicación maneja
distintos roles —desde administradores de centro hasta super administradores—
con dashboards y rutas específicas, además de guards de autenticación y
autorización.

El proyecto utiliza componentes standalone y soporte para Server-Side Rendering,
con una arquitectura organizada por dominios y servicios para los distintos
recursos del sistema.

<img src="https://img.shields.io/badge/Angular-161B22?style=flat-square&logo=angular&logoColor=C9A227" alt="Angular">
<img src="https://img.shields.io/badge/TypeScript-161B22?style=flat-square&logo=typescript&logoColor=C9A227" alt="TypeScript">
<img src="https://img.shields.io/badge/Angular%20Material-161B22?style=flat-square&logo=angular&logoColor=C9A227" alt="Angular Material">
<img src="https://img.shields.io/badge/Tailwind%20CSS-161B22?style=flat-square&logo=tailwindcss&logoColor=C9A227" alt="Tailwind CSS">
<img src="https://img.shields.io/badge/RxJS-161B22?style=flat-square&logo=reactivex&logoColor=C9A227" alt="RxJS">
<img src="https://img.shields.io/badge/SSR-161B22?style=flat-square&logo=angular&logoColor=C9A227" alt="Server Side Rendering">

  → [Repositorio](https://github.com/DanielOS1/sigma-front)

<br>

### Job Radar

Los filtros de los portales de empleo mienten: marcan como remoto lo que es
híbrido y como junior lo que pide tres años. Job Radar lee la descripción
completa de cada aviso —no la metadata declarada— y lo clasifica como apto,
ambiguo o descartado según reglas explícitas. Notifica por Telegram y registra
todo lo analizado, incluido lo descartado y por qué, para poder auditar el
filtro.

Corre cada tres horas sobre GitHub Actions. Sin servidor: el propio repositorio
hace de base de datos.

<img src="https://img.shields.io/badge/TypeScript-161B22?style=flat-square&logo=typescript&logoColor=C9A227" alt="TypeScript">
<img src="https://img.shields.io/badge/Node.js-161B22?style=flat-square&logo=nodedotjs&logoColor=C9A227" alt="Node.js">
<img src="https://img.shields.io/badge/GitHub%20Actions-161B22?style=flat-square&logo=githubactions&logoColor=C9A227" alt="GitHub Actions">
<img src="https://img.shields.io/badge/Cheerio-161B22?style=flat-square&logo=cheerio&logoColor=C9A227" alt="Cheerio">

  → [Repositorio](https://github.com/DanielOS1/job_radar)

<br>

### Gestión Médica

Sistema de gestión clínica construido en equipo durante la carrera. El backend
en NestJS expone una API GraphQL sobre PostgreSQL; el frontend web está en
Next.js y lo complementa una aplicación móvil. Es el proyecto donde más lejos
llevamos la separación entre capas: un esquema GraphQL como contrato único
consumido por dos clientes distintos.

Mi rol fue el desarrollo del frontend, junto a otra persona del equipo.

<img src="https://img.shields.io/badge/Next.js-161B22?style=flat-square&logo=nextdotjs&logoColor=C9A227" alt="Next.js">
<img src="https://img.shields.io/badge/NestJS-161B22?style=flat-square&logo=nestjs&logoColor=C9A227" alt="NestJS">
<img src="https://img.shields.io/badge/GraphQL-161B22?style=flat-square&logo=graphql&logoColor=C9A227" alt="GraphQL">
<img src="https://img.shields.io/badge/PostgreSQL-161B22?style=flat-square&logo=postgresql&logoColor=C9A227" alt="PostgreSQL">

  → [Frontend](https://github.com/DanielOS1/cchad-frontend)  ·  [Backend](https://github.com/DanielOS1/cchad-backend)

<br>

### Plataforma de Ecommerce

Arquitectura de microservicios con seis servicios en NestJS que se comunican de
forma asíncrona vía RabbitMQ y se exponen con GraphQL. El frontend en React
consume esa API e integra Transbank, cubriendo el flujo de transacciones de
punta a punta.

<img src="https://img.shields.io/badge/NestJS-161B22?style=flat-square&logo=nestjs&logoColor=C9A227" alt="NestJS">
<img src="https://img.shields.io/badge/GraphQL-161B22?style=flat-square&logo=graphql&logoColor=C9A227" alt="GraphQL">
<img src="https://img.shields.io/badge/RabbitMQ-161B22?style=flat-square&logo=rabbitmq&logoColor=C9A227" alt="RabbitMQ">
<img src="https://img.shields.io/badge/React-161B22?style=flat-square&logo=react&logoColor=C9A227" alt="React">

<img src="assets/rule.svg" width="100%" alt="">

## Stack

<img src="https://img.shields.io/badge/React-161B22?style=flat-square&logo=react&logoColor=C9A227" alt="React">
<img src="https://img.shields.io/badge/Next.js-161B22?style=flat-square&logo=nextdotjs&logoColor=C9A227" alt="Next.js">
<img src="https://img.shields.io/badge/TypeScript-161B22?style=flat-square&logo=typescript&logoColor=C9A227" alt="TypeScript">
<img src="https://img.shields.io/badge/Angular-161B22?style=flat-square&logo=angular&logoColor=C9A227" alt="Angular">
<img src="https://img.shields.io/badge/React%20Native-161B22?style=flat-square&logo=react&logoColor=C9A227" alt="React Native">

<img src="https://img.shields.io/badge/Node.js-161B22?style=flat-square&logo=nodedotjs&logoColor=C9A227" alt="Node.js">
<img src="https://img.shields.io/badge/NestJS-161B22?style=flat-square&logo=nestjs&logoColor=C9A227" alt="NestJS">
<img src="https://img.shields.io/badge/Spring%20Boot-161B22?style=flat-square&logo=springboot&logoColor=C9A227" alt="Spring Boot">
<img src="https://img.shields.io/badge/GraphQL-161B22?style=flat-square&logo=graphql&logoColor=C9A227" alt="GraphQL">

<img src="https://img.shields.io/badge/PostgreSQL-161B22?style=flat-square&logo=postgresql&logoColor=C9A227" alt="PostgreSQL">
<img src="https://img.shields.io/badge/MongoDB-161B22?style=flat-square&logo=mongodb&logoColor=C9A227" alt="MongoDB">
<img src="https://img.shields.io/badge/Docker-161B22?style=flat-square&logo=docker&logoColor=C9A227" alt="Docker">
<img src="https://img.shields.io/badge/GitHub%20Actions-161B22?style=flat-square&logo=githubactions&logoColor=C9A227" alt="GitHub Actions">

<img src="assets/rule.svg" width="100%" alt="">

## Contacto

Abierto a posiciones full stack.

<a href="https://www.linkedin.com/in/danielos1-dev">
  <img src="https://img.shields.io/badge/LinkedIn-161B22?style=flat-square&logo=linkedin&logoColor=C9A227" alt="LinkedIn">
</a>
<a href="mailto:danielolivares60@gmail.com">
  <img src="https://img.shields.io/badge/Correo-161B22?style=flat-square&logo=gmail&logoColor=C9A227" alt="Correo">
</a>
