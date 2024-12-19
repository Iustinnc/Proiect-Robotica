<h1 align="center"> Line Follower</h1>

<h2>Componente: </h2>

<ul>
  <li>1 Micro-Controller Arduino Nano ATMega328P </li>
  <li>1 LED RGB</li>
  <li>1 Ecran LCD</li>
  <li>4 Butoane</li>
  <li>2 DC Motors</li>
  <li>2 Roți</li>
  <li>4 Senzori IR (infraroșu)</li>
  <li>1 Potentiometru </li>
  <li>Rezistențe (număr necunoscut momentan)</li>
  <li>Cabluri de conexiune</li>
</ul>

<h2>Mod de functionare: </h2>
<ul>
  <li>Ecranul LCD:</li>
  <p>acesta va fi direct conectat la modulul arduino, luminozitatea va fi controlata de potentiometru, iar pe el va avea un mic meniu de unde se vor putea afisa lap time-ul si distanta parcursa</p>
  <li>DC Motors:</li>
  <p>Acestea vor fi controlate de micro-controller, pentru a invarti rotile ce vor face masina sa se deplaseze</p>
  <li>Senzorii IR:</li>
  <p>Acestia vor cauta banda neagra, iar in functie de ce ne returneaza senzorii, controller-ul va modifica puterea din motoare astfel incat sa pozitioneze masina pe traiectoria liniei, pe care mai apoi o va urma</p>
</ul>

<h2>Limbajul de Programare: </h2>

<p>
        Voi folosi limbajul <strong>C</strong>, implementând codul pe microcontroler utilizând biblioteca 
        <code>avr/io.h</code> și compilatorul <code>avr-gcc</code>.
</p>

<h2>Mod de Funcționare</h2>
    <p>
        Robotul urmăritor de linie va detecta și urmări o linie neagră pe un fundal alb. Ca funcționalități adiționale, 
        acesta va afișa distanța parcursă și timpul necesar pentru un tur pe ecranul LCD.
    </p>

<h2>Laboratoare Folosite</h2>
    <ul>
        <li><strong>Lab 0</strong>: Aplicații introductive (Conectarea componentelor și butoanelor).</li>
        <li><strong>Lab 3</strong>: Timer și PWM (Pentru afișarea timpului unui tur și controlul servomotoarelor).</li>
        <li><strong>Lab 6</strong>: I2C (Pentru comunicarea cu ecranul LCD).</li>
    </ul>

<h2>Imagine Exemplu</h2>
    <p>Imagine reprezentativă a unui robot urmăritor de linie:</p>
    <img src="[https://upload.wikimedia.org/wikipedia/commons/8/88/Line_follower_robot_using_IR_sensors.jpg](https://images.app.goo.gl/2cFGxdj2H6zqAjp69)" alt="Robot urmăritor de linie" width="400">
    </p>

<p>Imagini cu partea hardware a robotului: </p>

![WhatsApp Image 2024-12-19 at 17 11 01 (3)](https://github.com/user-attachments/assets/c6c69e39-50cf-4a84-b9c2-253c1a4af34a)
![WhatsApp Image 2024-12-19 at 17 11 01 (2)](https://github.com/user-attachments/assets/bf634bbd-da57-4586-9316-59a1b15cc9cb)
![WhatsApp Image 2024-12-19 at 17 11 01 (1)](https://github.com/user-attachments/assets/21e6e4ad-86b8-4d81-856e-a6151ad372a4)
![WhatsApp Image 2024-12-19 at 17 11 01](https://github.com/user-attachments/assets/c40778d5-3d9a-4dce-9587-d46c81d65d82)


link ul de TinkerCad: https://www.tinkercad.com/things/8PvNvjf9zFc-funky-jaagub
