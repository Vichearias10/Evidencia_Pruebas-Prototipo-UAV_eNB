# Prototipo-UAV_eNB
## Descripción General del prototipo:
<p style="text-align: justify;">
El sistema que se implementó consta de un UAV de tipo de despegue vertical con ala rotativa, específicamente un quadcopter. Será compuesto por un frame o estructura de fibra de carbono por su resistencia y peso, usando un controlador de vuelo que se adapte a las necesidades que se requiere, en este caso de hardware abierto, procesamiento y compatibilidad, además de requerir un transmisor y receptor de óptimas prestaciones para tener buen radio de operación.
  En el mismo se montará la estación móvil implementada en una raspberry Pi 4 que tendrá el núcleo de la red y junto a una Radio Definido por Software (SDR, por sus siglas en inglés) se creará el eNB que proveerá de cobertura móvil celular de 4ta Generación y los usuarios (UE) en tierra se podrán conectar a través de una SIM previamente programada para tener acceso a la red móvil.
</p>

### UAV implementado
La construcción final del UAV resultó en lo siguiente:
![UAV](https://github.com/Vichearias10/Evidencia_Pruebas-Prototipo-UAV_eNB/blob/main/UAV.png)


Para realizar las conexiones electrónicas se construyó el siguiente diagrama, el cual indica el correcto ensamble de todos los componentes. Para lograr esto, se ha acudido a documentación de cada uno de los componentes, así como también reviews en YouTube y asesorías con una persona especializada en el tema.

![Conexiones UAV](https://github.com/Vichearias10/Evidencia_Pruebas-Prototipo-UAV_eNB/blob/main/Diagrama.png)

### Prototipo Completo
Finalmente se indica el prototipo completo, es decir, el UAV y el nodo LTE, formado por una Rasberry Pi 4, SDR Blade RF y un power bank para su alimentación energética.

![Prototipo Completo](https://github.com/Vichearias10/Evidencia_Pruebas-Prototipo-UAV_eNB/blob/main/Prototipo_Completo.png)

## Evidencias de evaluación del Prototipo
Apartado para presentar las evidencias de las pruebas realziadas al prototipo de comunicación móvil de emergencia.

### Evaluación de UAV
En este apartado se presenta los links de los videos en youtube sobre la implementación del UAV, el funcionamiento de los modos de vuelo y algunas de las pruebas realizadas al prototipo completo, que inlcuye el UAV con en nodo LTE a bordo, donde se mide la cobertura, la potencia de Rx y autonomía del mismo.

### Videos de Evidencia
Link del Video acerca de los modos de vuelo:
https://www.youtube.com/watch?v=q7ofOJa2B-U

### Evaluación de Prototipo UAV_eNB
Link del Video acerca de la evalución del nodo LTE y del prototipo completo:
https://youtu.be/LKLdcyjWP2Y

