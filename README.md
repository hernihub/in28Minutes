# in28Minutes
Repository for teacher Ranga to review, because Swagger is not working at all.

Ranga, hi.
I have springfox 2.6.1, SpringBoot 2.0.4.RELEASE, SwaggerConfig with 

@Bean
public Docket apiDocket() {
  return new Docket(DocumentationType.SWAGGER_2);
}

instead of just naming the method api, because I already tried that. I found this project, 
https://www.vojtechruzicka.com/documenting-spring-boot-rest-api-swagger-springfox/ to work but when I add controllers of in28Minutes
project, swagger-ui says it cannot infer base url.

Help me, please.
