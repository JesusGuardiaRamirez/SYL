![Captura de pantalla 2023-06-04 a las 16 43 23](https://github.com/JesusGuardiaRamirez/SYL/assets/125477881/27846656-acd9-4e87-88d9-4543149b361a)



### SELF PROTECTION
Introducción - SYL -
Debería de ser un derecho el poder estar protegidos. En este mundo de injusticias, aqui pongo alguno de los miles de ejmplos de los cuales hay una fuga de escape en que se pierder por el camino. Por ejemplo: Situaciones como: el niño o la niña que va a la escuela y tiene que sufrir abusos, insultos, amenazas y la escuela no hacen nada o la mayoria de las veces ni si quiera se enteran de la situación o hace oidos sordos, como la mujer que es maltrada en su casa a manos de su pareja, sin que nadie la pueda socorrer en el momento o pueda pedir ayuda a terceros. El abuelo o la abuela que lamentablemente vive en una residencia y recibe mal trato de las propias cuidadoras o como otros casos como por ejemplo que te puedan socorrer en un accidente en la carretera (alertar a alguien en el mismo momento). Que te pueda servir de ayuda en un conflicto fuera de lo normal y que se quede registrado.. etc.. etc..

Descripción y funcionalidad- SYL -
Para ello he creado este algoritmo, que podría servir de mucha ayuda para esos casos mencionados.

### Regsitro en la misma aplicacion..:


![Captura de pantalla 2023-06-08 a las 17 47 25](https://github.com/Ironhack-Data-Madrid-Abril-2023/7.4-lab_unsupervised_learning_evaluation/assets/125477881/504cbdfd-17b2-40d4-8b52-2784302c2267)





El ususario tendrá la opción de registrar hasta 6 personas de emergencia cuando la aplicación este realmente funcionando, (solamente enseño una por tema de memoria)

Una vez el usuario se ha registrado, la pantalla de la aplicación se pondrá totalmente en negro. Empezará a escuchar y solamente se pondrá a grabar cuando detecte la palabra clave que el mismo usuario puso a la hora de registrarse.

Una vez el usuario se encuentra en una situación fuera de lo común, al decir la palabra clave, el sistema empieza a grabar por 45 segundos, una vez ese tiempo ha transcurrido, se activa la cámara y graba por otros 30 segundos, dándole tiempo a guardar el audio y a transcribirlo, detectando palabras claves para medir el nivel de lo que está sucediendo, seguidamente se conectará por Whatsapp y será enviado a través de texto a las personas en selección, de lo cual ocurre lo mismo por correo electrónico .

En ese correo electrónico irá los datos del usuario junto a la dirección exacta de donde se encuentra en ese momento, la gravedad del asunto, y el relato que se ha grabado en el audio con el video adjunto.

Mientras que en el Whatsapp, irá solamente los datos del usuario junto a la dirección exacta, la gravedad del asunto y el relato de lo sucedido en ese tiempo.

Una vez todo el proceso ha finalizado, estos datos serán guardados en MongoDB, una base datos tal y como la siguiente imagen demuestra.


0
Objetivo - SYL -
La idea de este proyecto es hacer una aplicación que se pase dicha información de usuario a usuario en la misma aplicación sin tener que depender del Whatsapp ni del correo electrónico.

Esto solamente sería la primera versión como trial de SYL, para ver realmente como va luciendo y poder trabajar en futuras versiones.



http://192.168.0.12:8501


