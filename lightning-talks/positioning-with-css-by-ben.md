#Positioning with CSS

* Think of a `div` as a box on a page.

```
<html>  
  <body>  
    <div id="abs">
      <div id="rel">
      </div>
    </div>
  </body>
</html>
```

* Default (Static) Positioning: Items are displayed in the order of their html code. 

* Absolute Positioning: If you use the style rule:
  ```
  .abs {  
    position: absolute;  
    left:100px;  
  }
  ```
removes the element from the normal flow of the html and positions it at the top and 100px from the left of its containing element. The containing element is the window unless specified.

* Relative Positioning: Moves it relative to where it was.

* Fixed Positioning: Affixes it to a set position on the page. 