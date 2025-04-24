# 🐧 Guide d'installation Linux – Dev Spring Boot

Salut manchot développeur 🐧 ! On va transformer ton terminal en outil de microservice master 💪

---

## 1️⃣ Installer Java 17 (JDK)

```bash
sudo apt update
sudo apt install openjdk-17-jdk -y
```

Configure `JAVA_HOME` :
```bash
echo 'export JAVA_HOME=/usr/lib/jvm/java-17-openjdk-amd64' >> ~/.bashrc
echo 'export PATH=$JAVA_HOME/bin:$PATH' >> ~/.bashrc
source ~/.bashrc
```

Test :
```bash
java -version
```

---

## 2️⃣ Installer Maven

```bash
sudo apt install maven -y
```

Test :
```bash
mvn -v
```

---

## 3️⃣ Installer Docker 🐳

```bash
sudo apt install docker.io -y
sudo systemctl start docker
sudo systemctl enable docker
sudo usermod -aG docker $USER
newgrp docker
```

Test :
```bash
docker --version
```

---

## 4️⃣ IDE préféré ? 😎

### IntelliJ :
```bash
snap install intellij-idea-community --classic
```

### VS Code :
```bash
sudo snap install code --classic
```

Extensions à installer :
- Java Pack
- Spring Boot Extension Pack
- Docker

---

## 5️⃣ Installer Tomcat (optionnel)

```bash
wget https://downloads.apache.org/tomcat/tomcat-10/v10.1.13/bin/apache-tomcat-10.1.13.tar.gz
tar -xvzf apache-tomcat*.tar.gz
export CATALINA_HOME=~/apache-tomcat-*
```

---

Tu es ready pour Spring Boot ! 🌼
