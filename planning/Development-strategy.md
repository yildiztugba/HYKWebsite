# Development strategy

## `for: Header`

### `type: html` (Header)

- section with class called "header"

  - div with class called "container-header"
  
    - logo with class "logo"

  - div with class "header-right"

    - a with class "nav_link"

    - button with class "header-right button"

### `type: css` (Header)

- "header": overflow, background, padding

- "container_header": width, margin, padding

- "logo img" height, width, cursor

- "header a" float, color, text-align, padding, text-decoration, font-size, line-height, font-family

- "header-right" float

- "header-right a:hover" border-bottom
  
- "header-right button" border, font-weight, outline, background, color, padding, border-radius, cursor

## `for: Main Image`

### `type: html` (Main Image)

- section with class called "container img"

  - img with class called "img-fluid"

### `type: css` (Main Image)

- "container img" width, margin, padding

- "img-fluid" display, max-width, height, max-width, line-height, margin, word-break, font-weight, margin

## `for: Our Program`

### `type: html` (Our Program)

- section with class called "our-program"

  - div with class called "explanation-wrapper"

    - div with class called "explanation"

    - Title with h2, class called "op-title"

    - Information with p, class called "program-info"
  
  - div with class called "exp-img-outer"
  
  - div with class called "exp-img"
  
### `type: css`

- "our-program": display, justify-content, width, padding, position, box-shadow, background, z-index, flex

- "explanation-wrapper" : width,display,margin

- "explanation": display, flex, align-items

- "op-title": padding, font-size, line-height

- "program-info": padding, font-size, line-height

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

## `for: Success stories`

### `type: html` (our Success stories)

- section with class called "our successes story"

  - Title with h2, class called "Demo"

    - div with class called "gita"

    - div with class called "suc"

    - div with class called "pic"

  - Title with h4, class called "name"
  
  - Title with h5, class called "pos"

    - p-class called "bio"

### `type: css`(successes stories)

- h2  "demo": align:left

- "pic": width,height,margin,float,background-position,filter,float,margin-top,margin-left,border-radius

- "name": margin,font-size,color,margin-left,margin-right

- "pos": margin-left,margin-right

- "name": color,margin-left,margin-right,font-size

- "bio": margin-top,margin-left,margin-right

## `for: Our Partners`

### `type: html`(Our Partners)

- section with class called "our-partners"

- div with class called "our-partners-box"

  - div with class called "box-title"

  - h2 with class called "our-partner-title"

  - link button for "become a partner"

    - svg with class called "right-arrow"

- div with class called "partners-box"

  - *12 div with partners logos

### `type: css`(Our Partners)

- our-partners: display, justify-content, width, padding.

- our-partners-box: display, flex-direction, justify-content, max-width.

- box-title: display, width, justify-content

- h2 : margin, font-size, font-family

- logos: align-items, webkit-box-align, display

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

## `for: donation form`

### `type: html` (donation form)

- div with class called "container-donate"

  - form with class called "form-donate"

    - div with class called "select-donate"

      - labels with class called "donate-label"

        - radio buttons with class called "radio-donate" for 'One time' and 'Monthly'

        - label with class called "donate-times"

        - div with class called "options-donate"

          - ul with class called "amount-list"

          - Multiple li with class called "amount-options"

        - label with class called "donate-times" for amount

        - input type of number with class called "input-donate"

        - label with class called "donate-times" for message

        - input type of text with class called "input-donate"

        - button with class called "donate-button"

### `type: css`(donation form)

- "container-donate": display,flex-direction,width,margin,padding,border,font-size,font-style,vertical-align,text-decoration,box-sizing,font-family

- "form-donate": display,flex-direction,align-items,margin,padding,border,font-size,font-style,vertical-align,text-decoration,box-sizing,font-family

- "select-donate": display,flex-direction,margin,padding,border,font-size,font-style,vertical-align,text-decoration,box-sizing,font-family

- "radio-donate": cursor,margin-right,font-size,font-style,font-family

- "donate-times": color,text-align,max-width,line-height,font-size,font-family,margin,white-space,padding,border,font-style,text-decoration,font-weight

- "amount-options": display,border,color,padding,cursor,justify-content,background-color,font-family,margin,font-size,text-decoration,font-weight

- "input-donate": width,border-color,border-style,border-width,border-image,margin,font-size,padding,box-sizing,color,background-color,outline

- "donate-button":  font-size,line-height,text-decoration,background-color,color,font-weight,border-radius,box-sizing,padding,cursor,font-family

## `for: Contact Us`

### `type: html` (contact us)

- section with class called "mainscreen"

  - div with class called "container__mainscreen"

    - div with class called "mainscreen_contactus"

      - Title h1 with class called "mainscreen__header"

        - p-class with class called "mainscreen_form"

          - form with cless called "mainscreen__form"

            - label with class called "mainscreen__form__name"

            - button with class called "mainscreen__form__button"

      - div with class called "mainscreen__center"

      - div style with class called "mainscreen__img"
  
### `type: css`(contact us)

- "mainscreen": display,-webkit-box-pack justify-content,width,padding,position,box-shadow,background,z-index, flex

- "container__mainscreen": display,width

- "mainscreen_contactus" : display,flex-direction, width, height, background-color, padding

-"mainscreen__header": color,text-align, max-width, font-size,line-height margin, white-space, font-family font-weight, word-break

-"mainscreen_form": font-size,line-height margin-bottom, text-transform, font-family font-weight, color, text-align, max-width

-"mainscreen__form" display, flex-direction,max-width, align-items

-"mainscreen__form__name" color, text-align, max-width, line-height, font-size, font-family, margin, white-space, word-break, font-weight

-"mainscreen__form__input" color, border, border-radius, outline, background-color, padding, width

-"mainscreen__form__message" color, border, border-radius, outline, background-color, padding, width, margin-bottom

-"mainscreen__form__button" display, font-size, line-height, text-decoration, background-color, color, font-weight, border, border-radius, box-sizing, padding, cursor, text-transform, -webkit-box-align, align-items, font-family

-"mainscreen__img"-webkit-box-align, align-items, box-shadow, box-sizing,  display, flex-direction, -webkit-box-flex, height, -webkit-box-pack, justify-content, max-height, max-weight, width, z-index, position, flex,  margin, padding

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

- "place1": color,text-align,max-width,line-height,font-size,font-family,white-space,word-break,fontweight,fontstyle,verticalalign,text,decoration,boxsizing.
