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
    (links)         :visited     :hover       :active    :target
    (buttons)       :enabled     :disabled    :checked
    (structural)    :root           :empty  
                    :first-child    :only-child    :last-child  
                    :first-of-type  :only-of-type  :last-of-type 
                    :nth-child(n)   :nth-last-child(an+b)  
                    :nth-of-type(parity)  :nth-last-of-type(parity) 
    (exclusive)     :not(.class)
    ```
- **Attributes**

    ```css
    htmlTag[attribute operator value] {...}
    ```  
    ```css
    OPERATORS
    [...*= value]   (contains value)
    [...~= value]   (contains value, after splitting by spaces)
    [...|= value]   (starts with or contains value, after splitting by hyphens)
    [...^= value]   (starts with value)
    [...$= value]   (ends with value)
    ```
