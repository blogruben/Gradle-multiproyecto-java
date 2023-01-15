
# Proyecto

Creamos un multiproyecto en gradle 5.6
definimos todos las funciones en el `build.gradle`
del proyecto principal. 

Los subproyectos no contienen
el build.gradle, ya que es opcional y nos centramos
en como usar invocar funciones en los subproyectos
definidos en el `build.gradle` principal.



# Requerimientos
En este ejemplo, basico no usamos wrapper, lo que necesitamos
tenemos instalado gradle 5.6

```
C:\Users\Ruben>gradle -v

------------------------------------------------------------
Gradle 5.6
------------------------------------------------------------

Build time:   2019-08-14 21:05:25 UTC
Revision:     xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx

Kotlin:       1.3.41
Groovy:       2.5.4
Ant:          Apache Ant(TM) version 1.9.14 compiled on March 12 2019
JVM:          1.8.0_202 (Oracle Corporation 25.202-b08)
OS:           Windows 10 10.0 amd64
```

# Documentacion

Este ejemplo esta basado en la [Documentacion oficial](https://docs.gradle.org/5.6/userguide/multi_project_builds.html#multi_project_builds)