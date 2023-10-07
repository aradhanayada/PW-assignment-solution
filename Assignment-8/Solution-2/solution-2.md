# Solution
**position: relative** positions an element relative to its normal position in the document flow, and it still affects the layout of other elements.

          div {
          position: relative;
          top: 20px;
          left: 30px;
           }



**position: absolute** positions an element relative to its closest positioned ancestor or the viewport, and it's taken out of the document flow, not affecting the layout of other elements.
         
          'div {
          position: absolute;
          top: 20px;
          left: 30px;
          }'

          
![download](https://github.com/aradhanayada/PW-assignment1-solution/assets/103102710/af355f21-945e-4be9-83f0-b6948196d43d)



In summary, the key difference is that position: relative positions an element relative to its normal position in the document flow, while position: absolute positions an element relative to its closest positioned ancestor or the viewport, and it's removed from the document flow. Each has its use cases, depending on how you want to control the layout and positioning of elements on your web page.
