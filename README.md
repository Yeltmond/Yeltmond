# 👋 Hola, soy Yeltsing Mondragón

<img src="img/484848509_2391219787878473_7571962223933263919_n.jpg" alt="Foto de Yeltsing Mondragón" width="180" align="right" style="border-radius:50%;">

**Egresado de Ingeniería de Sistemas**  
Apasionado por la **tecnología**.  

---

## 🧠 Sobre mí

Soy un estudiante del último semestre de Ingeniería de Sistemas con experiencia en desarrollo full-stack, sistemas empresariales complejos y soluciones IoT. Me especializo en crear **aplicaciones escalables** con arquitectura moderna y tecnologías de punta.

### Áreas de enfoque:
- 🏭 Desarrollo de **sistemas de gestión logística empresarial** (B2E)  
- 🚀 **Full-stack development** con TypeScript, React, NestJS y Firebase  
- 🛒 Plataformas de **e-commerce y marketplace**  
- 🌾 Sistemas **IoT** para agricultura inteligente y monitoreo ambiental  
- 📊 Arquitecturas **multi-tenant** con bases de datos complejas y RBAC  
- 💳 Integración de **pasarelas de pago** y APIs externas  
- 🤖 **Machine Learning** y **reconocimiento facial**  

---

## 🚀 Proyectos Destacados

### 🏭 **LINEANICA** — Sistema de Gestión Logística B2E
![TypeScript](https://img.shields.io/badge/TypeScript-92.1%25-3178C6?logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-3.5%25-F7DF1E?logo=javascript&logoColor=black)
![CSS](https://img.shields.io/badge/CSS-3.4%25-1572B6?logo=css3&logoColor=white)

**Sistema integral de gestión logística para agencia de envíos internacional.** Plataforma empresarial completa que automatiza el ciclo completo: recepción, almacenamiento, tracking automático, tránsito, entregas y facturación.

#### 🎯 ¿Qué hace Lineanica?
Lineanica es una solución B2E (Business-to-Employee) que transforma operaciones logísticas complejas en un sistema automatizado y escalable. Maneja múltiples sucursales, roles de usuario especializados y proporciona visibilidad en tiempo real de toda la cadena logística.

#### 📋 Características Clave

**📦 Gestión de Paquetes**
- Ciclo de vida completo: Recepción → Almacenamiento → Tránsito → En Sucursal → Entrega → Facturado
- Tracking automático integrado con CargoTrack (BullMQ workers)
- Código de locker único por cliente
- Búsqueda avanzada y filtrado de paquetes
- Historial completo de movimientos

**🏢 Gestión Multi-Sucursal (Multi-Tenant)**
- 4 sucursales operativas: Managua, León, Granada, Masaya
- Aislamiento lógico de datos por sucursal
- Permisos específicos y configuración independiente
- 6 schemas PostgreSQL separados: `auth`, `core`, `logistics`, `finance`, `notifications`, `audit`

**🔐 Control de Acceso Basado en Roles (RBAC)**
- **SuperAdmin**: Control total, gestión de usuarios y tarifas globales
- **Admin Sucursal**: Gestión local de sucursal asignada
- **Bodega**: Operador de almacén, asignación de anaqueles
- **Cajero Sucursal**: Operador de caja, cobro de fletes y facturas
- **Atención al Cliente**: Soporte y gestión de clientes
- **Developer**: Acceso técnico para soporte

**💬 Notificaciones Automáticas en Tiempo Real**
- **Email**: Integración Resend para notificaciones de estado
- **WhatsApp**: Meta Cloud API para tracking en tiempo real
- Notificaciones personalizadas por evento

**💰 Módulo de Caja y Facturación**
- Caja por sucursal con apertura/cierre de turno
- Cobro de fletes y servicios adicionales
- Generación de facturas automáticas
- Tarifas dinámicas actualizables
- Tasa de cambio en tiempo real

**📊 Dashboards y Reportería Avanzada**
- KPIs en tiempo real (paquetes, entregas, ingresos)
- Gráficos analíticos interactivos (Recharts)
- Exportación de reportes a Excel (ExcelJS)
- Filtrado por fecha, sucursal y valores

**🏗️ Arquitectura del Sistema**

| Capa | Tecnología |
|---|---|
| Backend API | NestJS + TypeScript |
| Base de Datos | PostgreSQL 15 (Docker) — 6 schemas multi-dominio |
| ORM | Prisma (type-safe) |
| Queue/Workers | BullMQ + Redis (Docker) |
| Frontend | React 18 + Vite + TypeScript |
| Estado Global | Zustand |
| Estilos | Tailwind CSS |
| Gráficos | Recharts |
| Reportes | ExcelJS |
| Email | Resend |
| WhatsApp | Meta Cloud API |
| Contenerización | Docker + Docker Compose |

**Stack:** TypeScript (92.1%) | NestJS | React 18 | Vite | PostgreSQL | Redis | Prisma | Docker

---

### 🛍️ **MKPLACENI** — Marketplace Empresarial
![TypeScript](https://img.shields.io/badge/TypeScript-97.7%25-3178C6?logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/Python-1.5%25-3776AB?logo=python&logoColor=white)
![Other](https://img.shields.io/badge/Other-0.8%25-gray)

**Plataforma marketplace empresarial moderna para compra y venta de productos.** E-commerce completo con gestión de vendedores, catálogos dinámicos, carrito de compras, pagos integrados y panel administrativo.

#### 🎯 ¿Qué hace MKPLACENI?
MKPLACENI es una plataforma de comercio electrónico profesional que conecta compradores y vendedores. Proporciona una experiencia de compra intuitiva, integración de pagos segura y herramientas de gestión potentes para vendedores.

#### 📋 Características Clave

**🛒 Experiencia de Compra**
- Catálogos de productos dinámicos y searchables
- Carrito de compras intuitivo
- Checkout seguro con validación en tiempo real
- Integración PayPal para pagos internacionales
- UI responsive con Radix UI components

**👨‍💼 Gestión de Vendedores**
- Registro y autenticación con Firebase
- Panels de control personalizados
- Gestión de inventario
- Análisis de ventas y métricas

**📱 Características Técnicas**
- Autenticación segura: Firebase Authentication
- Mapas interactivos: Google Maps Integration
- Optimización de imágenes: Sharp para carga rápida
- Dashboards analíticos: Recharts
- Drag & drop para gestión de productos
- Sincronización en tiempo real con Firebase Firestore

**🏗️ Stack Tecnológico**

| Capa | Tecnología |
|---|---|
| Frontend Framework | Next.js 16 |
| Lenguaje | TypeScript (97.7%) |
| Backend | Firebase (serverless) |
| Base de Datos | Firestore |
| Estado Global | Zustand |
| Estilos | TailwindCSS v4 |
| UI Components | Radix UI |
| Hosting | Vercel |

**Stack:** TypeScript (97.7%) | Next.js 16 | Firebase | Firestore | Zustand | TailwindCSS  
**Link:** [🌐 https://mkplaceni.vercel.app](https://mkplaceni.vercel.app)

---

### 🌾 **MONIT AGRO** — Plataforma IoT Agrícola
![Python](https://img.shields.io/badge/Python-43%25-3776AB?logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-41.9%25-F7DF1E?logo=javascript&logoColor=black)
![C++](https://img.shields.io/badge/C++-8.6%25-00599C?logo=cplusplus&logoColor=white)
![CSS](https://img.shields.io/badge/CSS-6.4%25-1572B6?logo=css3&logoColor=white)
![HTML](https://img.shields.io/badge/HTML-0.1%25-E34C26?logo=html5&logoColor=white)

**Plataforma IoT completa para monitoreo agrícola e ambiental en tiempo real.** Sistema end-to-end que integra sensores ESP32 distribuidos en campos agrícolas con backend de análisis y frontend de visualización.

#### 🎯 ¿Qué hace MONIT AGRO?
Monit Agro democratiza el acceso a tecnología de monitoreo agrícola profesional. Recolecta datos ambientales en tiempo real desde sensores IoT, los procesa con algoritmos de análisis y los visualiza en dashboards interactivos.

#### 📋 Características Clave

**📡 Infraestructura IoT**
- Sensores ESP32 distribuidos en campos
- Comunicación inalámbrica en tiempo real
- Recolección automática de datos
- Bajo consumo energético

**🌡️ Parámetros Monitoreados**
- Temperatura del aire y del suelo
- Humedad relativa del aire
- Humedad del suelo
- Luminosidad (intensidad de luz solar)
- Nivel de CO₂ ambiental
- pH del suelo
- Históricos de datos para análisis temporal

**📊 Backend de Procesamiento**
- Procesamiento de datos con Python (43%)
- Algoritmos de análisis y validación
- Almacenamiento persistente de históricos
- Cálculos de indicadores agrícolas
- Machine Learning básico para predicciones

**📈 Frontend Interactivo**
- Dashboards visuales en tiempo real (JavaScript 41.9%)
- Gráficos dinámicos de parámetros
- Alertas visuales para anomalías
- Históricos y tendencias
- Interfaz responsive para dispositivos móviles

**🤖 Machine Learning y Análisis**
- Predicción básica de condiciones óptimas
- Detección de anomalías en datos
- Recomendaciones de riego y fertilización
- Alertas tempranas de plagas o enfermedades

**🏗️ Stack Tecnológico**

| Capa | Tecnología |
|---|---|
| Hardware | ESP32 (C++) — 8.6% |
| Backend | Python (43%) — Flask/FastAPI |
| Frontend | JavaScript (41.9%) + HTML/CSS |
| Base de Datos | SQLite / MongoDB |
| Comunicación | MQTT / REST API |
| Visualización | Recharts / Chart.js |
| Machine Learning | Scikit-learn / TensorFlow basics |

**Stack:** Python (43%) | JavaScript (41.9%) | C++ (8.6%) | HTML/CSS | REST API

---

## 💻 Habilidades técnicas

| Lenguajes y tecnologías | Nivel / Experiencia |
|--------------------------|--------------------|
| 🔷 **TypeScript / JavaScript** | ⭐⭐⭐⭐⭐ |
| ⚛️ **React / Next.js** | ⭐⭐⭐⭐⭐ |
| 🏗️ **NestJS (Backend Framework)** | ⭐⭐⭐⭐☆ |
| 🗃️ **PostgreSQL / SQLite / Firebase** | ⭐⭐⭐⭐☆ |
| ⚙️ **Prisma ORM** | ⭐⭐⭐⭐☆ |
| 🐍 **Python** (OpenCV, NumPy, Pandas, Flask) | ⭐⭐⭐⭐☆ |
| 🔥 **Firebase** (Firestore, Functions, Auth) | ⭐⭐⭐⭐☆ |
| 💡 **Arduino / ESP32** (C++) | ⭐⭐⭐⭐☆ |
| 🎨 **HTML5 / CSS3 / TailwindCSS** | ⭐⭐⭐⭐⭐ |
| 🤖 **Machine Learning** (básico a intermedio) | ⭐⭐⭐☆☆ |
| 🧩 **Git / GitHub** | ⭐⭐⭐⭐☆ |
| 💳 **Integración de pagos** (PayPal, Meta APIs) | ⭐⭐⭐⭐☆ |
| 🌐 **REST APIs y WebSockets** | ⭐⭐⭐⭐☆ |
| 📡 **IoT y Conectividad** (MQTT, sensores) | ⭐⭐⭐⭐☆ |
| 📊 **Análisis de Datos en Tiempo Real** | ⭐⭐⭐☆☆ |
| 🐳 **Docker / Docker Compose** | ⭐⭐⭐⭐☆ |
| 🚀 **DevOps y Deployment** (Vercel, Firebase) | ⭐⭐⭐⭐☆ |
| 🔄 **Redis / BullMQ (Job Queues)** | ⭐⭐⭐⭐☆ |

---

## 🌐 Mis redes sociales

<p align="center">
  <a href="https://github.com/Yeltmond" target="_blank">
    <img src="https://img.shields.io/badge/GitHub-000?logo=github&logoColor=white">
  </a>
  <a href="https://www.instagram.com/yeltmond/" target="_blank">
    <img src="https://img.shields.io/badge/Instagram-E4405F?logo=instagram&logoColor=white">
  </a>
</p>

---

## 📬 Contacto

📧 **Email:** [yeltmondragon@gmail.com](mailto:yeltmondragon@gmail.com)  
📱 **Teléfono:** +505 8351-9105  

---

<p align="center">
  © 2025 Yeltsing Mondragón — Todos los derechos reservados.
</p>
