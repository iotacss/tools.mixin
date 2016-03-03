# Mixins Tool #

The mixins tool contains a collection of mixins for iotaCSS.


### Installation ###

```
npm install --save iotacss-mixin
```


### Breakpoint Mixin ###

Breakpoint mixin makes it easy to create media queries based on Settings.Breakpoint.


#### Example ####

```
.myClass {
  height: 100px;
  
  // Breakpoint for small screens
  @include breakpoint(sm) {
    height: 150px;
  }
  
  // Breakpoint for medium screens
  @include breakpoint(md) {
    height: 200px;
  }
}
```
