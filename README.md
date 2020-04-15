# SDK reconoSER ID Android

Este SDK de [reconoSER ID](https://reconoserid.com/), proporciona pantallas y métodos para aplicaciones Android que permiten capturar y analizar documentos de identidad y rostros en vivo con el fin de verificar en base a la información suminsitrada la identidad digital de sus usuarios.

Este SDK se integra al API administrador de reconoSER ID, permitiendo visualizar las interacciones y acciones de sus usuarios mediante el **authToken** y el **GUIDConvenio** suministrados por el equipo comercial.


## **Requerimientos** ##

* minSdkVersion 22
* Soporte para Java version 8

El SDK Solicita los permisos del telefono para:

* Internet
* Cámara
* Teléfono

Para esto, debe inicializar el SDK en *Application*
```
#!android

LibraryReconoSer.init(this, getApplicationContext(), "Identificador único de convenio", "Datos adicionales");
```

[Ver Wiki](https://github.com/ReconoSERID/SDK-ReconoSerId-Android/wiki)


