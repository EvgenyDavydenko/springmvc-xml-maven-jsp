## Создание простого приложения на Java Spring MVC

1.  Создать веб проект из шаблона Maven: [mvn archetype:generate](https://maven.apache.org/archetypes/maven-archetype-webapp/)

2.  В pom.xml добавить зависимость [Spring Web MVC](https://mvnrepository.com/artifact/org.springframework/spring-webmvc/6.0.11) и [Spring Web](https://mvnrepository.com/artifact/org.springframework/spring-web/6.0.11)

3.  Сконфигурировать Deployment Descriptor `/WEB-INF/web.xml` и Application Context `/WEB-INF/spring-servlet.xml`

4.  Собрать приложение с помощью: mvn clean package

5.  Запустить Tomcat: tomcat/bin/startup.sh

6.  Копируем *.war файл в директорию tomcat/webapps

[Tutorial](https://www.digitalocean.com/community/tutorials/spring-mvc-example)