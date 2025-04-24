# 🍎 Guide d'installation Mac – Spring Boot Dev Setup

Hello développeur sur Mac 🍏 ! On va faire de ta machine une centrale à microservices en quelques étapes ⚡

---

## 1️⃣ Installer Java 17 via Homebrew

```bash
brew install openjdk@17
```

Ajoute au terminal :
```bash
sudo ln -sfn /opt/homebrew/opt/openjdk@17/libexec/openjdk.jdk /Library/Java/JavaVirtualMachines/openjdk-17.jdk
echo 'export JAVA_HOME=$(/usr/libexec/java_home -v17)' >> ~/.zshrc
echo 'export PATH=$JAVA_HOME/bin:$PATH' >> ~/.zshrc
source ~/.zshrc
```

Test :
```bash
java -version
```

---

## 2️⃣ Installer Maven

```bash
brew install maven
mvn -v
```

---

## 3️⃣ Installer Docker 🐳

- Va sur [https://www.docker.com/products/docker-desktop](https://www.docker.com/products/docker-desktop)
- Télécharge et installe
- Lance Docker

Test :
```bash
docker --version
```

---

## 4️⃣ IDE au choix 💻

### IntelliJ IDEA :
- https://www.jetbrains.com/idea
- Plugins : Spring Assistant, Docker Plugin, Maven Helper

### VS Code :
- https://code.visualstudio.com
- Extensions : Java Pack, Spring Boot Pack, Docker

---

## 5️⃣ Tomcat (optionnel)

```bash
brew install tomcat
```

---

Ton Mac est maintenant prêt pour du Spring à haute dose ! 🌸
