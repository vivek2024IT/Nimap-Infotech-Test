<project xmlns="http://maven.apache.org/POM/4.0.0"
         xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
         xsi:schemaLocation="http://maven.apache.org/POM/4.0.0 http://maven.apache.org/xsd/maven-4.0.0.xsd">
    <modelVersion>4.0.0</modelVersion>

    <groupId>com.example</groupId>
    <artifactId>springboot-crud</artifactId>
    <version>0.0.1-SNAPSHOT</version>
    <name>SpringBoot CRUD</name>
    <description>CRUD application using Spring Boot and JPA</description>

    <properties>
        <java.version>1.8</java.version>
        <!-- Updated Spring Boot version -->
        <spring.boot.version>2.7.18</spring.boot.version> <!-- You can update this to a newer version if desired -->
    </properties>

    <dependencies>
        <!-- Spring Boot Dependencies -->
        <dependency>
            <groupId>org.springframework.boot</groupId>
            <artifactId>spring-boot-starter-data-jpa</artifactId>
            <version>${spring.boot.version}</version> <!-- Use version property -->
        </dependency>
        <dependency>
            <groupId>org.springframework.boot</groupId>
            <artifactId>spring-boot-starter-web</artifactId>
            <version>${spring.boot.version}</version> <!-- Use version property -->
        </dependency>
        <dependency>
            <groupId>org.springframework.boot</groupId>
            <artifactId>spring-boot-starter-validation</artifactId>
            <version>${spring.boot.version}</version> <!-- Use version property -->
        </dependency>

        <!-- MySQL JDBC Driver -->
        <dependency>
            <groupId>mysql</groupId>
            <artifactId>mysql-connector-java</artifactId>
            <version>8.0.29</version> <!-- Add appropriate version -->
        </dependency>

        <!-- Lombok (Optional, for reducing boilerplate code) -->
        <dependency>
            <groupId>org.projectlombok</groupId>
            <artifactId>lombok</artifactId>
            <version>1.18.22</version> <!-- Add appropriate version -->
            <scope>provided</scope>
        </dependency>

        <!-- Spring Boot DevTools (Optional, for automatic restart) -->
        <dependency>
            <groupId>org.springframework.boot</groupId>
            <artifactId>spring-boot-devtools</artifactId>
            <version>${spring.boot.version}</version> <!-- Use version property -->
            <scope>runtime</scope>
        </dependency>

        <!-- JUnit and Test Dependencies -->
        <dependency>
            <groupId>org.springframework.boot</groupId>
            <artifactId>spring-boot-starter-test</artifactId>
            <version>${spring.boot.version}</version> <!-- Use version property -->
            <scope>test</scope>
        </dependency>

        <!-- Logging Dependency -->
        <dependency>
            <groupId>org.springframework.boot</groupId>
            <artifactId>spring-boot-starter-logging</artifactId>
            <version>${spring.boot.version}</version> <!-- Use version property -->
        </dependency>

        <!-- H2 Database (For In-Memory Database - Optional for testing) -->
        <dependency>
            <groupId>com.h2database</groupId>
            <artifactId>h2</artifactId>
            <version>2.1.214</version> <!-- Add appropriate version -->
            <scope>runtime</scope>
        </dependency>

        <!-- Spring Boot Actuator (Optional, for monitoring and management) -->
        <dependency>
            <groupId>org.springframework.boot</groupId>
            <artifactId>spring-boot-starter-actuator</artifactId>
            <version>${spring.boot.version}</version> <!-- Use version property -->
        </dependency>
    </dependencies>

    <build>
        <plugins>
            <plugin>
                <groupId>org.springframework.boot</groupId>
                <artifactId>spring-boot-maven-plugin</artifactId>
                <version>${spring.boot.version}</version> <!-- Added version property -->
            </plugin>
        </plugins>
    </build>
</project>
