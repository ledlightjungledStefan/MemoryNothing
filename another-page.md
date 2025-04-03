---
layout: default
css:

- assets/css/main.css
  bugcss: <link rel="stylesheet" href="{{ css }}">

---

[NUR NET HUDLN:WEIL. . . -klein Adlerauge-](./NUR_NET_HUDLN.html)

![](assets/images/Flme.png)

```vbnet
Private Sub Button_HideLabel(ByVal sender As Object, ByVal e As EventArgs)
   myLabel.Visible = False
End Sub
```

#### Ereignishandler

Ein **Ereignishandler** ist die Methode oder Prozedur, die definiert, wie auf ein Ereignis reagiert wird. Wenn ein Ereignis ausgelöst wird, übernimmt der Handler die Aufgabe, die entsprechende Logik auszuführen. Man könnte ihn als die "Antwort" auf das Ereignis verstehen. Beispiel:

`Private Sub HandleButtonClick()
    MsgBox("Button wurde geklickt!")
End Sub`

Hier ist `HandleButtonClick` der Ereignishandler(warum nicht Name?).

##### Ereignis

Ein **Ereignis** ist eine Benachrichtigung, die signalisiert, dass etwas passiert ist. Es ist wie ein "Ruf", der angibt, dass eine bestimmte Aktion oder ein Zustand eingetreten ist. Ereignisse werden häufig von Objekten ausgelöst, z. B. ein Button-Klick, ein Timer-Ablauf oder eine Änderung des Werts einer Variable. Sie sind im Grunde "Auslöser", die darauf warten, dass sie verarbeitet werden. Beispiel:

`Public Event ButtonClicked()`

Hier wird ein Ereignis namens `ButtonClicked` definiert.

```vbnet
Private Sub AddVisibleChangedEventHandler()
   AddHandler myLabel.VisibleChanged, AddressOf Label_VisibleChanged
End Sub
```

[back](./)

In einem Sonnensystem ist ein blauer Planet. Auf dem Planeten fließt ein Fluss richtung Meer. Auf dem Fluss fährt ein Boot entgegen der Flussrichtung mit Aussenbordmotor.

- ein aussenbordmotor kann einen propeller antreiben:Meldung

- das signal einer Taste muss entprellt werden sonst kann die sendung nicht verstanden werden:Objekt

- das Boot ist schneller oder langsamer als der Fluss:Aktion

- die Luftfeuchtigkeit könnte ein Eigenschaftswert der Wassertiefe sein.
