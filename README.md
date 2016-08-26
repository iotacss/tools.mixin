# Mixins Tool #

The mixins tool contains a collection of mixins for iotaCSS.


### Installation ###

```
npm install --save iotacss-mixin
```


### Breakpoint Mixin ###

Breakpoint mixin makes it easy to create media queries. You can use it with Settings.Breakpoint or you can create your own breakpoints sass map.


#### Example ####

```sass
.myClass {
  height: 100px;
  
  // Breakpoint for small screens
  @include breakpoint(sm) {
    height: 150px;
  }
  
  // Breakpoint for medium screens
  @include breakpoint(md, $my-breakpoints-sass-map) {
    height: 200px;
  }
}
```
