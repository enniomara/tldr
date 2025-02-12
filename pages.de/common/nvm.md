# nvm

> Installiere, Deinstalliere oder wechsle zwischen Node.js Versionen.
> Unterstützt Versionsnummern wie "0.12" oder "v4.2", und Label wie "stable", "system", etc.
> Weitere Informationen: <https://github.com/creationix/nvm>.

- Installiere eine bestimmte Node.js Version:

`nvm install {{node_version}}`

- Verwende eine bestimmte Node.js Version in der aktuellen Shell:

`nvm use {{node_version}}`

- Setze die Standard Node.js Version:

`nvm alias default {{node_version}}`

- Zeige alle verfügbaren Node.js Versionen und hebe die Standard Version hervor:

`nvm list`

- Deinstalliere die angegebene Node.js Version:

`nvm uninstall {{node_version}}`

- Starte eine REPL mit einer bestimmten Node.js Version:

`nvm run {{node_version}} --version`

- Führe ein Skript mit einer bestimmten Node.js Version aus:

`nvm exec {{node_version}} node {{app.js}}`
