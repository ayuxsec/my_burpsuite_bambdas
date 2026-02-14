1. search response for a string

```java
return requestResponse.requestBody().contains("2dec8bdb-7db9-81d4-af09-0070b62b84fc");
```

2. filter status code

```java
return requestResponse.response().statusCode() == 200;
```

3. filter header

```java
return requestResponse.response().hasHeader("Next-Action");
```
