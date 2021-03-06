# JSDatePickerView

![Alt Text](https://user-images.githubusercontent.com/24965132/34535809-1ddfa72c-f091-11e7-9401-786896907352.gif)








## Introduction

This Cocoapod provides a custom date picker with a popout calendar.  The user can navigate throught the dates by clicking the left and right arrows or swiping left/right.  The user also has the option of using the pop out calendar to easily choose dates far in the future.  The calendar and view are very customizable and allow the developer to change many features.

## Code Samples

**Many features of the calendar can be customized:**

The calendar font:
```swift
js.calendarFont = UIFont.systemFont(ofSize: 20.0)
```
The calendar width
```swift
js.calendarWidth = 300.0
```
The calendar cell background color
```swift
js.cellBackgroundColor = UIColor.blue
```

**JSDatePicker can also be controlled programmatically**

Programmatically Expand:
```swift
js.expandCalendar()
```
Programmatically Collapse:
```swift
js.collapseCalendar()
```
Programmatically go left:
```swift
js.leftButtonAction()
```
Programmatically go right
```swift
js.rightButtonAction()
```


## Installation

To install simply include pod 'JSDatePickerView' in your podfile and run pod install.
