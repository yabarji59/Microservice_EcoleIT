# 🪟 Guide d'installation Windows – Spring Boot Ready

Bienvenue jeune développeur ! 👩‍💻 Voici comment transformer ton PC Windows en machine de guerre pour coder des microservices avec Spring Boot 🚀

---

## 1️⃣ Installer Java 17 (JDK)

1. Va sur 👉 [https://adoptium.net](https://adoptium.net)
2. Télécharge le JDK 17 pour Windows
3. Installe-le

### 🔧 Variables d’environnement
- Va dans « Ce PC » > clic droit > Propriétés > Paramètres système avancés
- Bouton « Variables d’environnement »
  - Ajoute une variable `JAVA_HOME` : `C:\Program Files\Eclipse Adoptium\jdk-17...`
  - Dans `Path`, ajoute : `%JAVA_HOME%\bin`

Vérifie dans le terminal :
```bash
java -version
```

---

## 2️⃣ Installer Maven

1. Télécharge ici : [https://maven.apache.org/download.cgi](https://maven.apache.org/download.cgi)
2. Décompresse et place dans `C:\dev\maven`

Variables :
- `MAVEN_HOME` → `C:\dev\maven`
- `Path` → `%MAVEN_HOME%\bin`

Vérifie :
```bash
mvn -v
```

---

## 3️⃣ Installer Docker 🐳

1. Télécharge Docker Desktop : [https://www.docker.com/products/docker-desktop](https://www.docker.com/products/docker-desktop)
2. Suis les instructions, redémarre si nécessaire

Test :
```bash
docker --version
```

---

## 4️⃣ Installer un IDE ✨

### 🔹 IntelliJ IDEA Community
- [https://www.jetbrains.com/idea/download](https://www.jetbrains.com/idea/download)
- Extensions :
  - Spring Assistant
  - Docker Plugin
  - Maven Helper

### 🔹 Visual Studio Code
- [https://code.visualstudio.com](https://code.visualstudio.com)
- Extensions :
  - Java Extension Pack
  - Spring Boot Extension Pack
  - Docker
  - Maven for Java

---

## 5️⃣ (Bonus) Installer Tomcat 🐱

Télécharge : [https://tomcat.apache.org](https://tomcat.apache.org)  
Dézippe, ajoute `TOMCAT_HOME` et mets dans `Path`

---

Prêt(e) ? Let’s Spring ! 🌱
