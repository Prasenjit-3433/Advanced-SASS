# Advanced-SASS
Learning advanced features of SASS

## SASS Data Types
  In SASS, there are total 7 data types -> Numbers, Strings, Colors, Lists, Maps, Booleans, Null.

### Numbers ###
a number can be integer, decimal or with units like px, rem, em, % etc.

```scss
.main-heading {
    font-weight: 400;
    line-height: 1.5;
    font-size: 5px; // rem, em or % 
}
```
### Strings ###
a string can defined with or without quotes("").

```scss
.sub-heading {
    font-family: 'Helvetica', Arial, sans-serif;
    font-weight: bold;
    font-style: italic;
}
```
### Colors ###

```scss
.sub-heading {
    font-family: 'Helvetica', Arial, sans-serif;
    font-weight: bold;
    font-style: italic;
}
```
### Colors ###

```scss
.sub-heading {
    color: red;
    background-color: #ff0000;
    border-color: rgba(255, 0, 0, 0.5);
    outline-color: hsl(0, 100%, 50%);
}
```
### Lists ###
a list is like an array and can store multiple values. The values are itself another data-types and separated by space or commas.

```scss
.sub-heading {
    margin: 10px 30px 15px 19px;
    font-family: 'Raleway', 'Dosis', 'Lato';
    border: 3px solid red;
}
```
### Map ###
Map can store data in key-value pairs where key can a number, string.

```scss
$colors: (
    1: red,
    green: green,
    "blue": blue
);
```

Now one can use the data in the following way
```scss
h1 {
    color: map-get($colors, 1);
    background-color: map-get($colors, "blue");
    border-color: map-get($colors, green);
}
```
### Boolean ###
It has two possible values - true or false. It is used with `if` statements.

### Null ###
Null is just empty, it has no value at all. so one say, it represents empty state.
**Note**: It's case sensitive, it should be written as `null` with lowercase.