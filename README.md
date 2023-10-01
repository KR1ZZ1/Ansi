# Ansi
Ansi Styling and Coloring for AHK
- Tested with Visual Studio Code's debug console
- Tested on Discord (Note: Some codes does not work on discord)

How to use

    ; One use
    Clipboard := Ansi.wrap("String to wrap", "red", "underline", "italic", "blinking")

    ; Multiple uses
    Style := new Ansi
    Clipboard := Style.wrap("String to wrap", Style.rgb, 255, 0, 0)
    Clipboard := Style.wrap("String to wrap", Style.Discord, "red", Style.black_background)
