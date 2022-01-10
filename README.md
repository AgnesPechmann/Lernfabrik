<h1 style="color:#8b0000">Virtual Learning Factory</h1>

<h2>1 Introduction</h2>

<p>The Learning Factory 4.0 aims to represent an Industry 4.0 conform production system to teach how a production management system can digitally be connected with a production; producing different products. Moreover, it is presented how different production data (e.g., status information, processing time, energy demand) can be used for simulation-based production planning and controlling processes according to sustainability aspects.</p>
<p>In general, the Learning Factory 4.0 demonstrates a shop floor production consisting of a high-bay warehouse; machining centers with conveyor belts; and robots with pneumatic and electric grippers and optical quality control (see video below). The orders are produced with a lot size of one. Production data are offered to digital services with the help of measuring devices and digital interfaces.</p>
<p>The transparency of the system (from process level to management level) is made possible by communication between the individual elements of the system (e.g., the Fischertechnik modules and the various information-bearing levels). Each Fischertechnik module is equipped with a TXT controller, which does not support an interface for direct communication with a database (an Oracle(c) DB of the ERP system is used as the database.) All TXT controllers in the Fischertechnik production system are therefore extended by one Raspberry Pi (mini-computer) each. This allows communication between, for example, the individual processing centers and the ERP system. By extending each module with a Rapsberry Pi, the following, among other things, can be achieved:</p>
<ul class="list-normal">
<li>a decentralized control and</li>
<li>a modular structure with a plug &amp; play function of the production system.</li>
</ul>
<p>The individual machining centers are integrated into a service architecture, which is gradually extended within the project by sensors and measuring devices for data acquisition and services, such as simulations.</p>
