# Advanced-SASS
Learning advanced features of SASS

<details>
  <summary>SASS Data Types</summary>
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
</details>
