# Endit – Minecraft Java 26.3 / Fabric (GitHub Build)

Dieses Projekt enthält die vorbereiteten Quelldateien und den GitHub-Actions-Workflow für einen Build der Endit-Mod für Minecraft 26.3.

## GitHub Build

1. Alle Inhalte dieses Ordners in das Hauptverzeichnis deines GitHub-Repositories hochladen. Wichtig: `.github/workflows/build.yml` muss enthalten sein.
2. Änderungen committen und den Tab **Actions** öffnen.
3. Nach einem erfolgreichen Lauf das Artefakt **endit-fabric-26.3** herunterladen. Darin liegt die gebaute JAR.

## Befehl

`/setendspawn <x y z>`

Der Befehl wird nur für Game-Master-Berechtigungen (Operator-Rechte) freigeschaltet.

## Hinweis

Der vorher gemeldete Compilerfehler wurde in `src/main/java/net/yeoxuhang/endit/command/EndSpawnCommand.java` korrigiert. Der Build und das Verhalten im Spiel müssen in GitHub Actions bzw. auf einem Testserver überprüft werden.
