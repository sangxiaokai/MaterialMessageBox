# MaterialMessageBox
[WIP] Custom QMessageBox/MessageDialog in QML for Qt Quick Controls 2.0

# Screenshot

![Screenshot](http://i.imgur.com/mdi98aF.png)

# How to use

1. Create a .qml file called 'MaterialMessageBox.qml'.
2. Add this code to it:
   ```qml
   MaterialMessageBox {
        id: msgBoxId
        message: "YOUR MESSAGE HERE"
        onAccepted: {
          // your code here if OK has been clicked. 
        }
    }
    ```
3. To call the MessageBox, you need to do this: ```qmlmsgBoxId.visible = true```.
   Example:
   ```qml
   button1.onClicked: {
        msgBoxShow.visible = true
    }
    ```
