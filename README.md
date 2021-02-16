# Android Resources Value Formats
⛻ Standard dimensions, color codes for Android

- **Color codes** :\
Android app development design colors.
  - [x] *Color Codes from Google's Material design color palette:* 
  [Material color codes](https://github.com/rshavinda/android-resources-value-formats/blob/main/Color%20Codes/colors.xml)


- **Standard dimensions** :\
Dimensions file which is used to define all size dimensions used within an app. A dimension is specified with a number followed by a unit of measure. For example: *10px, 5sp*. Dimensions should be defined within `res/values/dimens.xml`.

  - [x] *Dimensions Style #01* \
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

 - [x] *Dimensions Style #02* \
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
