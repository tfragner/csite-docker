# csite-docker

Docker installieren

Repository klonen

<code>
  git clone https://github.com/tfragner/csite-docker.git
</code>

Beim Starten folgenden Befehl im Verzeichnis ausführen:


<code>
  docker-compose -f csite-docker.yml up
</code>

bei Neustart vorher die Container löschen, sonst werden die Datenbankeinträge dupliziert:


<code>
  docker-compose -f csite-docker.yml down
</code>
