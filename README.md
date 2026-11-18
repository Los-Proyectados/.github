<div align="center">

# Los Jupacos

**Sistemas web y móviles para Jupaca Proyecta S.A. de C.V. · PTC 2026**

Digitalizamos los procesos de una empresa de ingeniería que todavía vivían en hojas de cálculo:
recursos humanos, contabilidad, seguimiento de estudios de suelos y laboratorio de materiales.

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Node.js](https://img.shields.io/badge/Node.js-5FA04E?style=flat-square&logo=nodedotjs&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white)
![Expo](https://img.shields.io/badge/Expo-000020?style=flat-square&logo=expo&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

</div>

---

## Proyectos

Todos los sistemas comparten **una sola base de datos PostgreSQL** (en Supabase) y las mismas cuentas
de usuario, así que un empleado, cliente o proyecto se registra una vez y lo ven todos.

### 🧑‍💼 Recursos Humanos y Administración

Plataforma **web y móvil** para planillas, contratos, horas extras, facturación y cuentas por cobrar,
con un módulo de **predicciones con Machine Learning e IA**.

- **Talento humano:** planillas automáticas (jornadas de 7 u 8 horas, ISSS, AFP y renta), contratos por
  área (administración, laboratorio, perforación) y horas extras con recargos de ley.
- **Contabilidad:** cuentas por cobrar unificadas por cliente, facturas proforma y envío masivo de
  comprobantes por correo.
- **Predicciones:** costo de planilla de los próximos 3 meses, cobros esperados, flujo de caja,
  riesgo de pago tardío por cliente y un reporte en PDF con resumen redactado por IA.
- **App móvil** (Android) conectada a la misma API.

**Stack:** React 19 + Vite + Tailwind · Node.js 22 + Express 5 · PostgreSQL · microservicio de
predicciones en Docker · React Native + Expo · Vercel y Render.

[![Web](https://img.shields.io/badge/Web-Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://jupaca-proyecta-ptc-2026.vercel.app)
[![API](https://img.shields.io/badge/API-Render-46E3B7?style=for-the-badge&logo=render&logoColor=black)](https://jupacaproyecta.onrender.com/api)
[![Swagger](https://img.shields.io/badge/Docs-Swagger-85EA2D?style=for-the-badge&logo=swagger&logoColor=black)](https://jupacaproyecta.onrender.com/docs)
[![APK](https://img.shields.io/badge/App-Android%20APK-3DDC84?style=for-the-badge&logo=android&logoColor=white)](https://expo.dev/accounts/marioivan44/projects/mobileApp/builds/e9a844a9-1e58-482b-836c-0a80e4a6de19)

### 🪨 Gestión GG (Geología y Geotecnia)

Seguimiento de los **estudios de suelos** desde la solicitud del cliente hasta la entrega del informe,
en **12 etapas**. La etapa nunca se cambia a mano: sale de lo que se registra.

- Solicitudes y **ofertas** (con la oferta oficial en Word), aceptación y anticipo.
- **Programación de campo** en calendario con arrastre, cuadrillas y feriados.
- Avance de campo, recepción de muestras y **ensayos de laboratorio**.
- **Semáforo** de cada trabajo, **alertas automáticas** (A1–A14) y tiempos que aprenden de lo real.
- Página pública de **seguimiento para el cliente**, buscador rápido (Ctrl+K) y formularios con teclado.

**Stack:** Django 6 + PostgreSQL (Supabase) · React + Vite + Tailwind 4 · pruebas con Django y Vitest
en GitHub Actions.

### 🧪 LIMS (Laboratorio de materiales)

Sistema de gestión del **laboratorio de concreto y materiales**: remisiones, colados, especímenes,
ensayos de resistencia, calendario de ensayos e informes, con **lectura de hojas escritas a mano**
para capturar medidas más rápido.

**Stack:** Django 6 + Django REST Framework + PostgreSQL · React + Vite.

> Gestión GG y LIMS viven en el mismo repositorio y comparten un **login único**: cada cuenta entra
> a los sistemas que su rol permite (Jefatura, GG o LIMS).

---

## Cómo trabajamos

- Ramas `feature/*` y `fix/*` → **pull request a `develop`** → `main` para cada versión.
- Cada PR pasa por **revisión** y por el **CI** (lint, pruebas y build) antes de entrar.
- Commits con [Conventional Commits](https://www.conventionalcommits.org/) (`feat:`, `fix:`, `docs:`…).
- Código y comentarios con nombres claros; **todo lo que ve el usuario, en español**.

---

<div align="center">

**Jupaca Proyecta S.A. de C.V.** · Software Empresarial 2026

</div>
