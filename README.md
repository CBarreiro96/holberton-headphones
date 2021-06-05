<div align="center"><img src="https://user-images.githubusercontent.com/66263776/98416555-43fa9b80-204d-11eb-800a-df8e19b62655.jpg" width="700" height= "200"> </div>

# <div align="center"><img src="https://user-images.githubusercontent.com/66263776/98705433-b6b88f00-234b-11eb-97b7-cb193f7424f4.png" width="20" height= "30"> holberton-headphones <img src="https://user-images.githubusercontent.com/66263776/98705433-b6b88f00-234b-11eb-97b7-cb193f7424f4.png" width="20" height= "30"></div>

## :orange_book: Expected to Look at this Concept

This web page was coded from scratch based on some design models given on [Figma](https://www.figma.com/file/gkWRcFqkwtruWZgSfnnHF0/Holberton-School---Headphone-company)

The designs were planned for Desktop, Tablet, and Mobile, so the web page was implemented with responsiveness to different device sizes.

<div align="center">
    <table>
        <tr align="center">
            <td> <b>Desktop (Width: 1400 px)</b>  </td>
            <td> <b>Tablet (Width: 760 px)</b> </td>
            <td> <b>Mobile (Width: 480 px)</b> </td>
        <tr>
        <tr align="center">
            <td>
                <img src="https://camo.githubusercontent.com/3ce2a43acc1b973359af75e49770aeb63ccee5d3feecd636b53fc39811ef401c/68747470733a2f2f692e6962622e636f2f3172346b3057432f30312d6865616470686f6e65732d6465736b746f702d32782e706e67" height="646">
            </td>
            <td>
                <img src="https://camo.githubusercontent.com/d2cb11b5e486418b7b1acf51a329a130b2f07442316d1ee3ad204fe93f11e1e0/68747470733a2f2f692e6962622e636f2f593246664836772f30322d6865616470686f6e65732d7461626c65742d32782e706e67">
            </td>
            <td>
                <img src="https://camo.githubusercontent.com/616990609d12d078dac068c7ba678dc9ca315410e7af04dae5c03d1a23be2a6c/68747470733a2f2f692e6962622e636f2f73317a78354e532f30332d6865616470686f6e65732d6d6f62696c652d32782e706e67">
            </td>
        </tr>
    </table>
</div>



## Requirements

- you are not allowed to import external CSS framework (like Bootstrap)
- you are not to use Javascript

## :books: Tasks

**0. Read and be familiar with Figma**

Create an account in Figma and open this project and �Duplicate to your Drafts� to have access to all design details.

If you can�t access to it, please find here the [Figma file](https://www.figma.com/file/gkWRcFqkwtruWZgSfnnHF0/Holberton-School---Headphone-company?node-id=0%3A2)

![](Tasks/images/pic1.png)

Important notes with Figma:

- if your computer doesn�t have missing fonts, you can find them here: [source-sans-pro](https://www.fontsquirrel.com/fonts/source-sans-pro) and [Spin-Cycle-OT](https://www.fontsquirrel.com/fonts/Spin-Cycle-OT)
- some values are in float - feel free to round them

For this task, please write an amazing README.md

### Interactions note:

- the web page must switch to the mobile version when the screen width is 480px or less
- links hover/active: #FF6565
- button hover/active: opacity: 0.9
- max width of the content: 1000px centered in the page


**1. Header**

Files: [0-index.html](Tasks/0-index.html/) - [0-styles.css](Tasks/0-styles.css/)

Building a web page the right way, is not easy - expect if you put in place strong foundations:

- reset CSS styling
- use variables
- simple/�as generic as you can� CSS selectors
- avoid as more as you can super specific CSS selector
- simple HTML structure - div containers are your friend!

Last advice: I always start to build a web page from outside to inside and from top to bottom.

Now, your turn!

For this first task: create the header/hero piece

Here an archive of all assets needed: [images_0x09.zip](https://intranet.hbtn.io/rltoken/6AnXuu5fO78UpPRvkBX3cw)

### Desktop

![](Tasks/images/headerD.gif)


### Mobile

![](Tasks/images/headerM.gif)


**2. "What we do..." section**

Files: [1-index.html](Tasks/1-index.html/) - [1-styles.css](Tasks/1-styles.css/)

Copy files from the previous task.

For this second task: create the �What we do�� section

In this section, you will need custom font icons. Here the archive of it: [holberton_school-icon.zip](https://intranet.hbtn.io/rltoken/UTLmru8XUpDXW2EbLdLyew) Inside you will find demo page of how to use it.

Important: try to build as generic as you can� you will probably need some components in next section.


**3. "Our results" section**

Files: [2-index.html](Tasks/2-index.html/) - [2-styles.css](Tasks/2-styles.css/)

Copy files from the previous task.

For this third task: create the �Our results� section

Now you can reuse components form the previous task!


**4. Contact us**

Files: [3-index.html](Tasks/3-index.html/) - [3-styles.css](Tasks/3-styles.css/)

Copy files from the previous task.

A good landing page has always a contact form.

You are free to add any animations and/or constraints on fields.


**5. Footer**

Files: [4-index.html](Tasks/4-index.html/) - [4-styles.css](Tasks/4-styles.css/)

Copy files from the previous task.

Last piece of the page� the Footer!

When you are done, here the result:

### Desktop:

![](Tasks/images/footerD.gif)

### Mobile:

![](Tasks/images/footerM.gif)


And you are done!

Good job!


**6. Replace image by... code!**

Files: [100-index.html](Tasks/100-index.html/) - [100-styles.css](Tasks/100-styles.css/)

In the section �Our results�, replace item background image by HTML and CSS only!�


**7. Let's animate items**

Files: [101-index.html](Tasks/101-index.html/) - [101-styles.css](Tasks/101-styles.css/)

From 4-index.html and 4-styles.css, add fun animations to �What we do�� and �Our results� sections items row. Either all the time, either when hover.

Scaling, opacity, rotation, bouncing� many options!


**8. And SASS??**

Files: [102-styles.css](Tasks/102-styles.css/)

Take your 101-styles.css file and create a 102-styles.scss that will be the SASS version of it.

```sh
$ sass 102-styles.scss > 101-styles.css
```