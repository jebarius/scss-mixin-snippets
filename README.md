# Mixins




## Gradients

```
$blue:blue;
$green:green;
$red:red;

$colourList: $blue 0%,$blue 10%,$green 25%,$green 39%,$red 79%,$red 100%; 

// to bottom right, to right, to left or just right, left, top, bottom
// degree values: 180, -180, 90, -45 
@include gradient(to left, $colourList);
```



## keyframes

```
@include keyframes(borderColour) {
   0% {
     border-color: red;
   }
   50% {
      border-color: green;
   }
   100% {
      border-color: blue;
   } 
}
```


## Pseudo

```
div::after {
    @include pseudo;
    // @include pseudo(inline-block, relative, '');
    top: 50px; 
    left: 50px;
    width: 50%; 
    height:300px;
}
```
