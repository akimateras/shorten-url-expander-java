# About

短縮URLを展開するJavaコードです.

# Citation

* http://kurusugawa.jp/2011/05/27/fast-universal-java-url-expander/

# Usage Sample

```java
public class Main {
    public static void main(String[] args) {
        ShortenUrlExpander expander = new ShortenUrlExpander();
        try {
            String result = expander.expand("http://bit.ly/test");
            System.out.println(result);
        } catch (IOException e) {
            System.err.println("Failed to expand URL.");
        }
    }
}
```
