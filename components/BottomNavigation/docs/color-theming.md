<!--docs:
title: "Color Theming"
layout: detail
section: components
excerpt: "How to theme Bottom Navigation using the Material Design color system."
iconId: bottom_navigation
path: /catalog/bottomnavigation/color-theming/
-->

# Bottom Navigation Color Theming

You can theme a bottom navigation with your app's color scheme using the ColorThemer extension.

You must first add the Color Themer extension to your project:

```bash
pod 'MaterialComponents/BottomNavigation+Extensions/ColorThemer'
```

## Example code

<!--<div class="material-code-render" markdown="1">-->
#### Swift
```swift
// Step 1: Import the ColorThemer extension
import MaterialComponents.MaterialBottomNavigation_ColorThemer

// Step 2: Create or get a color scheme
let colorScheme = MDCSemanticColorScheme()

// Step 3: Apply the color scheme to your component
MDCBottomNavigationBarColorThemer.applySemanticColorScheme(colorScheme, to: component)
```

#### Objective-C

```objc
// Step 1: Import the ColorThemer extension
#import "MaterialBottomNavigation+ColorThemer.h"

// Step 2: Create or get a color scheme
id<MDCColorScheming> colorScheme = [[MDCSemanticColorScheme alloc] init];

// Step 3: Apply the color scheme to your component
[MDCBottomNavigationBarColorThemer applySemanticColorScheme:colorScheme
     toBottomNavigation:component];
```
<!--</div>-->
