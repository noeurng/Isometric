# Isometric
Isometric drawing library for Android

### Drawing a simple cube

```java
isometricView.add(new Prism(new Point(0, 0, 0)), new Color(33, 150, 243));
```

![Image](https://raw.githubusercontent.com/fabianterhorst/isometric/master/asset/sample_1.png)

### Drawing multiple Shapes

```java
isometricView.add(new Prism(new Point(0, 0, 0)), new Color(33, 150, 243));
isometricView.add(new Prism(new Point(-1, 1, 0), 1, 2, 1), new Color(33, 150, 243));
isometricView.add(new Prism(new Point(1, -1, 0), 2, 1, 1), new Color(33, 150, 243));
```

![Image](https://raw.githubusercontent.com/fabianterhorst/isometric/master/asset/sample_2.png)

# Include in your project
## Using Maven
#### build.gradle file (currently required until its been published at jcenter)
```groovy
repositories {
    maven {
        url  "http://dl.bintray.com/fabianterhorst/maven" 
    }
}
...
compile 'io.fabianterhorst:Isometric:0.0.1'
```