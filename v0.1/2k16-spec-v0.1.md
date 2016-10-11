Programmaufbau
========
ZWEITER ENTWURF &mdash; ELFTER OKTOBER ZWEITAUSENDSECHZEN  
*Dieses Dokument dient zur Festlegung der Grundsätzlichen Struktur von 2k16. Bitte beachtet: Da das nur ein Entwurf ist, können sich große Bestandteile dieser "Sprache" noch gurndlegend abändern. Wenn ihr so verrückt seid, 2k16 zu nutzen, seid ihr selbst schuld. Wenn was nicht funktioniert, macht mich nicht dafür verantwortlich!*

---

```
was ist das für 1 code?
    [code]
1 nicer!
```

## Kommentare
> Kommentare werden durch ein Zipper-Mouth Face (Unicode U+1F910) eingeleitet. Ein einzeiliger Kommentar wird mit einem 🤐 eingeleitet.
```
[code] 🤐 Das ist 1 nicer kommentar!
```

> Mehrzeilige Kommentare werden mit 🤐🤐 eingeleitet und mit 🤐 beendet.
```
🤐🤐 Das ist 1 alte Funktion, die wo nicht benutzt
wierd. Deshalb stet hier 1 langes Kommentar!
[kommentierter code]
🤐
```

## Variablen
> Variablen **müssen** aus Emojis bestehen, ansonsten ist das Programm ungültig.

#### Typen
| Code   | Typ      |
| ------ | -------- |
| `word` | String   |
| `zal`  | Integer  |
| `isso` | Boolean  |

#### Zuweisung:
```
gönn dir [name] vong [type] her 
[name] bim [value]
```
Die Zuweisung ist auch einzeilig möglich:
```
gönn dir [name] vong [type] her bim [value]
```


#### Beispiel
Die Variable `1⃣` wird als Integer mit einem Wert von `15` definiert.
```
gönn dir 1⃣ vong zal her
1⃣ bim 15
```

## Kontrollstrukturen
```
bist du [bool] (nope)
    [code wenn bool == false]
bist du [bool] (yup)
    [code wenn bool == true]
real rap
```
Zeilen, bei denen [bool] zu true evaluieren muss, enden mit (yup). Umgekehrt mit (nope). Else gibts also nicht direkt. else-if ergibt sich durch mehrere "bist du ..."

## Schleifen
```
turnup [bool]
    [code]
nice nice
```

## Funktionen
#### Zuweisung
```
[name, args in runden klammern] so von funktion her
    [code]
dies das
```
#### Beispiel
```
was ist 🍔🍟(kek) für 1 scheiss ?? so von funktion her
    gönn dir 📝 vong word her "Ey, lass Mäcces!"
    bist du kek (nope)
        gieb 📝
    real rap
dies das

was ist 🍔🍟 für 1 scheiss ??
```
## stdlib:
`true: yup`  
`false: nope`  
`gieb [variablenname]` - Gibt Variablenname auf stdout aus  
`was ist [variablenname] für 1 typ ??` - Gibt Variablentyp als String zurück  
`mdma, heroin, kokain, alkohol ist auf jeden fall etwas sehr nices` - Bricht das Programm ab wie exit(0)