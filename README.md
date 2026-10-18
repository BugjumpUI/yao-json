# yao.json

一个轻量级、无依赖、兼容 Java 7+ 的 JSON 库。

## 快速开始

### 解析 JSON

```java
JsonObject obj = Json.parseObject("{\"name\":\"test\",\"age\":18}");
String name = obj.getString("name");  // "test"
int age = obj.getInt("age");          // 18

JsonArray arr = Json.parseArray("[1, 2, 3]");
int first = arr.getInt(0);            // 1
```
