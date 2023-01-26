# Gradle hacer multiproyecto en Java

Queremos crear un fat-jar con la librerías y todo dentro del mismo Jar.
Usamos en versión antigua de Java JDK1.6 y queremos poder separa lógica
en varios subproyectos separados para simplicarla y que sea más mantenible. 

# Requisitos
Esta desarrollada en VSCode con la extenxion de `Extension Pack for Java`
Gradle version 5.6 y Java 1.6

# Iniciar programa
```
C:\Users\Ruben\Gradle-multiproyecto-java>gradle wrapper
BUILD SUCCESSFUL in 2s
1 actionable task: 1 up-to-date

C:\Users\Ruben\Gradle-multiproyecto-java>gradlew -v

------------------------------------------------------------
Gradle 5.6
------------------------------------------------------------

Build time:   2019-08-14 21:05:25 UTC
Revision:     f0b9d60906c7b8c42cd6c61a39ae7b74767bb012

Kotlin:       1.3.41
Groovy:       2.5.4
Ant:          Apache Ant(TM) version 1.9.14 compiled on March 12 2019
JVM:          1.8.0_202 (Oracle Corporation 25.202-b08)
OS:           Windows 10 10.0 amd64

C:\Users\Ruben\Gradle-multiproyecto-java>gradlew -q run
Hello world.
Raul
```

