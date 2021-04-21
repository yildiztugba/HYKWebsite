# Development strategy

## `for: Result`

### `type: html` (Result)

- section with class called "ourResult"

  - div with class called "resultLayout"

    - div with class called "resultBox"

      - div with class called "resultInfo"

        - Title with h2, class called "title"

        - Information with p, class called "titleDefinition"

      - div with class called "tableImpact"

        - div with class called "columnOfTable"

          - Title with h1, class called "cTitle"

          - information with p, class called "cParag"

        - div with class called "columnOfTable"

          - Title with h1, class called "cTitle"

          - information with p, class called "cParag"

        - div with class called "columnOfTable"

          - Title with h1, class called "cTitle"

          - Information with p, class called "cParag"

### `type: css`(Result)

- "ourResult":display,-moz-box-pack,justify-content,width,padding,position,box-shadow,background,z-index,flex

- "resultLayout":display,flex-direction,-moz-box-pack,justify-content,-moz-box-align,align-items,width,max-width,padding,margin

- "resultBox":display,flex-direction,-moz-box-align,align-items,box-shadow,padding,margin-bottom

- "resultInfo":display,flex-direction,-moz-box-align,align-items,width,margin

- "title":font-size,line-height,margin-bottom,text-transform,font-family,font-weight,color,text-align,max-width

- "titleDefinition":color, text-align, max-width,line-height,font-size,font-family, margin,white-space,word-break,font-weight:

- "tableResult":display,width,-moz-box-pack,justify-content

- "columnOfTable": display,flex-direction,background-color,width,padding

- "cTitle":font-size,line-height,margin-bottom,text-transform,font-family,font-weight,color,text-align,max-width

- "cParag":color,text-align,max-width,line-height,font-size,font-family,margin,white-space,word-break,font-weight

- "h1": margin,margin-bottom,padding,border,font-size,font-style,vertical-align,text-decoration,box-sizing,font-family

- "h2": margin,margin-bottom,padding,border,font-size,font-style,vertical-align,text-decoration,box-sizing,font-family

- "div": margin,margin-bottom,padding,border,font-size,font-style,vertical-align,text-decoration,box-sizing,font-family

- "section": margin,padding,border,font-size,font-style,vertical-align,text-decoration,box-sizing,font-family