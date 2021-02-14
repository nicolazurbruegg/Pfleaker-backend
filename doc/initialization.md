<h1>Initialization Guide</h1>
<p>
Hier wird beschrieben, wie man das PFleaker Backend bei sich lokal starten kann.
</p>
<h2>Installations</h2> 

<h4>PGAdmin</h4>
<p>
Installiere PGAdmin 4 https://www.pgadmin.org/download/pgadmin-4-windows/
</p>

<h4>Java</h4>
<p>
Sofern nicht bereits vorhanden, installiere Java.
</p>

<h2>Setup</h2>
<h4>Datenbank</h4>
<p>
Öffne PGAdmin und erstelle einen neuen Server (name egal). Anschliessend muss
auf dem Server eine Datenbank mit dem namen postgres erstellt werden. Es ist darauf zu achten, dass
als Password "password" gesetzt wird.
</p>
<h4>Backend</h4>
<p>
Öffne das Projekt in IntelliJ und führe ein npm install aus.
Möglicherweise muss noch ein maven install ausgeführt werden (IntelliJ rechte Seite, dann Lifecycle). 
</p>
