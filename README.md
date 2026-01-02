# Instalaciones necesarias para Curso de Spring Boot

Bienvenido a este repositorio donde encontrarás la lista de herramientas esenciales, extensiones y documentaciones oficiales para preparar tu entorno de desarrollo con **Java + Spring Boot** desde cero.

Este material es ideal para estudiantes, desarrolladores y profesionales que estén iniciando en el ecosistema Spring.

---

## Curso (Video/Playlist)
- YouTube (playlist): https://www.youtube.com/playlist?list=PL2Z95CSZ1N4EWw14HZ0NFD3woFcn6uiCm
- Video (clase): https://www.youtube.com/watch?v=pQGxVgaNM-o

---

# 1. Herramientas necesarias (Instalar)

- **Java JDK 17+ (Recomendado Temurin/OpenJDK)**
  - https://adoptium.net/temurin/releases/?version=17
  - (Opcional Java 21 LTS) https://adoptium.net/temurin/releases/?version=21

- **Editor / IDE (elige uno)**
  - IntelliJ IDEA (Community): https://www.jetbrains.com/idea/download/
  - Visual Studio Code: https://code.visualstudio.com/

- **Git (control de versiones)**
  - https://git-scm.com/

- **GitHub Desktop (opcional)**
  - https://desktop.github.com/download/

- **Spring Initializr (crear proyectos en 1 minuto)**
  - https://start.spring.io/

- **Cliente para probar APIs**
  - Postman: https://www.postman.com/downloads/

- **Base de datos (según el curso/proyecto)**
  - MySQL Community Server: https://dev.mysql.com/downloads/mysql/
  - MySQL Workbench (opcional): https://dev.mysql.com/downloads/workbench/
  - PostgreSQL (opcional): https://www.postgresql.org/download/

- **Cliente universal de BD (recomendado)**
  - DBeaver Community: https://dbeaver.io/download/

- **Docker Desktop (opcional, recomendado para BD/servicios)**
  - https://www.docker.com/products/docker-desktop/

---

# 2. Extensiones recomendadas (VS Code)

> Si usas VS Code, instala estas extensiones:

- **Extension Pack for Java**
  - https://marketplace.visualstudio.com/items?itemName=vscjava.vscode-java-pack

- **Spring Boot Extension Pack (Spring Tools for VS Code)**
  - https://marketplace.visualstudio.com/items?itemName=vmware.vscode-boot-dev-pack

- (Opcional) **REST Client (para probar endpoints rápido)**
  - https://marketplace.visualstudio.com/items?itemName=humao.rest-client

---

# 3. Plugins recomendados (IntelliJ IDEA)

> Si usas IntelliJ:

- Lombok (si tu proyecto lo usa): https://plugins.jetbrains.com/plugin/6317-lombok
- (Opcional) SonarLint: https://plugins.jetbrains.com/plugin/7973-sonarlint

---

# 4. Build tools (solo si los necesitas)

> Normalmente Spring Boot trae **Maven Wrapper** (`mvnw`) o **Gradle Wrapper** (`gradlew`), así que **no siempre** debes instalar Maven/Gradle manualmente.

- Apache Maven (opcional): https://maven.apache.org/download.cgi
- Gradle (opcional): https://gradle.org/install/

---

# 5. Documentaciones oficiales (para estudiar bien)

- Spring Boot Docs: https://docs.spring.io/spring-boot/
- Requisitos del sistema (Java/Gradle/Maven): https://docs.spring.io/spring-boot/system-requirements.html
- Spring Guides (tutoriales paso a paso): https://spring.io/guides
- Spring Boot Quickstart: https://spring.io/quickstart
- Spring Initializr: https://start.spring.io/
- Java en VS Code: https://code.visualstudio.com/docs/languages/java
- Postman Docs: https://learning.postman.com/
- Docker Docs: https://docs.docker.com/

---

# 6. Verificación rápida (para validar que todo quedó bien)

En consola/terminal:

- `java -version`
- `git --version`

Para ejecutar un proyecto Spring Boot (Maven):
- `./mvnw spring-boot:run`
o en Windows:
- `mvnw spring-boot:run`

---

# 7. Recomendaciones

- Instala **Java 17+** y verifica `java -version` antes de abrir el IDE.
- Crea los proyectos desde **Spring Initializr** para no perder tiempo configurando.
- Usa Postman para validar endpoints desde el día 1.
- Si vas a trabajar con BD, usa Docker o instala MySQL/PostgreSQL local.

---

# 8. Autor

Curso creado y mantenido por: **[Tu Nombre Aquí]**
