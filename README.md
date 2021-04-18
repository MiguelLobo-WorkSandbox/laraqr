## LaraQR - Pruebas de concepto


####Modulo QR
Se instalo dos paqutes que permite el manejo de codigos qr,  para ello se esta generando un numero rando desde 10000000 al 99999999 para la generacion del codigo.

- Generador: [simplesoftwareio/simple-qrcode](https://github.com/SimpleSoftwareIO/simple-qrcode "simplesoftwareio/simple-qrcode") (PHP).
- Lector: [schmich/instascan](https://github.com/schmich/instascan "schmich/instascan") (Js).

Para la prueba es necesario que el proyecto se ejecute en un url segura (https), para que asi se puede solicitar el permiso de uso de la camara.

Urls:
- / (*Genera el codigo QR*).
- /qr/scanner (*Lee el codigo QR*).

Pusar el tefl para la prueba es necesario que el navagedor tenga los permisos para acceder a la camara del dispositivo y a su vez para poder ejecutar el proyecto desde local se recomienda usar [ngrok.io](https://ngrok.com/ "ngrok.io").
