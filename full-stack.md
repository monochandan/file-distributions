1. Completed personal portfolio project (demo)
   
    ```
        core HTML tags,
        Nesting,
        Buttons,
        Input Field,
        Anchor Tag,
        Document Structure,
        Lists,
        [Deployment](https://app.netlify.com/teams/mkdas-chandan/projects)
    ```
    

[COLOUR CONTRAST CHECKER](https://userway.org/contrast/?fg=F8F9FA&bg=#dfe1e5)

2. CSS 1.0
   
    ```
        1. CSS SYNTAX
        1. INLINE VS BLOCK (centering the elements)
        1. MARGING (space outside the elements)
        1. PADDING (space inside the elements)
        1. BORDERS (TO DIFFERENCIATE THE ELEMENTS)
        1. DIVS (by default block. DIVIDE THE PAGE FOR MULTIPLE COMPONENTS GROUP)
        1. CLASSES (HELP TO SEPERATELY IDENTIFY MULTIPLE COMPONENTS AND DESIGN THEM)
        1. CENTERING (centering the elements)
            1. display: block, margin-left/right: auto
            2. Parent wrapper, display: block, text-align: center
            3. wrapper container (e.g.- buttons wrapped by div), display: flex, justify-content: center
    ```

    CSS 2.0
   
    ```
        1. Relative path syntax.
            - ./    --> Start from the same directory the current file is in.
            - ../   --> start from the parent directory of (the directory above) the current file.
            - /     --> start from the projects root directory.

        2. More about flex box.

        3. Utility Class - A class for a single css property.

        4. CENTERING ELEMENT.
            - (apply on wrapper div) - display: flex, margin-left/right: auto.
        
        5. CSS INHERITANCE (Write DRYer code, which means dont repeat yourself)
            - list of properties can be inherited - https://www.w3.org/TR/CSS22/propidx.html
            - fewer bugs

        6. WEB SAFE FONTS (https://www.w3schools.com/cssref/css_websafe_fonts.php)

        7. Margin & Padding Shorthand.
         - margin: top right bottom left (as clock wise).
         - margin: top/bottom right/left [if top, bottom  and right, left has the same value].
         - trending color palates - [https://coolors.co/palettes/trending]
         - shadows, hover, transition, animations
        
        8. img alt variable.

        9. Color Palettes.
    ```

3. Web Space
   ```
    1. good quality image from : https://unsplash.com/.
    2. Google Font : google.font.org.
    3. Font Family Inherit to the child component.
    4. More availiable fonts : https://www.1001fonts.com/
    5. use @font-face property for external font from https://www.1001fonts.com/
    6. span tag - it is inline, where div is blicked base
    7. id - used #id_name  and this is unique, class (.class_name) can be reused again and again.
    8. Animated image - https://giphy.com/
    9. Text Shadow - text-shadow: horizontal(+/- , push shadow right/left) vartical(+/-, push shadow top/botom)  blur color;
    10. HTML lang attribute. (language (standard language code) of the content in an html page). Reach the correct audiance. [https://developer.mozilla.org/en-US/docs/Web/HTML/Reference/Global_attributes/lang#inheritance]
   ```
    
    ```
        1. background image.
        2. webp format.
        3. google fonts.
        4. span tag.
        5. id and utility classes.
        6. text-shadow.

    ```



4. b-day gif
   
   ```
            1. hexadecimal lcode for emoji [should add this line in head <meta charset="UTF-8">] - https://www.w3schools.com/charsets/ref_emoji_celebration.asp
            2. align items
                {
                    display: flex;
                    justify-content: start, center, end, space-around, space-evenly, space-between;
                    align-items: start, center, end;
                }
        
            3.     
                --- CENTERING ELEMENT FOR DIV ---
                img is inline element so, text-alignment: center work for img or any other default inline elements.
                BUT, div is block element, fo div text-alignment does not work as It is display: block by default.
        
                So, for display:block, margin-left/right: auto will center the element,
                if the height and width is set.
        
            4. hover (pseudo-class).
                - <a> are typically inline.
                - specificity - the more specific the css property is, the higher it will be prioratize (for example id).
        
            5. Gradients (different colour fading from top to bottom or another angales).
        
            6. flex-direction.
        
            7. Grouping selector (select multiple elements/tags from html to fullfill DONT REPEAT AGAIN).
```

5. JS FUNDEMENTALS
    ```
        var, let, const : https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Grammar_and_types
        clicklictener : https://developer.mozilla.org/en-US/docs/Web/API/HTMLElement/click
        change html element text from js : https://developer.mozilla.org/en-US/docs/Web/API/HTMLElement/innerText
        textContent (more useful then innerText) : https://developer.mozilla.org/en-US/docs/Web/API/Node/textContent
        change css style also from js: https://developer.mozilla.org/en-US/docs/Web/API/HTMLElement/style
        escape element (tell js the next "/' is not string delimeter by \): let wish = 'I\'d love to see the show "The Lion King"' OR let wish = "I'd love to see the show \"The Lion King\"'


        - script tag
        - variables
        - numbers
        - strings
        - console.log()
        - functions
        - DOM
        - getElementById()
        - innerText
        - textContent

```
6. JS 1.0 
    ```
        - strictly equal (===).(100 == "100") --> TRUE. (100 === "100") --> FALSE.
        - if/else statement.
        - BOOLEAN : https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Boolean
        - querySelector : https://developer.mozilla.org/de/docs/Web/API/Document/querySelector 
        - Array: https://developer.mozilla.org/de/docs/Web/JavaScript/Reference/Global_Objects/Array/Array
        - Add elements in Array: https://developer.mozilla.org/de/docs/Web/JavaScript/Reference/Global_Objects/Array/push
        - Loops: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Loops_and_iteration
        - Math.random: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/random
        - objects: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object
    ```
