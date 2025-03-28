# asesinato-en-SQL_City
Este repositorio contiene la solución de una investigación criminal utilizando consultas SQL sobre
diversas bases de datos. El objetivo es identificar añ asesino analizando informes del crimen, entrevistas
con testigos, registros de membresías y otros datos relevantes en una base de datos simulada de SQL City.

![mysterio-1](https://github.com/user-attachments/assets/131ee9a4-a75f-4241-869c-2a7b1789b272)

Investigación del Asesinato en SQL City
Informe del Crimen
El 15 de enero de 2018, ocurrió un asesinato en SQL City. El informe de la escena del crimen reveló que hubo dos testigos: uno que vivía en la última casa de Northwestern Dr. y otro llamado Annabel, que vivía en Franklin Ave.

![mysterio-2](https://github.com/user-attachments/assets/6d0dd72f-b5b4-4a41-8ec3-b803d8340371)


Identificación de Testigos
Primero, encontramos el person_id de Annabel. Mediante una consulta en la tabla "person", descubrimos que su ID es 16371.

![mysterio-3](https://github.com/user-attachments/assets/301aa9d8-acb5-49d8-9875-a8d71977ff2c)


Luego, buscamos al testigo que vivía en la última casa de Northwestern Dr., encontrando a Morty Schapiro, cuyo ID es 14887.

![mysterio-4](https://github.com/user-attachments/assets/e10b70cf-0215-453a-826e-311155531ad4)


Testimonios de los Testigos
Consultamos las entrevistas de ambos testigos. Annabel reveló que el asesino es un miembro del gimnasio que ingresó el 9 de enero de 2018.

![mysterio-5](https://github.com/user-attachments/assets/c57a4bdd-2b5a-456e-a738-4fb4a73b2a01)


Morty nos proporcionó más detalles: el asesino es hombre, socio "Gold", posee una pistola, y su número de socio parcial es "48Z". También mencionó que la matrícula del coche del asesino comienza con "H42W".

![mysterio-6](https://github.com/user-attachments/assets/86b0acc4-2753-4963-81ff-f894e4b0253d)


Investigación en el Gimnasio
Buscamos en la tabla "get_fit_now_check_in" para ver quiénes ingresaron al gimnasio el 9 de enero de 2018. Encontramos dos miembros cuyos IDs comienzan con "48Z": Joe Germuska y Jeremy Bowers.

![mysterio-7](https://github.com/user-attachments/assets/29a50e5a-b641-45a6-9047-c61917f94cfa)


Placas de Matrícula
Ambos sospechosos son socios "Gold", por lo que consultamos sus matrículas. Solo Jeremy Bowers tenía un coche registrado, y su matrícula coincidía con la descripción dada por Morty: "H42W".

![mysterio-8](https://github.com/user-attachments/assets/f70178f6-6e76-47cd-b620-c73248f5b37d)


¡Jeremy Bowers es el asesino!

![mysterio-9](https://github.com/user-attachments/assets/a2eafcca-5d8b-40ff-a956-8e02c9056ac5)


El Cerebro detrás del Crimen
Jeremy confesó que actuaba bajo las órdenes de una mujer pelirroja que mide entre 1,65 y 1,70 m y que conduce un Tesla Model S. También mencionó que ella asistió al Concierto Sinfónico SQL tres veces en diciembre de 2017.

![mysterio-10](https://github.com/user-attachments/assets/b84594c4-e182-49ac-98d8-20e8bb00f6f5)


Consultamos los eventos y descubrimos que la mujer en cuestión es Miranda Priestly.

![mysterio-11](https://github.com/user-attachments/assets/c6836dfb-9efc-4555-bf4a-b9ab17b4417f)


¡Felicidades! Miranda Priestly es la mente maestra detrás de todo el crimen. Caso resuelto.

![mysterio-solución](https://github.com/user-attachments/assets/4361ab3e-d469-44f9-9366-ebc2846c33b4)
