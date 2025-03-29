---
layout: default
---
```vb
Private Sub Button_HideLabel(ByVal sender As Object, ByVal e As EventArgs)
   myLabel.Visible = False
End Sub


Private Sub AddVisibleChangedEventHandler()
   AddHandler myLabel.VisibleChanged, AddressOf Label_VisibleChanged
End Sub


Private Sub Label_VisibleChanged(ByVal sender As Object, ByVal e As EventArgs)
   MessageBox.Show("Visible change event raised!!!")
End Sub
```

# NUR NET HUDLN

VISIBLE CHANGED

VISIBLECHANGED
