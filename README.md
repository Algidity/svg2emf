# svg2emf
Automatically exported from code.google.com/p/svg2emf

converts SVG(Scalable Vector Graphics) files to EMF(Enhanced Meta File) files using batik and FreeHEP VectorGraphics library
```java
public void testConvert() throws IOException {
    String svgUrl = "http://upload.wikimedia.org/wikipedia/en/7/7f/Mickey_Mouse.svg";
    File emfFile = new File("mickey.emf");
    SVG2EMF.convert(svgUrl, emfFile);
}
```
