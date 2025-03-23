# Invitame un cafe
Paypal: https://www.paypal.com/paypalme/CitalanKevin 
Nombre : Kevin Gomez

# Titulo del proyecto

Arcade Timer para HyperSpin y Rocket Launcher



## Requerimientos para el proyecto
* HyperSpin
* Rocket Launcher
* Windows 10
## Archivos necesarios
- https://mega.nz/folder/YLlWBQSS#9IA_q8j3A5v1t04qIQQ5iw

## Levantamiento del proyecto

Clone the project

```bash
  git clone https://github.com/UpdateSabio/TimerPublicado.git
```

## Links bibliograficos

 - [RocketLauncher Wiki Development](https://www.rlauncher.com/wiki/index.php/Development)


## Archivos de configuracion
#### En esta ubicación del equipo se coloca los archivos de configuración
C:\Users\\{nombreUsuarioPC}\AppData\Roaming

#### Configuración Rocket Launcher
En el archivo: "E:\HyperSpin\RocketLauncher\Lib\Classes\UserFunction\UserFunction.ahk"  
Reemplazaremos el archivo que esta en el link de archivos necesarios : UserFunction.ahk . Hacer respaldo de este archivo por seguridad




# Explicación de Codigo
### checarTiempo()
Esta función del archivo Global.ahk determina si hay tiempo con el archivo de configuración "time.json" que contine la bandera de si hay tiempo, al igual se cierra el timer si fuese un sistema tipo coin como en este caso el Mame
![App Screenshot](https://firebasestorage.googleapis.com/v0/b/portfoliowebsite-6adbe.appspot.com/o/Arcade%20Timer%20Proyect%2FCodigo%20ahk.png?alt=media&token=9f86135e-7093-4830-a8a2-bde5c21dd67f)

Mandamos a llamar la función antes de iniciar el emulador y despues de terminar el loading en la linea 13 y 23

![App Screenshot](https://firebasestorage.googleapis.com/v0/b/portfoliowebsite-6adbe.appspot.com/o/Arcade%20Timer%20Proyect%2FInicio%20sistema.png?alt=media&token=5afe6747-8199-4472-8041-b285636c5136)


### Descripcion del archivo de configuración "time.json"

![App Screenshot](https://firebasestorage.googleapis.com/v0/b/portfoliowebsite-6adbe.appspot.com/o/Arcade%20Timer%20Proyect%2FConfiguracion%20timer.png?alt=media&token=14518318-68a6-434f-972f-c870d3fbd419)



* isTheretime: Bandera para saber si hay tiempo, esta campo sirve para que el rocket launcher sepa si hay tiempo o no

* segundosPorCredito:La cantidad de segundos por cada credito que se deposita

* pathSound: La dirección del path donde estan todos los sonidos

* pathHyperSpin: La dirección del path donde esta el HyperSpin, ya que el HyperSpin no se abrira solo, si no que el timer hara ese trabajao cuando se ejecute

* nameProcesos: Los nombres de los procesos que cerrara el timer cada vez que llegue a 0, la mayoria de las veces es el nombre del exe del emulador sin la extensión


# Notas
* La letra designada que habilitara el tiempo es la letra i
* Se recomienda hacer un respaldo del codigo de Rocket Launcher, ya que el rocket launcher es el encargado de verificar si hay tiempo o no para iniciar el emulador o juego
# Contacto
* Correo: kevin.gypsydanger@gmail.com
* Whatsapp: 954-313-8520
* Usuario Discord: updatesabio

