# micro-bit-
project with microbit for multipilicatin and sumation
input.onButtonPressed(Button.A, function () {
    num1 += 1
})
input.onButtonPressed(Button.AB, function () {
    result = num1 + num2
    basic.showNumber(result)
})
input.onButtonPressed(Button.B, function () {
    num2 += 1
})
input.onGesture(Gesture.Shake, function () {
    result = num1 * num2
    basic.showNumber(result)
})
let result = 0
let num2 = 0
let num1 = 0
num1 = 0
num2 = 0
result = 0
