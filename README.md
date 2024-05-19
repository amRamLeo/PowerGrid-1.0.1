Este repositorio es un Walkthrough sobre como reesolver la maquina virtual PowerGrid 1.0.1. Esta VM se encuentra disponible en la página Vulnhub: https://www.vulnhub.com/entry/powergrid-101,485/
Esta máquina está diseñada para poner a prueba tus habilidades en seguridad informática y hacking ético.


Acerca de: 

Name: PowerGrid: 1.0.1

Date release: 28 May 2020

Author: Thomas Williams

Series: PowerGrid

Web page: https://security.caerdydd.wales/powergrid-ctf/




Descripción:.
Los ciberdelincuentes han tomado el control de la red eléctrica en toda Europa. Como miembro del servicio de seguridad, se te encarga penetrar en su servidor, obtener acceso de root y evitar que lancen su malware antes de que sea demasiado tarde.

Sabemos por inteligencia previa que este grupo a veces utiliza contraseñas débiles. Te recomendamos que examines este vector de ataque primero; asegúrate de configurar tus herramientas correctamente. No tenemos tiempo que perder.

Desafortunadamente, los delincuentes han iniciado un reloj de 3 horas. ¿Podrás llegar a su servidor a tiempo antes de que desplieguen su malware y destruyan las pruebas en su servidor?

Este ejercicio está diseñado para completarse de una sola vez. Apagar la máquina virtual no pausará el temporizador. Después de que el temporizador haya terminado, la máquina CTF se apagará y no podrás iniciarla. Por favor, haz una copia de seguridad local de la CTF antes de comenzar, en caso de que desees intentarlo por segunda vez.


Si quieres tener éxito, te recomiendo leer estos puntos:

- Haz una copia de seguridad local antes de comenzar en caso de que se te acabe el tiempo.
- Necesitarás un entendimiento básico de la herramienta GPG y cómo funciona.
- Configura tus herramientas para que funcionen al nivel máximo/más difícil posible. Asegúrate de estar bucleando alrededor de lo correcto, si entiendes a lo que me refiero.
- Obtener el shell inicial es posiblemente la parte más larga.
- Hay un total de cuatro banderas. Cada archivo de bandera te guiará hacia la siguiente área.
- Esta máquina virtual ha sido probada solo en VirtualBox. No puedo garantizar que funcione en VMWare, pero debería estar bien.
- SHA-256: 8bc79937082748c21de14c5da3772f7fc750d52b68cf27816922186f6e68d6b7

Está clasificado como 'Difícil' (según la matriz aquí: https://security.caerdydd.wales/ctf-difficulty-levels/)

Cambios v1.0.1 - 2020-05-28 v1 - 2020-05-20
