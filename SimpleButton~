import Qt 4.7
Rectangle {
    id: simpleButton
    color: "grey"
    width: 150; height: 75

    Text{
        id: buttonLabel
        anchors.centerIn: parent
        text: "button label"
    }

    MouseArea{
        id: buttonMouseArea

        anchors.fill: parent // anchor all sides of the mouse area to the rectangle's anchors
        // onClicked handles valid mouse button clicks
        onClicked: console.log(buttonLabel.text + " clicked")
    }
}
