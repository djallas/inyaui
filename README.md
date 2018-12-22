# Inyarwanda UI Framework

## How to use UI Framework?
To get started, you must call your css file in your html page
```
<link rel="stylesheet" href="css/inyaui.1.0.0.css">
```

### Font family used: 

Paragraphs: exo
Heading: Krub


## 1. helpers

Wrap element with max width of 1280px
`.container`

Hide element
`.hide`

Hide element on large screen
`.hide-on-large`

Hide element on medium screen
`.hide-on-medium`

Hide element on small screen
`.hide-on-small`

### Border

Initiate border
`.border`

### Border color
White
`.b-lite`

Grey
`.b-grey`

Red
`.b-red`

Black
`.b-red`

Indigo
`.b-indigo`


### Clearfix
`.clear`
```
<div class="clear"></div>
```


#### Aligment

Center
`.center-align`

Left
`.left-align`

Right
`.right-align`


## 2. Playing with Padding

**-h-** indicate that the property is applied horizontally on a given selector

**-v-** indicate that the property is applied veritically on a given selector

Small padding

`.s-padding`
`.s-h-padding`
`.s-v-padding`

Medium padding

`.m-padding`
`.m-h-padding`
`.m-v-padding`

Large padding

`.l-padding`
`.l-h-padding`
`.l-v-padding`

Extra large padding

`.xl-padding`
`.xl-h-padding`
`.xl-v-padding`

Extra large padding

`.xxl-padding`
`.xxl-h-padding`
`.xxl-v-padding`

## 3. Playing with Margin

**-h-** indicate that the property is applied horizontally on a given selector

**-v-** indicate that the property is applied veritically on a given selector

Small margin

`.s-margin`
`.s-h-margin`
`.s-v-margin`

Medium margin
`.m-margin`
`.m-h-margin`
`.m-v-margin`

Large padding
`.l-margin`
`.l-h-margin`
`.l-v-margin`

Extra large padding
`.xl-margin`
`.xl-h-margin`
`.xl-v-margin`

Extra large padding
`.xxl-margin`
`.xxl-h-margin`
`.xxl-v-margin`

## 4. Typography

Small text
`.s-text`

Medium text
`.m-text`

Large text
`.l-text`

Extra large text
`.xl-text`

Extra-extra large text
`.xxl-text`


## 5. grid

Grid must be wrap in row
`.row`
```
<div class="row">
    //content
</div>
```

|  | Small  |  Medium | Large |
| ------- | --- | --- | --- |
| Prefix | `.s` | `.m` | `.l` |

## 6. Color palette

| Color | 1  |  2 | 3 |
| ------- | --- | --- | --- |
| .white | #ffffff | - | - |
| .black | #000000 | - | - |
| .grey- | #202020 | #404040 | #606060  |
| .grey- | #efefef | #dedede | #cdcdcd  |



- Add `text- ` prefix before the defined color class to apply it on text 

- `-darken-1` , `-darken-2` and `-darken-3` gives option to play with strongness of the color 

- `-lighten-1` , `-lighten-2` and `-lighten-3` gives option to play with lightness of the color 

## 7. form

Input, textarea, radio, checkbox and button must be in `.input-field` `div` or `p`

#### example
```
    <div class="input-field">
        <label for="email">Email</label>
        <input type="email" id="email" placeholder="your email">
    </div>
```

## 8. Button

Initiate button
`.btn`

```
<button class="btn">Button</button>
```

## 9. Managing Image

If your wrap to wrap image to fix the width of a container, you must add `.image` in the parent container of a image

```
<div class="image">
    <img src="images/img2.jpg" alt="Article" >
</div>
```

## 10. Header 

Example of Header

```
   <header class="black shadow-2">
         <nav>
            <a href="#" class="left l-padding hide-on-large">
               <span class="fas fa-bars xl-text text-white"></span>
            </a>
            <div class="logo left">
                  <img src="images/logo.png" alt="Logo | Inyarwanda">
            </div>
            <span class="right right-align">
                  <a href="#" class="l-padding">
                     <span class="fas fa-search xl-text text-white"></span>
                  </a>
                  <a href="#" class="l-padding">
                     <span class="fas fa-bars xl-text text-white"></span>
                  </a>
            </span>
         </nav>
   </header>
```

## 11. Card 

Example of a card

```
    <div class="card">
        <div class="image radius-2">
            <a href="#">
                <img src="placeholder.jpg" alt="Article" >
            </a>
        </div>
        <div class="card-content center-align">
            <h2>
                <a href="#">
                        Watoto Children's Choir iri kubarizwa i Kigali yatangarije abanyamakuru ibyihariye bizaranga igitaramo igiye kuhakorera-AMAFOTO
                </a>
            </h2>
            <span class="timestamp"> 1 ago </span>
        </div>
    </div>

```

# Author: 

### Gilles Kagarama

[Twitter: @kagaramag](https://www.twitter/kagaramag)

[Scotch.io: @kagarama](https://scotch.io/@gilles)
