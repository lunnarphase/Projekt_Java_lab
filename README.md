https://github.com/ankitrajput0096/Dockerized_SpringBoot_PostgreSQL

1. Instalacja Maven - https://dlcdn.apache.org/maven/maven-3/3.9.9/binaries/apache-maven-3.9.9-bin.zip

Rozpakować do C:\Program Files

Zmienne środowiskowe:
M2 i M2_HOME -> C:\Program Files\apache-maven-3.9.9 
Path -> C:\Program Files\apache-maven-3.9.9\bin

2. Instalacja Java JDK-23 i zmiana zmiennych środowiskowych:
JAVA_HOME -> C:\Program Files\Java\jdk-23
Path -> C:\Program Files\Java\jdk-23\bin

3. cd do lokalizacji spring_boot_app\spring_boot_jpa, tam gdzie jest pom.xml i "mvn install" / "mvn clean install"

4. cd do lokalizacji docker-compose.yml i "docker-compose build"  **MUSI BYC URUCHOMIONY DOCKER DESKTOP

5. docker-compose up


