input.buttonB.onEvent(ButtonEvent.Click, function () {
    pauze = _140bpm
    ifpotentio = 0
})
input.buttonA.onEvent(ButtonEvent.Click, function () {
    ifpotentio = 1
})
let potentiometer = 0
let ifpotentio = 0
let pauze = 0
let _140bpm = 0
let _120bpm = 20
_140bpm = 300
pauze = 200
forever(function () {
    potentiometer = 0
    if (ifpotentio == 1) {
        light.setPixelColor(Math.randomRange(0, 9), 0xff0000)
        pause(pins.A2.analogRead())
        light.setPixelColor(Math.randomRange(0, 9), 0x0000ff)
        pause(pins.A2.analogRead())
        light.setPixelColor(Math.randomRange(0, 9), 0x00ff00)
        pause(pins.A2.analogRead())
        light.setPixelColor(Math.randomRange(0, 9), 0x000000)
        pause(pins.A2.analogRead())
    } else {
        light.setPixelColor(Math.randomRange(0, 9), 0xff0000)
        pause(pauze)
        light.setPixelColor(Math.randomRange(0, 9), 0x0000ff)
        pause(pauze)
        light.setPixelColor(Math.randomRange(0, 9), 0x00ff00)
        pause(pauze)
        light.setPixelColor(Math.randomRange(0, 9), 0x000000)
        pause(pauze)
    }
})
