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
    
##Properties
- **width**
- **height**
- **margin**
- **padding**
- **float**
- **clear**
- **position**
- **top**
- **left** 
- **z-index**
- **display** 
- **visibility**
- **overflow**
<br>
- **border**
- **border-radius**
- **box-shadow**
- **background-color**
- **background-image**  
- **cursor**
<br>
- **color**
- **font-size**
- **font-weight**
- **font-family**
- **font-style**
- **text-align**
- **text-shadow**
- **text-decoration**
- **text-transform**
- **text-indent**
- **text-overflow**
- **@font-face**  
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
