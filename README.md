# maven-repository
Repositorio Maven personal para librerías, jars, ...

## Usar el repositorio
En el pom.xml del proyecto se debe añadir, dentro de `/project/repositories/`:
```
<repository>
    <id>lib</id>
    <url>https://github.com/daoc/maven-repository/raw/master/</url>
</repository>
```
## Añadir nuevos programas al repositorio

Abrir un terminal en el directorio raíz del proyecto y ejecutar: `mvn install`

Al terminar, el programa se instala en el repositorio maven local: `<user-dir>/.m2/repository/`

Si `<groupId>A.B</groupId>` y `<artifactId>C</artifactId>` se debe copiar desde el directorio `A` incluido, 
directamente en la raíz del repositorio, `maven-repository`

Se puede arrastrarlos directamente en la interfaz web si se hace: Add file -> Upload files

O, más clásico, clonar el repositorio en la máquina local y hacer el típico `git add .` -> `git commit -m "..."` -> `git push`

## Listado
### SimUTE
```
<dependency>
  <groupId>griinf.daoc</groupId>
  <artifactId>SimUTE</artifactId>
  <version>3.0-SNAPSHOT</version>
</dependency>
```
### jpct
```
<dependency>
  <!-- Original en: http://www.jpct.net/ -->
  <groupId>threeDengine</groupId>
  <artifactId>jpct</artifactId>
  <version>1.15.3</version>
</dependency>
```
### j3dcore
```
<dependency>
  <!-- Original en: ... -->
  <groupId>jogamp.j3d</groupId>
  <artifactId>j3dcore</artifactId>
  <version>1.6</version>
</dependency>
```
### j3dutils
```
<dependency>
  <!-- Original en: ... -->
  <groupId>jogamp.j3d</groupId>
  <artifactId>j3dutils</artifactId>
  <version>1.6</version>
</dependency>
```
### vecmath
```
<dependency>
  <!-- Original en: ... -->
  <groupId>jogamp.j3d</groupId>
  <artifactId>vecmath</artifactId>
  <version>1.6</version>
</dependency>
```
### jogamp-fat
```
<dependency>
  <!-- Original en: ... -->
  <groupId>jogamp</groupId>
  <artifactId>jogamp-fat</artifactId>
  <version>2.3.2</version>
</dependency>
```
### simbad
```
<dependency>
  <!-- Original en: ... -->
  <groupId>simbad</groupId>
  <artifactId>simbad</artifactId>
  <version>1.4</version>
</dependency>
```
