# Mixins




## Gradients

Directions can be either in degrees or using the 'to right' method.
https://www.w3schools.com/cssref/func_linear-gradient.asp

```
$blue:blue;
$green:green;
$red:red;

$colourList: $blue 0%,$blue 10%,$green 25%,$green 39%,$red 79%,$red 100%; 

// to bottom right, to right, to left
// degree values: 180, -180, 90, -45 
@include gradient(to left, $colourList);
```
