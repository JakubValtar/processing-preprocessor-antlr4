An experimental Processing preprocessor based on Antlr4
==============================


### Building / Running

```
# process grammar
# assumes alias:
# alias antlr4='java -jar /usr/local/lib/antlr/antlr-4.2.2-complete.jar'
$ antlr4 Processing.g4

# compile it
$ javac *.java

# test a .pde file
$ java PdeToJava "/path/to/pde-sketch/sketch.pde" JavaClassName
```
