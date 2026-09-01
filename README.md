# RANG <small>`pre-alpha`</small>
Rang is a UI library with that contains ready-to-use & pre-made components, utility classes and more to design systems fast and systematically.
 
I made this library for projects here in iotaStudio. However, it is open source and anyone can install it with:

---
## Installation
To install Rang, open terminal and enter,   
*_Not available yet_

```bash
npm install rang
```
However, if you want to include style but not script or vice-versa, run these command instead,

for CSS only installation,
```bash
npm install rang/css
```
for JS only installation,
```bash
npm install rang/js
```
After that simply import/link the files.
```html
<link rel="stylesheet" href="rang/index.css">

<script type="module" src="rang/index.js"></script>
```
or
```js
import "rang/css";
import "rang/js";
```
Other APIs from rang will have to be imported seprately.

---
## #Changelog
I had so much work done but unfotunately, I forgot to push before I switch to linux and all the progress were wiped..

---
## Features
As of `pre-alpha`, Rang has many features, below is a quick overview of them along with links to their documentation;
### Components
1. Form
    1. Buttons
    0. Input
        1. Field
        2. Fieldset
    0. Meter
        1. Progress
        0. Range
    0. Select
        1. Dropdown
        0. Selector
    0. Toggle
        1. Radio
        0. Checkbox
        0. SWitch
0. Notification
    1. Alertbox
    0. Modal
    0. Snackbar
0. Navigation
    1. Navbar
    0. Sidebar
    0. Navigator
    0. Tab
    0. Breadcrumb
    0. Pagination
    0. Context
    0. Footer
0. Layout
    1. Display
        1. Grid
        0. Flex
    0. Wraps
        1. Container
        0. Wrapper
        0. Title
        0. Content
    0. Solid
        1. Block
        0. Card
        0. Code
### Utitlity
1. Visibility
    1. Show     
        `.open`
        `.show`
        `.visible`
        `.show._root-hov`
        `.show._root-act`
        `.show._parent-hov`
        `.show._parent-act`
    0. Hide     
        `.hide`
        `.close`
        `.hidden`
        `.invisible`
        `.hide._root-hov`
        `.hide._root-act`
        `.hide._parent-hov`
        `.hide._parent-act`
    0. Opacity  
        `.o-0`
        `.o-1`
        `.0-0-5`
        `.o-1._root-act`
        `.o-1._root-act`
        `.0-0._parent-hov`
        `.o-1._parent-act`

0. Spacing
    1. Padding  
        `.p-a`
        `.p-0`
        `.p-10`
        `.px-1`
        `.py-1`
        `.pt-1`
        `.pl-1`
        `.pb-1`
        `.pr-1`

    0. Margin  
        `.m-a`
        `.m-0`
        `.m-10`
        `.mx-1`
        `.my-1`
        `.mt-1`
        `.ml-1`
        `.mb-1`
        `.mr-1`

    0. Gap  
        `.g-a`
        `.g-0`
        `.g-10`
        `.gx-1`
        `.gy-1`
        `.gt-1`
        `.gl-1`
        `.gb-1`
        `.gr-1`
        
    0. Line Height  
        `.l-a`
        `.l-0`
        `.l-10`
        `.lx-1`
        `.ly-1`
        `.lt-1`
        `.ll-1`
        `.lb-1`
        `.lr-1`

    0. Letter Spacing  
        `.t-a`
        `.t-0`
        `.t-10`
        `.tx-1`
        `.ty-1`
        `.tt-1`
        `.tl-1`
        `.tb-1`
        `.tr-1`

0. Transforming
    1. Width  
        `.w-a`
        `.w-f`
        `.w-50per`
        `.w-100per`
        `.w-0`
        `.w-mbl`
        `.w-lap`
        `.w-com`
        `.w-mbl`
        `.wn-lap`
        `.wn-com`
        `.wx-mbl`
        `.wx-lap`
        `.wx-com`
        
    0. Height  
        `.h-a`
        `.h-f`
        `.h-50per`
        `.h-100per`
        `.h-0`
        `.h-10`
    0. Aspect Ratio  
        `.ar-16-9`
        `.ar-1-1`
        `.ar-4-6`

    0. Scale    
        `.s-0-1`
        `.s-0-5`
        `.s-1`
        `.s-10`
        `.sx-0-1`
        `.sx-0-5`
        `.sx-1`
        `.sx-10`
        `.sy-0-1`
        `.sy-0-5`
        `.sy-1`
        `.sy-10`

    0. Font Size    
        `.fs-0-1`
        `.fs-0-5`
        `.fs-1`
        `.fs-10`

    0. Rotate    
        `.r-0-1`
        `.r-0-5`
        `.r-1`
        `.r-10`

0. Typography
    1. Label    
        `strong.label`
        `small.label`
        `i.label`

    0. Info   
        `strong.info`
        `small.info`
        `i.info`

    0. Icon     
        `i.icon`
        `svg.icon`
        `img.icon`

    0. Image
        `.logo`
        `.banner`
        `.avatar`
        `.hero`

0. Border
    1. Border Radius   
        `.bdr-rad-rnd`
        `.bdr-rad-cir`
        `.bdr-rad-sqr`

    0. Border Color     
        `.bdr-clr-bgd`
        `.bdr-clr-bgd-hov`
        `.bdr-clr-bgd-act`
        `.bdr-clr-mid`
        `.bdr-clr-mid-hov`
        `.bdr-clr-mid-act`
        `.bdr-clr-pim`
        `.bdr-clr-pim-hov`
        `.bdr-clr-pim-act`

```css
/*
Intenally, it sets the whole border; Not just the color!
*/

.class{
    border: var(--bdr-thk) solid var(--bdr-clr);
}
```

### Core
1. Reset
0. Imports
0. Base

### Variables
1. Transform
    1. --space  
        `--space-0`
        `--space-10`

    0. --size   
        `--size-0`
        `--size-10`

0. Colors
    1. --clr-fill   
        `--clr-bgd`
        `--clr-h-bgd`
        `--clr-s-bgd`
        `--clr-l-bgd`
        `--clr-bgd-hov`
        `--clr-bgd-act`
        `--clr-mid`
        `--clr-h-mid`
        `--clr-s-mid`
        `--clr-l-mid`
        `--clr-mid-hov`
        `--clr-mid-act`

    0. --clr-brand  
        `--clr-pim`
        `--clr-acc`
        `--clr-wrn`
        `--clr-h-pim`
        `--clr-s-pim`
        `--clr-l-pim`
        `--clr-err`

    0. --clr-text   
        `--clr-lab`
        `--clr-inf`
        `--clr-ico`
        `--clr-h-lab`
        `--clr-s-lab`
        `--clr-l-lab`

0. --bdr   
    `--bdr-rad`
    `--bdr-thk`