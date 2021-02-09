# Creando un Logro
Al grano...
1. Crea una carpeta en **data** llamada _advancements_

2. En el editor crea un archivo asi:
```
<nombre del archivo>.json <---- Importante poner.json
```
**Es importante usar .json ya que no serviria a la hora de hacerle tests** 

En el editor, debeis guiaros de esta planilla (otra vez, lo se)

```
{
  "parent": "minecraft:"
  "display": {
    "title": {
      "text": "A datapack example"
    },
    "description": {
      "text": "A datapack example"
    },
    "icon": {
      "item": "minecraft:grass"
    },
    "frame": "goal",
    "show_toast": true,
    "announce_to_chat": true,
    "hidden": false
    {
  "criteria": {
    "example": {
      "trigger": "minecraft:impossible"
      }
    }
  }
}

```

[Mas informacion de los logros aqui](https://github.com/carlop3333/datapack.creator/blob/main/help/2./readme_more_es.md)
