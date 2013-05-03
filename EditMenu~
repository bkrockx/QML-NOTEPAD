import Qt 4.7 // import the main Qt QML module

Rectangle{
    id: fileMenu
    width: 700; height: 350
    color: "lightblue"

    Row{
        anchors.centerIn: parent
        spacing: parent.width/6

        Button{
            id: loadButton
            buttonColor: "lightgrey"
            label: "Cut"
        }
        Button{
            id: saveButton
            buttonColor: "grey"
            label: "Paste"
        }
        Button{
            id: exitButton
            buttonColor: "darkgrey"
            label: "Select All"

            onButtonClick: Qt.quit()
        }
    }
}
