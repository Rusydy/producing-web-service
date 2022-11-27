# list of notes

- [x] package javax.xml.bind.annotation does not exist
    to fix this, add the following to the pom.xml file:

    ```xml
    <dependency>
        <groupId>jakarta.xml.bind</groupId>
        <artifactId>jakarta.xml.bind-api</artifactId>
        <version>2.3.2</version>
    </dependency>
    ```
  
    due to this issue, don't forget to create a PR to [this repo](https://github.com/spring-guides/gs-producing-web-service#readme)

- [ ] No endpoint mapping found for `[SaajSoapMessage {http://api.com}getCountryRequest]`
