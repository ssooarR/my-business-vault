#projekt 


## Ergebnisse

### 1. config Datei für Verbesserung der ssh-key Verwendung einrichten
Erstelle in deiner `~/.ssh/config`:

```sshconfig

Host meinserver
    HostName meinserver.de
    User user
    IdentityFile ~/.ssh/id_ed25519_meinserver

```
