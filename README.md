# Mixins Tool #

The mixins tool contains a collection of mixins for iotaCSS.


### Installation ###

```
npm install --save iotacss-mixin
```


### Breakpoint Mixin ###

Breakpoint mixin makes it easy to create media queries.


#### Syntax ####

```sass
@include breakpoint($breakpoint-size, $breakpoint-sizes)
```


#### Parameters ####

* $breakpoint-size: Size of the breakpoint you want to use
* $breakpoint-sizes: A Sass map that contains breakpoints. By default, uses Settings.Breakpoint. This parameter is optional.


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
