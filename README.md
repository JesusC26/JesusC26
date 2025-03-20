
<h1 align="center">
  Hola👋, Mi nombre es Jesús Cervantes.
</h1>
<p align="Justify">
Soy ingeniero en mecatrónica, graduado por el Tecnológico de Monterrey, con una especialización en sistemas ciber-físicos. Entusiasta en el trabajo en equipo desarrollando proyectos mecatrónicos que contribuyan al desarrollo de la sociedad. Soy muy apasionado en el área de la programación (Matlab, C++, Python, java), el diseño asistido por computadora CAD y sobre todo de trabajar en el diseño electrónico, especialmente en el área de semiconductores. Creo fielmente que la industria de semiconductores ha sido la responsable del mayor desarrollo tecnológico que hemos experimentado y me gustaría contribuir en esta grandiosa área de conocimiento. Persona responsable, con gran interés en el autoaprendizaje, comprometida, creativa y en búsqueda constante de nuevos retos profesionales y académicos.
</p>
<h3>Conecta conmigo en LinkedIn</h3>
<a href="https://www.linkedin.com/in/jesuscervantes26/" target="_blank">
  <img src="./Images/icons/Linkedin_Icon.png" alt="LinkedIn" style="width: 50px;"/>
</a>
<h3>Languages and tools</h3>
<div style="display: flex;">
  <img src="./Images/icons/Python.png" alt="Python" style="width: 40px;">
  <img src="./Images/icons/C++.png" alt="C++" style="width: 40px;">
  <img src="./Images/icons/Linux.png" alt="Linux" style="width: 40px;">
  <img src="./Images/icons/Matlab.png" alt="Matlab" style="width: 40px;">
  <img src="./Images/icons/Eagle.jpg" alt="Eagle" style="width: 40px;">
  <img src="./Images/icons/Proteus.png" alt="Proteus" style="width: 40px;">
</div>

<h2>Proyectos</h2>
<h3>Red de sensores meteorológicos</h3>
<p align="Justify">
  La contaminación ambiental en la zona metropolitana de Guadalajara ha repercutido en el aumento de enfermedades respiratorias en la población. Para la mitigación de este tipo de problemas, es indispensable realizar un monitoreo constante de concentraciones de partículas con un diámetro igual o menor a 2.5 μm. En este proyecto se desarrolló el diseño e implementación de 3 distintos dispositivos que permitieran medir ciertas condiciones meteorológicas, con el objetivo de conocer la calidad del aire en cierta área de una metrópolis.
</p>
<div style="text-align: center;">
  <img src="./Images/First_project/Devices.png" alt="Devices"/>
</div>
<p>
  Descripción de cada uno de los dispositivos.
  <ul>
    <li>Dispositivo 1 (Home edition):</li>
      <p align="Justify">
      Esta versión se caracteriza como el dispositivo con menor complejidad de uso para el usuario. El modelo integro una PCB, la cual mantiene la integración dentro de la PCB el sensor BMP280 (Sensor que nos ayuda a medir presión atmosférica), además se implementó una memoria microSD (con el objetivo de guardar un back-up de los datos), se agregaron borneras para conectar los demás sensores utilizados (PMS5003 y DHT22, los cuales nos ayudan a medir partículas finas y temperatura respectivamente). Cabe mencionar que se utilizaron componentes SMD que nos ayudaron a reducir el tamaño de nuestra PCB. Los datos que recolecta el sistema son publicados directamente en Firebsase Realtime Database, que a su vez son transferidos a una interfaz gráfica para su visualización en cualquier parte del mundo.
      </p>
      <div style="display: flex;">
        <img src="./Images/First_project/Home_edition.jpg" alt="First device" style="width:200px; margin-right: 20px"/>
        <img src="./Images/First_project/PCB.png" alt="PCB first device" style="width:200px; margin-right: 20px"/>
      </div>
    <li>Dispositivo 2 (At Home +):</li>
      <p align="Justify">
      Nuestra segunda versión permite ser un dispositivo que pueda ser llevado a cualquier lugar, ya que este integra una batería recargable, y además una pantalla touch para que pueda ser más amigable con el usuario. Con respecto a la parte electrónica, se añadieron integrados distintos (DW01-A y 8205A, nos ayudan a realizar la carga de la batería) los cuáles se implementaron en una configuración de tipo TP4056, la cual nos permite cargar la batería de manera segura, de acuerdo con las distintas fases de carga para estas.
      </p>
      <div style="display: flex;">
        <img src="./Images/Second_project/Device.jpg" alt="Second device" style="width:200px; margin-right: 20px"/>
        <img src="./Images/Second_project/PCB2.png" alt="PCB second device" style="width:200px; margin-right: 20px"/>
      </div>
    <li>Dispositivo 3 (AW - 1):</li>
      <p align="Justify">
      Finalmente, nuestro modelo más complejo de todos, el cual contempla las características mencionadas anteriormente, solo con diferenciación en el área de carga de la batería, ya que este modelo cuenta con la conexión de un pequeño panel solar que le da autonomía de energía al dispositivo. Pero, su mayor característica en este modelo es que dicho dispositivo tiene la capacidad para interconectarse con otro dispositivo, mediante un protocolo de comunicación de radiofrecuencia llamado LoRa. Estos dispositivos se comunican entre sí, para formar una malla y poder transmitir información recolectada por cada nodo hacia un Gateway, el cual se encarga de subir toda la información (de toda la malla) a la nube y pueda ser visualizada por cualquier persona en un Dashboard. El objetivo principal de esta característica es poder mapear la calidad de aire en un área extensa, como por ejemplo en una ciudad.
      </p>
      <div style="display: flex;">
        <img src="./Images/Third_project/PCB.png" alt="Second device" style="width:280px; margin-right: 20px"/>
      </div>
  </ul>
  <a href="https://drive.google.com/drive/folders/1eiuvkdpiHxJToPeLuIFRoA54uQjY4gR3?usp=sharing"> Para mayor información del proyecto haga click aquí</a>
</p>
<h3>Rover Autonomous Exploration & Mapping</h3>
<p align="Justify">
Los robots autónomos son de gran relevancia para la industria hoy en día, debido a que estas están en constante búsqueda de nuevas maneras de aumentar la eficiencia operacional, incrementar la velocidad, garantizar la precisión y optimizar la seguridad y un robot de este tipo puede ayudar a mejorar todos estos aspectos. </p>
<p> 
 El problema a resolver en este proyecto fue la implementación de un sistema de navegación autónoma y reconstrucción del entorno, el sistema integra una camara y una computadora, los cuales fueron incorporados en un robot de tipo diferencial, por medio de un soporte de accionamiento Pan-tilt, el cual permite mover la cámara utilizada (modelo Euclid de Intel) hacia casi cualquier dirección del robot y así poder mapear el entorno y evitar que nuestro robot pueda tener alguna colisión con algún objeto que le impida navegar hacia un punto deseado. 
</p>
<p>
El desarrollo del proyecto tuvo distintas etapas, las cuales fueron:
  <ul>
    <li>Estudio de del modelo cinematico del robot:</li>
    <p>
    El modelado cinemático de un robot es el estudio de movimiento, sin contemplar las fuerzas que lo generan. Para un robot diferencial, el principal propósito del modelo cinemático es representar la velocidad lineal y angular total del robot en función de las velocidades de las ruedas de accionamiento, tomando en cuenta la geometría del robot, tal como se muestra en la siguiente figura.
    </p>
    <div style="display: flex;">
        <img src="./Images/Rover_Autonomous/Robot_Geometry.png" alt="Robot Geometry" style="width:200px; margin-right: 20px"/>
    </div>    
    <li>Diseño CAD del robot:</li>
    <p>
    El modelo CAD del robot diferencial utilizado para este proyecto, se puede observar en la siguiente figura, el cual consta de dos llantas actuadas (se encuentran en la parte trasera del robot) y dos llantas omnidireccionales, la cuales permiten al robot moverse a cualquier dirección. Además, se integró un mecanismo de pan-tilt, que permite sujetar la cámara utilizada y moverla a cualquier dirección.
    </p>
    <div style="display: flex;">
        <img src="./Images/Rover_Autonomous/CAD_design.png" alt="CAD design" style="width:400px"/>
    </div>
    <li>Navegación usando SLAM y exploración:</li>
    <p>
    La etapa más importante para un robot autónomo sin duda es la navegación de un entorno desconocido. En este apartado utilizamos el paquete de Gmapping de ROS, que en conjunto con todos los parámetros que entregan nuestros sensores, tales como la cámara (utilizada como LiDAR), encoder dentro del robot (conocer odometria del robot), logramos desarrollar un robot autónomo. 
    </p>
    <div style="display: flex;">
      <img src="./Images/Rover_Autonomous/Navigation_core.png" alt="Navigation core" style="width:600px"/>
    </div>
    <li>Resultados</li>
    <div style="display: flex;">
      <img src="./Images/Rover_Autonomous/Results.png" alt="Results" style="width:600px"/>
    </div>
  </ul>
  <a href="https://drive.google.com/drive/folders/1_d6Y_us8aZrnQOZAlpY2hZB-vicpmhr2?usp=sharing"> Para mayor información del proyecto haga click aquí</a>
</p>

<!--
**JesusC26/JesusC26** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
