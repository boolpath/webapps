# CSS3

##Selectors
- **Elements**  

    ```css
    htmlTag1, htmlTag2, htmlTag3,... {...}
    ```
    
- **IDs**  

  ```css
  htmlTag#tagID {...}
  ```
  
- **Classes**  

  ```css
  htmlTag.tagClassName {...}
  ```
  
- **Nesting**  

  ```css
  outerHtmlTag innerHtmlTag {...}
  ```
  
- **Children**  

  ```css
  parentHtmlTag > childrenHtmlTag {...}
  ```
  
- **Siblings**  

  ```css
  htmlTag + adjacentSiblingsHtmlTag {...}
  htmlTag ~ anySiblingsHtmlTag {...}
  ```

- **Pseudo-classes**  

    ```css
    htmlTag:pseudo-class {...}
    ```  
    ```css
    (forms)         :optional   :required   :read-only   :read-write    :out-of-range
    (state)         :visited    :hover      :active      :target        :focus
                    :enabled    :checked    :disabled    ::selection
    (structure)     :root           :empty  
                    :first-child    :only-child    :last-child  
                    :first-of-type  :only-of-type  :last-of-type 
                    :nth-child(n)   :nth-last-child(n)  
                    :nth-of-type(parity)  :nth-last-of-type(parity) 
    (exclusion)     :not(.class)
    (order)         ::before   ::after   ::first-letter   ::first-line
    ```
- **Attributes**

    ```css
    htmlTag[attribute operator value] {...}
    ```  
    ```css
    OPERATORS
    [... = value]   (equals value)
    [...*= value]   (contains value)
    [...~= value]   (contains value, after splitting by spaces)
    [...|= value]   (starts with or contains value, after splitting by hyphens)
    [...^= value]   (starts with value)
    [...$= value]   (ends with value)
    ```

- **Wildcard**
    ```css
    * {...}
    ```
    
##Properties
- **width**  

    ```css
    width: 100%;            min-width: 50px;            max-width: 100px;
    ```
- **height**  

    ```css
    height: 100px;          min-height: 50px;           max-height: 100px;
    ```

- **margin**  

    ```css
    margin: 0px auto;       margin-top: 10px;           margin-left: 10%;
    ```

- **padding**  

    ```css
    padding: 0px auto;      padding-top: 10%;           padding-left: 10px;
    ```

- **float**  

    ```css
    float: left;            float: right;
    ```

- **clear**  

    ```css
    clear: left;            clear: right;
    ```

- **position**  

    ```css
    position: absolute;     position: relative;         position: fixed;
    ```

- **top**  

    ```css
    top: 100px;
    ```

- **left**   

    ```css
    left: 100px;
    ```

- **z-index**  

    ```css
    z-index: 1;
    ```

- **display**   

    ```css
    display: block;         display: none;
    ```

- **visibility**  

    ```css
    visibility: hidden;
    ```

- **overflow**  

    ```css
    overflow: visible;      overflow: hidden;          overflow: scroll;
    ```
<br>
- **border**  

    ```css
    border: 1px solid #000;
    ```
    

- **border-radius**  

    ```css
    border-radius: 10px;            border-radius-top-left: 10px;
    ```
    

- **box-shadow**  

    ```css
    
    ```
    

- **background-color**  

    ```css
    background-color: #fff;         background-color: rgb(255, 255, 255);
    ```
    

- **background-image**    

    ```css
    background-image: url("image.png")
    ```
    

- **cursor**    

    ```css
    cursor: pointer;        /*none, auto, move, help, progress, zoom-in, x-resize,...*/
    ```
    
<br>
- **color**  

    ```css
    color: black;            color: #000;               color: rgb(0, 0, 0); 
    ```
    
- **font-size**  

    ```css
    font-size: 1em;         font-size: 16px;
    ```
    
- **font-weight**  

    ```css
    font-weight: bold;
    ```
    

- **font-family**  

    ```css
    font-family: Arial, sans-serif;
    ```
    
- **font-style**  

    ```css
    font-style: italic;         /**/
    ```
    

- **text-align**  

    ```css
    text-align: center;         text-align: left;           text-align: right;
    ```
    

- **text-shadow**  

    ```css
    
    ```
    

- **text-decoration**  

    ```css
    
    ```
    

- **text-transform**  

    ```css
    
    ```
    

- **text-indent**  

    ```css
    
    ```
    

- **text-overflow**  

    ```css
    
    ```
    

- **@font-face**   

    ```css
    
    ```
    
<br>
- **list-style-type**
- **list-style-image**
- **list-style-position**  
<br>
- **border-collapse**
- **border-spacing**
- **vertical-align**  
<br>
- **transform**
- **transform-origin**
- **transform-style**  
<br>
- **transition**
- **transition-property**
- **transition-duration**
- **transition-delay**
- **transition-timing-function**  
<br>
- **animation**
- **animation-delay**
- **animation-duration**
- **animation-direction**
- **@keyframes**  
<br>
- **@import**  

    ```css
    @import "style.css";
    ```
