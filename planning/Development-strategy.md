# Development strategy

## `for: Header`
- section with class called "header"
  - div with class called "header"

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

## `for: Core Values`

### `type: html` (Core Values)

- section with class called "padding-core-values"
  
  - div with class called "margin-core-values"
  
    - div with class called "table-core-values"

      - Title with class called "title-core-values"

      - div with class called "box-core-values"

        - div with class called "one-value one-value-2"

          - image with class called "image-one-value"

          - title with class called "title-one-value"

          - information with class called "info-one-value"

        - div with class called "one-value one-value-2"

          - image with class called "image-one-value"

          - title with class called "title-one-value"

          - information with class called "info-one-value"

        - div with class called "one-value one-value-2"

          - image with class called "image-one-value"

          - title with class called "title-one-value"

          - information with class called "info-one-value"

        - div with class called "one-value one-value-2"

          - image with class called "image-one-value"

          - title with class called "title-one-value"

          - information with class called "info-one-value"

### `type: css`(Core Values)

- "padding-core-values":display,-moz-box-pack,justify-content,width,padding,position,box-shadow,background, z-index,flex
- "margin-core-values":display, flex-direction,-moz-box-pack,justify-content,-moz-box-align,align-items,width,max-width,padding,margin
- "table-core-values": display,background-color,padding,flex-direction
- "title-core-values": font-size,line-height,margin-bottom,text-transform,font-family,font-weight,color,text-align,max-width
- "box-core-values":display,flex-wrap,-moz-box-flex,flex-grow,-moz-box-pack,justify-content
- "one-value":  display,width,flex-direction,align-items
- "image-one-value": width,height,object-fit,border-radius
- "title-one-value:font-size,line-height,margin-bottom,text-transform,font-family,font-weight,color,text-align,max-width
- "info-one-value":color,text-align,max-width,line-height,font-size,font-family,margin,white-space,word-break,font-weight

## `for: Sucesses story`

### `type: html` (our successes story)

- section with class called "our successes story"

    - Title with h2, class called "Demo"

      - div with class called "gita"

      - div with class called "suc"

      - div with class called "pic"

    - Title with h4, class called "name"
   
    - Title with h5, class called "pos"
    
    - p-class called "bio"

 ### `type: css`(successes story)    
 
 - h2  "demo": align:left
    
 - "pic": width,height,margin,float,background-position,filter,float,margin-top,margin-left,border-radius
    
 - "name": margin,font-size,color,margin-left,margin-right
 
 - "pos": margin-left,margin-right
 
 - "name": color,margin-left,margin-right,font-size

 -  "bio": margin-top,margin-left,margin-right
 
## `for: Support the developers`

### `type: html` (Support the developers)

- section with class called "section-support"

    - div with class called "outer-container"

      - div with class called "inner-container"

        - div with class called "div-support"

          - div with class called "div-content"

            - Title with h1, class called "support-title"
    
            - p-class called "support-paragraph"

### `type: css`(support the developers) 

- "section-support": display,justify-content,width,padding,position,box-shadow,background,flex 

- "outer-container": display,flex-direction,justify-content,align-items,width,max-width,padding,margin

- "inner-container": display,width,overflow

- "div-support": display,flex-direction,column,width,padding-right

- "div-content": align-items,background,box-shadow,box-sizing,display,flex-direction,height,margin,max-height,max-width,padding,width

- "support-title": font-size,color,text-align,font-family,font-weight

- "support-paragraph" : text-align,color,font-size,font-family,font-weight

## `for: footer`

### `type: html` (footer)

- section with class called "footer"

  - div with class called "container"

  - div with class called "box"

- Title with h3, class called "demo"

  - p-class called "place"

  - a class "place1"

### `type: css`(footer)

- "footer": padding,position,box-shadow,background,flex,disply,-moz-box-pack,justtify-center,width,margin,border,font-size,font-style,vertical-align,box-sizing,font-familliy

- "container":display,flex-direction,-moz-box-pack,justify-content,-moz-box-align,align-items,max-width,padding,margin,font-size,font-style,text-decoration,box-sizing,border-box,font-family

- "box": -moz-box-align,align-items,background,box-shadow,box-sizing,border-box,flex,flex-direction,-moz-box-flex,height,-moz-box-pack,justify-content,width,position,border,font-size,font-style,vertical-align,font-family

- "demo": font-size,line-height,margin,text-transform,font-family,font-weight,color,text-align,max-width,padding,border,font-style,vertical-lign,box-sizing,font-family,

- "place": color,text-align,max-width,line-height,font-size,font-family,margin,white-space,word-break,font-weight,font-style,text-decoration,box-sizing,

- "place1": color,text-align,max-width,line-height,font-size,font-family,white-space,word-break,fontweight,fontstyle,verticalalign,text,decoration,boxsizing,


 
 
 


 
 
 
 





