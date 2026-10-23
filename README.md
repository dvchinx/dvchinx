<h1 align="center"><code><img src="https://i.imgur.com/6JmNI86.jpeg" height="110px" style="border-radius: 50%; object-fit: cover; transform: scale(1.1);">⠀Bienvenido!</code></h1>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=24&duration=2800&pause=900&color=4B9FC9&center=true&vCenter=true&width=800&lines=Backend+Developer+%7C+Java+%26+Spring;Backend+%2B+IA+explicable;Programaci%C3%B3n+competitiva+y+hackathons;Contribuidor+Open+Source" alt="typing animation">
</p>

<p align="center">
  <a href="https://jesusflorez.cloud/portfolio"><img src="https://img.shields.io/badge/Portafolio-4B9FC9?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Portafolio"></a>
  <a href="https://blog.jesusflorez.cloud"><img src="https://img.shields.io/badge/Blog-0A101F?style=for-the-badge&logo=hashnode&logoColor=4B9FC9" alt="Blog"></a>
  <img src="https://img.shields.io/badge/Colombia-0A101F?style=for-the-badge&logo=googlemaps&logoColor=4B9FC9" alt="Colombia">
  <img src="https://img.shields.io/badge/Abierto_a_oportunidades-10B981?style=for-the-badge&logo=handshake&logoColor=white" alt="Abierto a oportunidades">
  <img src="https://komarev.com/ghpvc/?username=dvchinx&style=for-the-badge&color=4B9FC9&label=Visitas" alt="Visitas">
</p>

<table>
  <tr>
    <td width="60%">

### 📖 Sobre mí
Soy **Software Engineer** enfocado en **backend con Java y Spring**. Me interesa el software que se puede auditar y explicar: sistemas que no solo toman decisiones, sino que dejan registrado *por qué* las tomaron.

- 🏦 Construyo sistemas **Backend + IA** para el sector financiero: scoring crediticio y detección de fraude con ML explicable (SHAP)
- 🧱 Me gusta la **arquitectura hexagonal**: dominio limpio, sin frameworks, testeado contra infraestructura real
- 🏆 **Top 15 de Colombia en [Kattis](https://open.kattis.com/users/jesus-florez)** y top 6.000 global. También compito en Codeforces y AtCoder y participo en **hackathons**
- 🌱 Publico herramientas **open source** y documento lo que aprendo en mi [blog](https://blog.jesusflorez.cloud)
- 🇨🇴 Desde Colombia, trabajando en español e inglés

  </td>
  <td width="40%" align="center">
    <img src="https://user-images.githubusercontent.com/74038190/229223263-cf2e4b07-2615-4f87-9c38-e37600f8381a.gif" width="100%" alt="developer gif" />
  </td>
  </tr>
</table>

### ⬆ En qué ando

```yaml
trabajando_en:
  - Florez's Suite: escuchando a la comunidad y agregando features
  - Resolviendo concursos semanales de AtCoder y Codeforces en C++
aprendiendo:
  - Dynammic Programming (DP)
  - Sliding Window de tamaño variable
debatamos_sobre:
  - Java, Spring Boot, IA
  - Pasarte a Linux
```

---

## 🚀 Proyectos destacados

> [!TIP]
> Haz clic en una categoría para desplegarla. Los proyectos de **Backend + IA** son los que mejor muestran cómo trabajo.

<details open>
<summary><b>🏦 Backend + IA (sector financiero)</b></summary>

#### [Credit Scoring Engine](https://github.com/dvchinx/credit-scoring)
Motor de scoring crediticio **explicable y auditable**. Decide si aprobar, rechazar o enviar a revisión manual, y **explica por qué** con SHAP. Cada decisión queda ligada a la versión exacta del modelo y a la política vigente, así que se puede reconstruir meses después. Incluye un model registry con versiones inmutables (hash SHA-256 del artefacto, activación auditada y rollback) y simulación *what-if*.

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white) ![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white) ![Testcontainers](https://img.shields.io/badge/Testcontainers-291A3F?style=flat-square) ![Hexagonal](https://img.shields.io/badge/Arquitectura_Hexagonal-444444?style=flat-square)

#### [Fraud Detection Platform](https://github.com/dvchinx/fraud-detection)
Detección de fraude en transacciones **en tiempo real**. La ingesta es asíncrona con Kafka (`202 Accepted`). Cada transacción pasa por un motor de reglas configurable (monto, velocidad, geolocalización) y un modelo de ML explicable, y termina aprobada, bloqueada o marcada para revisión. La justificación de cada decisión queda registrada.

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white) ![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white) ![Kafka](https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white) ![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![JWT](https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white)

</details>

<details>
<summary><b>🏆 Hackathons</b></summary>

#### [Trazo](https://github.com/dvchinx/Trazo-Hackathon) · [Ver](https://trazo.jesusflorez.cloud)
Mapa interactivo de la **contratación pública en Colombia**, hecho en la *IA-Hackathon GOV-TECH de Croma*. Junta SECOP, RUES, Contraloría y Procuraduría en un solo grafo al estilo Obsidian: buscas una entidad y el grafo muestra con quién contrata, qué sanciones tiene y qué proveedores comparte con otras entidades. Tiene salas de investigación colaborativa y permite compartir un grafo por URL.

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB) ![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white) ![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white) ![Tailwind](https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white) ![Open Data](https://img.shields.io/badge/Datos_abiertos-444444?style=flat-square)

</details>

<details>
<summary><b>🌐 Mi plataforma: <a href="https://jesusflorez.cloud">jesusflorez.cloud</a></b></summary>

#### Portafolio · [Ver](https://jesusflorez.cloud/portfolio) · [Repo](https://github.com/dvchinx/portfolio) · [Docs](https://deepwiki.com/dvchinx/portafolio)
SPA en React con animaciones GSAP (ScrollTrigger, SplitText) y scroll suave con Lenis. Escrita en CSS puro, sin frameworks de estilos.

![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB) ![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white) ![GSAP](https://img.shields.io/badge/GSAP-88CE02?style=flat-square&logo=greensock&logoColor=black)

#### Blog colaborativo · [Ver](https://blog.jesusflorez.cloud) · [Repo](https://github.com/dvchinx/blog) · [Docs](https://deepwiki.com/dvchinx/blog)
Blog estático open source con posts en Markdown, rutas dinámicas, búsqueda, categorías y despliegue en contenedor con Nginx.

![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB) ![Markdown](https://img.shields.io/badge/Markdown-000000?style=flat-square&logo=markdown&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)

#### Simulación de vida artificial · [Ver](https://simulation.jesusflorez.cloud) · [Repo](https://github.com/dvchinx/simulation) · [Docs](https://deepwiki.com/dvchinx/simulation)
Ecosistema evolutivo en un grid de 200×200 donde cada organismo tiene un **genoma heredable** que evoluciona por selección natural. Simula cadena trófica, biomas, estaciones, epidemias y migración. El servidor transmite el estado por WebSocket a un cliente Canvas. Optimicé el tick de **139 ms a ~21 ms (6,7× más rápido)** vectorizando con NumPy.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white) ![WebSocket](https://img.shields.io/badge/WebSocket-010101?style=flat-square&logo=socketdotio&logoColor=white) ![Canvas](https://img.shields.io/badge/Canvas-E34F26?style=flat-square&logo=html5&logoColor=white)

</details>

<details>
<summary><b>🧰 Open source y herramientas</b></summary>

#### [EazyJava](https://github.com/dvchinx/EazyJava) ⭐
Librería Java sin dependencias que simplifica tareas comunes: `print()`/`println()` al estilo Python, casting avanzado, conversión entre bases numéricas y de texto a número.

![Java](https://img.shields.io/badge/Java_8+-ED8B00?style=flat-square&logo=openjdk&logoColor=white) ![MIT](https://img.shields.io/badge/Licencia-MIT-yellow?style=flat-square)

#### [Easy-Background](https://github.com/dvchinx/Easy-Background)
Removedor y cambiador de fondo de imágenes con IA.

#### [Fractal-Gallery](https://github.com/dvchinx/Fractal-Gallery)
Generador de arte fractal para crear imágenes y galerías.

#### [Feelings-Detector](https://github.com/dvchinx/Feelings-Detector) · [Hand-Mesh](https://github.com/dvchinx/Hand-Mesh)
Visión por computadora: detección de emociones por análisis geométrico facial y mapeo de la mano en tiempo real.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white) ![MediaPipe](https://img.shields.io/badge/MediaPipe-0097A7?style=flat-square&logo=mediapipe&logoColor=white)

</details>

<details>
<summary><b>📚 Arquitectura y aprendizaje</b></summary>

- [**Hexagonal-Architecture**](https://github.com/dvchinx/Hexagonal-Architecture): API REST con Spring y PostgreSQL siguiendo puertos y adaptadores
- [**Oauth2-Spring**](https://github.com/dvchinx/Oauth2-Spring): autenticación con GitHub y Google usando Spring Security
- [**Pizzeria-API**](https://github.com/dvchinx/Pizzeria-API): API RESTful monolítica con Spring, JPA/Hibernate y MySQL
- [**IA_Aplicada-2026**](https://github.com/dvchinx/IA_Aplicada-2026): apuntes del curso de Inteligencia Artificial Aplicada de MinTIC, en Obsidian
- [**Java-Exercises**](https://github.com/dvchinx/Java-Exercises): ejercicios de Java de principiante a experto (ES/EN)

</details>

---

## 🏆 Programación competitiva

Resuelvo problemas en **C++** y publico las soluciones, con comentarios y organizadas por dificultad y origen, en [**Competitive-Programming**](https://github.com/dvchinx/Competitive-Programming).

<p align="center">
  <a href="https://open.kattis.com/users/jesus-florez"><img src="https://img.shields.io/badge/Kattis-Top_15_Colombia_🇨🇴-FCD116?style=for-the-badge&labelColor=0A101F" alt="Kattis: Top 15 Colombia"></a>
  <a href="https://open.kattis.com/users/jesus-florez"><img src="https://img.shields.io/badge/Kattis-Top_6.000_global_🌎-4B9FC9?style=for-the-badge&labelColor=0A101F" alt="Kattis: Top 6.000 global"></a>
</p>

<p>
  <a href="https://codeforces.com/profile/dvchinx"><img src="https://img.shields.io/badge/Codeforces-dvchinx-1F8ACB?style=for-the-badge&logo=codeforces&logoColor=white" alt="Codeforces"></a>
  <a href="https://atcoder.jp/users/dvchinx"><img src="https://img.shields.io/badge/AtCoder-dvchinx-222222?style=for-the-badge" alt="AtCoder"></a>
  <a href="https://open.kattis.com/users/jesus-florez"><img src="https://img.shields.io/badge/Kattis-jesus--florez-0A101F?style=for-the-badge" alt="Kattis"></a>
  <a href="https://github.com/dvchinx/Competitive-Programming#leetcode-solutions"><img src="https://img.shields.io/badge/LeetCode-soluciones-FFA116?style=for-the-badge&logo=leetcode&logoColor=black" alt="LeetCode"></a>
</p>

---

## 📊 Actividad en GitHub

<p align="center">
  <img src="https://streak-stats.demolab.com/?user=dvchinx&card_width=900&background=0A101F&ring=4B9FC9&fire=10B981&currStreakNum=E5E7EB&sideNums=E5E7EB&currStreakLabel=4B9FC9&sideLabels=8B95A7&dates=8B95A7&border=4B9FC9&locale=es" alt="Racha de contribuciones" />
</p>

<p align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=dvchinx&theme=github_dark" width="100%" alt="Resumen de contribuciones" />
</p>

<table align="center">
  <tr>
    <td align="center" valign="top">
      <img src="https://github-readme-stats.vercel.app/api?username=dvchinx&locale=es&show_icons=true&hide_rank=true&bg_color=0A101F&title_color=4B9FC9&icon_color=10B981&text_color=E5E7EB&border_color=4B9FC9" alt="Estadísticas de GitHub" />
    </td>
    <td align="center" valign="top">
      <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=dvchinx&locale=es&layout=compact&langs_count=8&bg_color=0A101F&title_color=4B9FC9&text_color=E5E7EB&border_color=4B9FC9" alt="Lenguajes más usados" />
    </td>
  </tr>
</table>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/dvchinx/dvchinx/output/github-contribution-grid-snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/dvchinx/dvchinx/output/github-contribution-grid-snake.svg" />
    <img alt="Serpiente de contribuciones" src="https://raw.githubusercontent.com/dvchinx/dvchinx/output/github-contribution-grid-snake.svg" />
  </picture>
</p>

---

## 📫 Conectemos

> [!TIP]
> Estoy abierto a oportunidades como **Backend Developer (Java/Spring)** o en roles **Backend + IA**, y a colaborar en proyectos open source o hackathons. Si algo de lo que hago te sirve, ¡escríbeme!

<p align="center">
  <a href="https://jesusflorez.cloud"><img src="https://img.shields.io/badge/jesusflorez.cloud-4B9FC9?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Sitio web"></a>
  &nbsp;
  <a href="https://blog.jesusflorez.cloud"><img src="https://img.shields.io/badge/Blog-0A101F?style=for-the-badge&logo=hashnode&logoColor=4B9FC9" alt="Blog"></a>
  &nbsp;
  <a href="https://codeforces.com/profile/dvchinx"><img src="https://img.shields.io/badge/Codeforces-0A101F?style=for-the-badge&logo=codeforces&logoColor=4B9FC9" alt="Codeforces"></a>
  <!-- TODO: añade tus enlaces reales y descomenta
  &nbsp;
  <a href="https://www.linkedin.com/in/TU_USUARIO"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge" alt="LinkedIn"></a>
  &nbsp;
  <a href="mailto:TU_CORREO"><img src="https://img.shields.io/badge/Email-0A101F?style=for-the-badge&logo=gmail&logoColor=4B9FC9" alt="Email"></a>
  -->
</p>
