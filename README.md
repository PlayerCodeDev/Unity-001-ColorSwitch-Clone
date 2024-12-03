# Color Switch (Clon)

![Static Badge](https://img.shields.io/badge/Engine-Unity-blue?style=flat-square)
![Static Badge](https://img.shields.io/badge/Language-C%23-blue?style=flat-square)
![Static Badge](https://img.shields.io/badge/Practice-gray?style=flat-square)

Proyecto que contiene la mecánica básica del videojuego Color Switch desponible para móviles y pc, donde ayudas a un circulo que cambia de color a pasar por diferentes obstaculos haciendo coincidir el color del circulo con el color de los obstaculos. En el caso de que el color no coincida, el circulo se destruye y el jugador pierde la partida.

<div align="center">
    <img src="./img/ColorSwitch-Logo.png" alt="Logo de Color Switch Original" width="150" height="150"/>
    <p>Logo del videojuego Color Switch Original</p>
</div>

Para este desarrollo se utiliza el motor de videojuegos **Unity** (versión 6000.0.28f1 LTS) y el lenguaje predefinido en dicho motor **C#**.

## Arte y Apariencia
Si bien el juego está copiando la mecánica principal del videojuego original, se ha querido utilizar colores diferentes. En este caso parecido a los colores primarios:

![#2C2D2C](https://placehold.co/100x35/2C2D2C/E6E8E6.webp?text=2C2D2C)
![#3772FF](https://placehold.co/100x35/3772FF/2C2D2C.webp?text=3772FF)
![#DF2935](https://placehold.co/100x35/DF2935/E6E8E6.webp?text=DF2935)
![#FDCA40](https://placehold.co/100x35/FDCA40/2C2D2C.webp?text=FDCA40)
![#10C668](https://placehold.co/100x35/10C668/2C2D2C.webp?text=10C668)
![#E6E8E6](https://placehold.co/100x35/E6E8E6/2C2D2C.webp?text=E6E8E6)

### Sprites
A continuación se presentan los sprites utilizados para crear los obstaculos que el jugador tiene que sobrepasar junto con un power-up o, en este caso, un sprite que hace de switch y obliga a cambiar de color alatoreamente al personaje.

#### Sprite Power-Up/Switch
Este es un sprite que le da la habilidad al jugador de cambiar, de forma aleatoria, su color al tocarlo. Lo que obliga al jugador a moverse atravez de los obstaculos de su mismo color para seguir avanzando.

<div align="center">
    <img src="./img/Color-Switch.png" alt="Sprite Power-Up/Switch" width="150" height="150"/>
    <p>Sprite Power-Up/Switch</p>
</div>


#### Sprite Obstaculos
Hay dos sprites que se utilizan para crear los obstaculos principales que el jugador debe transpasar. El primero es un circulo dividido en cuatro partes, cada parte tiene un color por donde el jugador, depenediendo de su propio color, puede transpasar o no. El segundo es un sprite que contiene una forma básica con la que se puede crear diferentes obstaculos como una cruz, barreras que se mueven horizontalmente, etc.

<div style="display:table-cell; vertical-align:middle; text-align:center">
    <img src="./img/Obstacle-Circle.png" alt="Obstaculo en forma de circulo" width="150" height="150"/>
    <p>Obstaculo circular de colores</p>
<!-- </div>
<div align="center"> -->
    <img src="./img/Obstacle-Cross.png" alt="Barras de obstaculos" width="150" height="150"/>
    <p>Barra de colores</p>
</div>

> [!NOTE]
> Este proyecto está desarrollado con el objetivo de aprender y/o repasar conceptos básicos del motor gráfico Unity.