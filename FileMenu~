import Qt 4.7 // import the main Qt QML module

Rectangle{
    id: fileMenu
    width: 700; height: 350

    Row{
        anchors.centerIn: parent
        spacing: parent.width/6

        Button{
            id: loadButton
            buttonColor: "lightgrey"
            label: "Load"
        }
        Button{
            id: saveButton
            buttonColor: "grey"
            label: "Save"
        }
        Button{
            id: exitButton
            buttonColor: "darkgrey"
            label: "Exit"

            onButtonClick: Qt.quit()
        }
    }
}
