# PowerBuddy-ASCOM-Driver
<b>This is a win32 driver for the Arduino based PowerBuddy relay controller</b>

This ASCOM switch driver is designed to work with the PowerBuddy by SimonTelescopium.<p>

<b>The Power Buddy by SimonTelescopium has three components</b>
<ol>
<li><b>PowerBuddy Arduino Sketch</b><p>
This is the sketch for the Arduino based relay controller, containing the sketch and instructions for how to build the PowerBuddy and configure the sketch for your usecase</li>
<li><b>PowerBuddy ASCOM Switch Driver</b><p>
This is the code in this repository, it creates and installs an ASCOM compliant driver to be used in conjunction with the Arduino PowerBuddy Sketch</li>
<li><B>PowerBuddy ASCOM Client</B><P>
This is client software to control the PowerBuddy, this software is optional, but I strongly suggest you use it to at least test all the components before using PowerBuddy with other ASCOM switch clients</li>
</ol>

<b>Features and limitations</b><p>

<ul>
<li>Test connection feature </li>
<li>communication log to help you debug issues </li>
<li>Edit names for each switch/relay/sensor </li>
<li>Set default power on state for each switch/relay </li>
</ul>

<b>Clients Tested</b>
<ul>
<li>NINA 1.10 HF1 (32bit version) (NightTime Imaging 'N' Astronomy) </li>
<li>PowerBuddy Client 1.0 By SimonTelescopium </li>
</ul>
