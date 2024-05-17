# Robot suiveur de ligne 

| | |
|-|-|
|`Author` | Josue Kabongo

## Description 
Le projet consiste à concevoir et à construire un robot suiveur de ligne autonome à l'aide d'une plateforme Arduino. Le robot sera équipé de capteurs de ligne qui lui permettront de détecter et de suivre des trajectoires spécifiques tracées au sol. À l'aide de moteurs et de circuits de contrôle, le robot ajustera sa trajectoire en temps réel pour rester centré sur la ligne, évitant ainsi les obstacles éventuels.

## Motivation
J'ai choisi ce projet car c'est une excellente introduction dans le monde de la robotique. Cela me permettra d'explorer des concepts de base tout en développant des compétences pratiques en électronique et en programmation.

## Architecture
Le projet utilise un Arduino UNO R3 comme cerveau central pour contrôler le suiveur de ligne. Les capteurs infrarouges sont utilisés pour détecter la ligne tracée sur le sol, tandis que les moteurs permettent au suiveur de ligne de se déplacer le long de cette ligne.

Lorsque le suiveur de ligne est mis sous tension, l'Arduino UNO R3 initialise les différents composants, notamment les capteurs infrarouges et les moteurs. Les capteurs infrarouges effectuent des lectures régulières pour détecter la position de la ligne par rapport au suiveur de ligne.

Les données des capteurs sont ensuite analysées par l'Arduino UNO R3 pour déterminer la direction dans laquelle le suiveur de ligne doit se déplacer pour rester sur la ligne. En fonction de ces données, des signaux sont envoyés aux moteurs pour ajuster la vitesse et la direction du suiveur de ligne afin qu'il suive la ligne tracée sur le sol.

Ainsi, le suiveur de ligne se déplace de manière autonome le long de la piste, ajustant continuellement sa trajectoire en fonction des informations fournies par les capteurs. Cette architecture permet au suiveur de ligne de suivre la ligne tracée sur le sol de manière autonome, en utilisant les données des capteurs infrarouges pour ajuster sa trajectoire et en contrôlant les moteurs pour son déplacement.


### Block diagram

<!-- Make sure the path to the picture is correct -->
![Diagram](Robot-ligne.png)

### Schematic

![Schematic](Schema-robot-1.png)

### Components


<!-- This is just an example, fill in with your actual components -->

| Device | Usage | Price |
|--------|--------|-------|
| Activ Buzzer | Buzzer | [1.5 RON](https://www.optimusdigital.ro/ro/audio-buzzere/635-buzzer-activ-de-3-v.html?search_query=buzzer&results=61) |
| Push Button | Button | [1 RON](https://www.optimusdigital.ro/ro/butoane-i-comutatoare/1119-buton-6x6x6.html?search_query=buton&results=222) |
| Jumper Wires | Connecting components | [7 RON](https://www.optimusdigital.ro/ro/fire-fire-mufate/884-set-fire-tata-tata-40p-10-cm.html?search_query=set+fire&results=110) |
| Breadboard | Project board | [10 RON](https://www.optimusdigital.ro/ro/prototipare-breadboard-uri/8-breadboard-830-points.html?search_query=breadboard&results=145) |

### Libraries

<!-- This is just an example, fill in the table with your actual components -->

| Library | Description | Usage |
|---------|-------------|-------|
| [lib-name1](link-to-lib) | official description of the lib | Used for accesing the peripherals of the microcontroller  |
| [lib-name2](link-to-lib) | official description of the lib | Used for accesing the peripherals of the microcontroller  |

## Log

<!-- write every week your progress here -->

### Week 6 - 12 May

### Week 7 - 19 May

### Week 20 - 26 May


## Reference links

<!-- Fill in with appropriate links and link titles -->

[Tutorial 1](https://www.youtube.com/watch?v=wdgULBpRoXk&t=1s&ab_channel=BenEater)

[Article 1](https://www.explainthatstuff.com/induction-motors.html)

[Link title](https://projecthub.arduino.cc/)