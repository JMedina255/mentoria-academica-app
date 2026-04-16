# Mentoria-academica-app
# 🎓 MentoriaAcademicaAppMobil 📱

![React Native](https://img.shields.io/badge/React_Native-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white)
![Expo](https://img.shields.io/badge/Expo-000020?style=for-the-badge&logo=expo&logoColor=white)

## 🚀 Descripción del Proyecto
**MentoriaAcademicaAppMobil** es una plataforma móvil diseñada para conectar a estudiantes universitarios con mentores especializados. El objetivo principal es facilitar el intercambio de conocimientos y fortalecer el rendimiento académico mediante una gestión eficiente de sesiones y un algoritmo de recomendación inteligente.

Este proyecto forma parte del desarrollo de tesis para el noveno ciclo de la carrera de **Ingeniería de Sistemas**.

## ✨ Características Principales
- **Gestión de Roles:** Flujos personalizados para Estudiantes y Mentores.
- **Buscador de Mentores:** Filtros avanzados por materia, carrera y habilidades.
- **Sistema de Solicitudes:** Gestión en tiempo real de peticiones de mentoría.
- **Algoritmo de Matching:** Recomendaciones basadas en las necesidades del estudiante y la experiencia del mentor (Web Scraping / Data Processing).
- **Notificaciones en Tiempo Real:** Comunicación directa mediante Supabase Realtime.

## 🛠️ Stack Tecnológico
- **Frontend:** [React Native](https://reactnative.dev/) con [Expo](https://expo.dev/).
- **Backend as a Service (BaaS):** [Supabase](https://supabase.com/) (Auth, Database, Storage).
- **Base de Datos:** PostgreSQL.
- **Gestión de Estado:** Context API / React Hooks.
- **Estilos:** NativeWind (Tailwind CSS) o Styled Components.

## 📁 Estructura del Repositorio
```text
/
├── src/
│   ├── api/          # Configuración de clientes (Supabase)
│   ├── components/   # Componentes reutilizables UI
│   ├── context/      # Manejo de estado global (Auth, User)
│   ├── hooks/        # Lógica personalizada
│   ├── navigation/   # Configuración de rutas
│   ├── screens/      # Pantallas principales de la App
│   └── utils/        # Funciones auxiliares y constantes
├── assets/           # Imágenes y recursos estáticos
├── supabase/         # Scripts SQL y configuraciones de DB
└── App.js            # Punto de entrada de la aplicación
