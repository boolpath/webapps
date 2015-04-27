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
    clear: left;            clear: right;               clear: both;
    ```

- **position**  

    ```css
    position: absolute;     position: relative;         position: fixed;
    ```

- **top, bottom**  

    ```css
    top: 100px;             bottom: 100px;
    ```

- **left, right**   

    ```css
    left: 100px;            right: 100px;
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
- **outline**  

    ```css
    outline: 1px solid #000;
    ```

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
    box-shadow: 10px 10px 5px 0px #ccc [inset]; /*horizontal vertical blur spread color*/
    ```
    
- **background (gradient)**  

    ```css
    background: linear-gradient(angle, color-stop1, color-stop2);
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
    cursor: pointer;    /*none, auto, move, help, progress, zoom-in, x-resize, url(),...*/
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

- **direction**  

    ```css
    direction: ltf;             direction: rtl;             
    ```

- **columns**  

    ```css
    columns: 3;                 columns: 1px solid black;
    ```

- **text-align**  

    ```css
    text-align: center;         text-align: left;           text-align: right;
    ```
    
- **text-shadow**  

    ```css
    text-shadow: 3px 3px #ccc;
    ```
    
- **text-decoration**  

    ```css
    text-decoration: underline;     text-decoration: line-through;      text-decoration: none;
    ```
    
- **text-transform**  

    ```css
    text-transform: lowercase;      text-transform: uppercase;      text-transform: capitalize;
    ```
    
- **text-indent**  

    ```css
    text-indent: 50px;              text-indent: 10%;
    ```

- **text-overflow**  

    ```css
    text-overflow: clip;            text-overflow: ellipsis;
    ```
    
- **letter-spacing**  

    ```css
    letter-spacing: 2px;            letter-spacing: 0.3em;
    ```
 
- **white-space**  

    ```css
    white-space: normal;            /*nowrap, pre, pre-wrap, pre-line, initial*/
    ```
    
- **@font-face**   

    ```css
    font-family: thefont;
    src: url(font.woff);
    ```
    
<br>
- **counter-increment**  

    ```css
    counter-increment: counterName counterIncrement;
    ```

- **content**  

    ```css
    content: "abc123";              content: counter(counterName) "...";
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

    ```css
    transform: scale(2);        transform: rotate(90deg);       transform: translate(10px, 10px);         
    ```
  
- **transform-origin**
- **transform-style**  
<br>
- **transition**  

    ```css
    transition: property duration timing-function delay|initial|inherit;
    ```

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
