## simple-spring-boot-boilerplate

Quick start for spring boot project. 

### Prerequisites
- JDK 17+
- Spring Boot 3.2.2
- Gradle 8.5

### Dependency

- spring-boot-starter-web
- spring-boot-starter-data-jpa
- h2
- lombok
- spring-boot-starter-test

### Quick start

1. Clone repo.
    ```bash
    git clone https://github.com/kkangmj/simple-spring-boot-boilerplate.git
    ```
2. Go to `File > Project Structure > Project > Project Name` and update project name with new name.
3. Go to `settings.gradle` file and change rootProject name as same.
    ```gradle
    rootProject.name = 'sth u want'
    ```
4. Exit IntelliJ IDEA and rename project root folder name in file explorer. 
5. Restart IntelliJ and import project again.
6. Right click on pacakge(com.mango.springbootboilerplate) and rename it.
7. Done for setup! Start coding!
