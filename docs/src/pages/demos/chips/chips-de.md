---
title: Chip React Component
components: Chip
---
# Chips

<p class="description">Chips sind kompakte Elemente, die eine Eingabe, ein Attribut oder eine Aktion repräsentieren.</p>

[Chips](https://material.io/design/components/chips.html) erlauben es dem Nutzer, eine Information einzugeben, eine Auswahl zu treffen, Inhalte zu filtern oder Aktionen auszulösen.

Obwohl hier als eigenständige Komponente eingebunden, wird der wohl häufigste Anwendungsfall in einer Art von Input sein. Einiges des hier demonstrierten Verhaltens ist also nicht unbedingt im Kontext dargestellt.

## Chip

Beispiele von Chips, die ein Bild-Avatar, SVG-Icon-Avatar, "Buchstaben-" und (Text-) Avatar verwenden.

- Chips, auf denen das `onClick` Property gesetzt ist, ändern ihr Erscheinungsbild beim Fokusieren, Darüberfahren und Klicken.
- Chips, auf denen das `onDelete` Property definiert ist, zeigen ein Löschen-Icon, das beim Darüberfahren sein Erscheinungsbild ändert.

{{"demo": "pages/demos/chips/Chips.js"}}

### Umrandete Chips

Umrandete Chips bieten einen alternativen Stil.

{{"demo": "pages/demos/chips/OutlinedChips.js"}}

## Chip Array

Ein Beispiel vom Rendern mehrerer Chips aus einem Array von Werten. Das Löschen eines Chips entfernt ihn aus dem Array. Beachte, das dadurch, dass kein `onClick` Property gesetzt ist, der Chip zwar fokussiert, jedoch nicht geklickt oder berührt werden kann.

{{"demo": "pages/demos/chips/ChipsArray.js"}}

## Chip Spielwiese

{{"demo": "pages/demos/chips/ChipsPlayground.js", "hideHeader": true}}