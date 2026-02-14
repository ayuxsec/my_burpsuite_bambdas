1. search response for a string

```java
return requestResponse.requestBody().contains("x-api-key");
```

2. filter status code

```java
return requestResponse.response().statusCode() == 200;
```

3. filter header

```java
return requestResponse.response().hasHeader("Next-Action");
```
