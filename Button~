import Qt 4.7
Rectangle {
    id: button
    width: 150; height: 75

    property string label: "Button"
    property color buttonColor: "lightblue"
    property color onHoverColor: "gold"
    property color borderColor: "white"

    signal buttonClick()
    onButtonClick: {
        console.log(buttonLabel.text + " clicked")
    }

    Text{
        id: buttonLabel
        anchors.centerIn: parent
        text: button.label
    }

    MouseArea{
        id: buttonMouseArea
        anchors.fill: parent
        onClicked: buttonClick()
        hoverEnabled: true
        onEntered: parent.border.color = onHoverColor
        onExited: parent.border.color = borderColor
    }

    // determines the color of the button by using the conditional operator
    color: buttonMouseArea.pressed ? Qt.darker(buttonColor, 1.5) : buttonColor
}
