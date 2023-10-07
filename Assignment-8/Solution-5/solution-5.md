# Solution
## Z-Index
The z-index property specifies the stack order of an element.
An element with greater stack order is always in front of an element with a lower stack order.
**Note:** z-index only works on positioned elements (position: absolute, position: relative, position: fixed, or position: sticky) and flex items (elements that are direct children of display:flex elements).

**Note:** If two positioned elements overlap without a z-index specified, the element positioned last in the HTML code will be shown on top.
#### Example code of z-index
HTML

     <div class="wrapper">
     <div class="dashed-box">Dashed box</div>
     <div class="gold-box">Gold box</div>
     <div class="green-box">Green box</div>
     </div>

CSS
      
        .wrapper {
        position: relative;
         }
       .dashed-box {
        position: relative;
        z-index: 1;
        border: dashed;
        height: 8em;
        margin-bottom: 1em;
        margin-top: 2em;
        }
       .gold-box {
       position: absolute;
        z-index: 3; /* put .gold-box above .green-box and .dashed-box */
        background: gold;
        width: 80%;
        left: 60px;
        top: 3em;
        }
       .green-box {
        position: absolute;
        z-index: 2; /* put .green-box above .dashed-box */
        background: lightgreen;
        width: 20%;
        left: 65%;
        top: -25px;
        height: 7em;
       opacity: 0.9;
       }

## Result
![Screenshot (115)](https://github.com/aradhanayada/PW-assignment1-solution/assets/103102710/065ade54-f731-4e45-88a6-495ecd9bee32)
 
