# GAC Pro — Gestor de Capacitaciones Corporativas

App web para gestionar el ciclo completo de capacitación de un call center: cursos, instructores, asistencia de operadores, evaluaciones y reportes.

**🔗 Demo:** https://gac-pro.vercel.app — acceso: `demo123`

## Funcionalidades

- Calendario y gestión de cursos e instructores
- Registro de asistencia y evaluaciones de operadores
- Generación de reportes (Excel / PDF)
- Panel administrativo con roles y modo edición protegido
- Sincronización en la nube con Firebase

## Stack

- JavaScript (ES6+), HTML5, CSS3 — app autocontenida, sin dependencias de build
- Firebase: Authentication + Firestore con Security Rules basadas en roles
- Deploy en Vercel

## Seguridad

Antes de su presentación formal al área de Sistemas, el proyecto pasó por una auditoría propia: se reemplazó la autenticación inicial por Firebase Auth y se reescribieron las reglas de Firestore para acceso por usuario y rol.

---
Desarrollado por [Solange Mieres](https://landing-pages-sdm.vercel.app) · SOLtech
