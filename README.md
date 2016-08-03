# ACFloatingTextField

UITextfield class to float the Placeholder and customize the placeholder while editing.
i have remove require add delegate.

## Features

- [x] Add Floating effect In UITextfield Placeholder.
- [x] Change the Placeholder Text Color.
- [x] Change the Placeholder Text Color when UITextfield begins editing.
- [x] Add bottom line in UITextfield.
- [x] Change the bottom line color.
- [x] Change the bottom line color when UITextfield begins editing.
- [ ] The best is yet to come.


## Installation

Download the Sample and drag & drop the ACFloatingTextField.h and ACFloatingTextField.m in your project.

## How To Use.

**1) Add Textfield From Storyboard in View Controller and Set the class to ACFloatingTextField or create the textfield programmatically.**

**2) Set Placeholder Text By Following Method.**

```objective-c

textField.placeholder = @"Username";

```



##Customization

**1) Change the colour of Bottom Line.** 

```objective-c

_textField.btmLineColor = [UIColor blueColor];

```

**2) Change the selected State colour for Bottom Line.**

```objective-c

_textField.btmLineSelectionColor = [UIColor orangeColor];

```

**3) Change the Placeholder Color.**

```objective-c

_textField.placeHolderTextColor = [UIColor redColor];

```

**4) Change the Selected Placeholder Color.**

```objective-c

_textField.selectedPlaceHolderTextColor = [UIColor greenColor];

```

## Communication

- If you **found a bug**, open an issue.
- If you **have a feature request**, open an issue.
- If you **want to contribute**,please submit a pull request.

## License

ACFloatingTextField is released under the MIT license. See LICENSE for details.
