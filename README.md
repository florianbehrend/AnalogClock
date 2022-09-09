# AnalogClock
<p align="center">
 <img width="200px" src="https://github.com/florianbehrend/AnalogClock/blob/master/AnalogClock.PNG"
    align="center"
    alt="Analog Clock"
    />
</p>

## 🛠Setup

Add this to your app build.gradle:

```gradle
implementation 'com.github.florianbehrend:AnalogClock:v0.1'
```
## Usage

Add to your layout xml-file:

```xml
<com.itbehrend.analogclockview.AnalogClockView
        android:layout_width="300dp"
        android:layout_height="300dp"
        app:showSecondPointer="true"
        app:showNumbers="true"
        app:secondColor="@color/design_default_color_primary"
        />
```

## ⚙ Options

AnalogClockView XML-options:
- `borderColor` - border color of clock 
- `clockBackgroundColor` - background color of clock
- `hourColor` - color of hour hand
- `minuteColor` - color of minute hand
- `secondColor` - color of second hand
- `numbersColor` - color of numbers
<br><br>
- `showSecondPointer` - show second hand (default = false)
- `showNumbers` - show numbers (default = false)
<br><br>
- `borderStrokeWidth` - width of border (default = 8)
- `hourStrokeWidth` - width of hour hand (default = 12)
- `minuteStrokeWidth` - width of minute hand (default = 9)
- `secondStrokeWidth` - width of minute hand (default = 7)

## License

MIT License

Copyright (c) 2022 Florian Behrend

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
