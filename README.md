# Android Resources Value Formats
⛻ Standard dimensions, color codes for Android

---
### color.xml
Android app development design colors.
  - [x] *Color Codes from Google's Material design color palette:* [Material color codes](https://github.com/rshavinda/android-resources-value-formats/blob/main/Color%20Codes/colors.xml) <br/>
  

  
      ![#D32F2F](https://via.placeholder.com/15/D32F2F/000000?text=+) ` ⚬ Red` <br/>
      ![#D81B60](https://via.placeholder.com/15/D81B60/000000?text=+) ` ⚬ Pink ` <br/>
      ![#8E24AA](https://via.placeholder.com/15/8E24AA/000000?text=+) ` ⚬ Purple ` <br/>
      ![#5E35B1](https://via.placeholder.com/15/5E35B1/000000?text=+) ` ⚬ Deep Purple ` <br/>
      ![#303F9F](https://via.placeholder.com/15/303F9F/000000?text=+) ` ⚬ Indigo ` <br/>
      ![#1976D2](https://via.placeholder.com/15/1976D2/000000?text=+) ` ⚬ Blue ` <br/>
      ![#039BE5](https://via.placeholder.com/15/039BE5/000000?text=+) ` ⚬ Light Blues ` <br/>
      ![#00ACC1](https://via.placeholder.com/15/00ACC1/000000?text=+) ` ⚬ Cyan ` <br/>
      ![#00796B](https://via.placeholder.com/15/00796B/000000?text=+) ` ⚬ Teal ` <br/>
      ![#43A047](https://via.placeholder.com/15/43A047/000000?text=+) ` ⚬ Green ` <br/>
      ![#7CB342](https://via.placeholder.com/15/7CB342/000000?text=+) ` ⚬ Light Green ` <br/>
      ![#A4B42B](https://via.placeholder.com/15/A4B42B/000000?text=+) ` ⚬ Lime ` <br/>
      ![#FFEB3B](https://via.placeholder.com/15/FFEB3B/000000?text=+) ` ⚬ Yellow ` <br/>
      ![#FFCA28](https://via.placeholder.com/15/FFCA28/000000?text=+) ` ⚬ Amber ` <br/>
      ![#FF9800](https://via.placeholder.com/15/FF9800/000000?text=+) ` ⚬ Orange ` <br/>
      ![#E64A19](https://via.placeholder.com/15/E64A19/000000?text=+) ` ⚬ Deep Orange` <br/>
      ![#5D4037](https://via.placeholder.com/15/5D4037/000000?text=+) ` ⚬ Brown` <br/>
      ![#607D8B](https://via.placeholder.com/15/607D8B/000000?text=+) ` ⚬ Blue Grey ` <br/>
      ![#757575](https://via.placeholder.com/15/757575/000000?text=+) ` ⚬ Grey ` <br/>

---
### dimens.xml
Dimensions file which is used to define all size dimensions used within an app. A dimension is specified with a number followed by a unit of measure. For example: *10px, 5sp*. Dimensions should be defined within `res/values/dimens.xml`.

  - [x] **Dimensions Style #01** <br/>
 The 'space' tag represent both margins and padding properties as follows,
```xml
  <resources>
       <!-- Margins and Padding -->
       <dimen name="space_xl">32dp</dimen>
       <dimen name="space_large">24dp</dimen>
       <dimen name="space_medium">16dp</dimen> 
       <dimen name="space_small">8dp</dimen>
       <dimen name="space_xs">4dp</dimen>
  </resources>
```
   > Format 01 : [dimens.xml](https://github.com/rshavinda/android-resources-value-formats/blob/main/Dimensions%20Style%20%2301/dimens-clean.xml) ( space_xs, space_xl ) <br/>
   > Format 02 : [dimens.xml](https://github.com/rshavinda/android-resources-value-formats/blob/main/Dimensions%20Style%20%2301/dimens.xml) ( space_extra_small, space_extra_large )
<br/>
<br/>

 - [x] **Dimensions Style #02 :** 
 Margins and padding properties defined in separate sections as shown below,
```xml
  <resources>
        <!-- Margins -->
        <dimen name="margin_xxl">48dp</dimen>
        <dimen name="margin_xl">32dp</dimen>
        <dimen name="margin_large">24dp</dimen>
        <dimen name="margin_medium">16dp</dimen> 
        <dimen name="margin_small">8dp</dimen>
        <dimen name="margin_xs">4dp</dimen>

        <!-- Padding -->
        <dimen name="padding_xl">32dp</dimen>
        <dimen name="padding_large">24dp</dimen>
        <dimen name="padding_medium">16dp</dimen>
        <dimen name="padding_small">8dp</dimen>
        <dimen name="padding_xs">4dp</dimen>
  </resources>
```
   > Format 01 : [dimens.xml](https://github.com/rshavinda/android-resources-value-formats/blob/main/Dimensions%20Style%20%2302/dimens-clean.xml) ( margin_xs, padding_xl ) <br/>
   > Format 02 : [dimens.xml](https://github.com/rshavinda/android-resources-value-formats/blob/main/Dimensions%20Style%20%2302/dimesns.xml) ( margin_extra_small, padding_extra_large )
