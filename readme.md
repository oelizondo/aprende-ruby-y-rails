#Aprende Ruby y Rails

##Contenidos
  * Instalación de Ruby
  * Version Manager
  * Interactive Shell
  * Gemas
  * Gemfile y Bundler
  * Aprendiendo un poco de Ruby (recursos)
  * Rails

##Instalando Ruby
  * OS X
  * Linux
  * Windows

  Para aquellos que ya cuentan con una máquina de derivado * NIX, no
  habrá mucho problema, porque Ruby ya viene en sus máquinas. Sin
  embargo, es importante tener un manejador de versiones de Ruby para
  poder manejar distintas gemas y librerías. Adicionalmente, la versión de
  Ruby que tienen por predeterminado estas máquinas es antigua.

####Cómo checar tu versión de Ruby

```console
ruby -v
```

###Instalando en OS X

Si el comando previo no dio resultado, o un error, entonces tenemos que
instalar Ruby, de otra manera, hay que actualizarlo. Para esto,
utilizaremos un manejador de versiones. Hay dos manejadores de versiones
populares, RVM y Rbenv. Para este tutorial vamos a usar Rbenv.

  1. Para OS X, la mejor manera de tener Rbenv installado es via
Homebrew.
  2. ```brew update```
  3. ```brew install rbenv```
  4. ```rbenv init``` (después de la instalación)
  5. ```rbenv install -l``` (Listado de todas las versiones de Ruby)
  6. ```rbenv install <versión de ruby>``` (2.2.3)

Para este tutorial, utilizaremos la versión más reciente de Ruby: 2.2.3.
Ya que tengamos Ruby y rbenv instalados, hay algunos commandos que podemos ver para saber si todo está en orden:

* ```rbenv``` (debería mostrar el menú de rbenv)
* ```ruby -v``` (ahora debería ser 2.2.3)

####No tengo Homebrew
Fácil, solo instlálalo: ```/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"```.
Homebrew es un manejador de paquetes para installar programas de manera más sencilla en tu sistema. Podríamos decir que es un estándar de la industria.

###Instalando en Linux
