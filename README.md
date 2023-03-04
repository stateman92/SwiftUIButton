# SwiftUIButton
An introduction to handling SwiftUI Buttons! ⬇️

### How to use

You can use the style on a button like so:

```swift
Button {
    print("The button is tapped!")
} label: {
    Text("Tap me!")
}
.buttonStyle(BaseButtonStyle(icon: .leading(.init(systemName: "circle")),
                             size: .normal(cornerRadius: 15),
                             theme: DefaultButtonTheme()))
```

For details see the Example app.

### Example

<p style="text-align:center;"><img src="https://github.com/stateman92/SwiftUIButton/blob/main/Resources/screenshot.png?raw=true" width="50%" alt="Example"></p>
