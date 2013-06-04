jfinal-rythm-demo
=================

Update JFinal Offical Demo app with Rythm template engine. 

You need to modify the main method of DemoConfig.java from

```lang-java
public static void main(String[] args) {
  	JFinal.start("p:/jfinal-rythm-demo/WebRoot", 80, "/", 5);
}
```

to

```lang-java
public static void main(String[] args) {
    JFinal.start("path/to/your/WebRoot", 80, "/", 5);
}
```

For more about Rythm Template Engine, checkout 

* The project [website](http://rythmengine.org)
* The interactive [fiddle site](http://fiddle.rythmengine.org)
