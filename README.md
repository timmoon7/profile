# Tim Moon's portfolio website
- Live at https://timmoon.netlify.com/

## Inspiration
 - [Pinterest board](https://www.pinterest.com.au/timmoon7/profile/)
 - [Figma design process](https://www.figma.com/file/GYrWtTlwfKlj7BBjGMvcdXbh/MyProfile)

## STYLE DEVELOPMENT AND GUIDE
### Layout
The layout is based on the cover design of D3cubed. The site layout is minimalist and spacious. Sections are horizontal and cover 100% of the page width. Mainly it is implemented with a Flexbox and media query. It has a header for logo and menu, the menu has mobile and desktop views. The mobile screen shows menu icon and vertical menus based on with menu toggle funtion. And then it has a wrapper, section, 5 articles and footer.

![D3cubed](http://demos.q-themes.net/dcubed/v1.1/#home "D3cubed, web design company")

### Colours
The colour scheme is from a page of 'realtor-website-launch-kiley-mondloch' with dark blue, cream and brown and pictured on the [realtor-website-launch-kiley-mondloch](https://www.pinterest.com.au/pin/791648440723495868/).

![A page from The Realtor Website Launch :: Kiley Mondloch] (http://saffronavenue.com/blog/logo-branding/realtor-website-launch-kiley-mondloch/ "Realtor Website Launch :: Kiley Mondloch")

 - Background 'body' light-grey: #EBE8E0
 - Navigation bars dark blue: #2C3B48
 - articles cream: #EFEEEC
 - Footer brown: #66503D
 - Text 'print' dark blue, black and cream: #000, #2C3B48 and #EFEEEC
 - a:hover light navy: #616C75

![Site colour theme](https://github.com/timmoon7/profile/tree/master/assets/img/colors.png)

### Fonts
 - Google Fonts: Exo 2, Roboto and Roboto Condensed
 - Article headings h1: Exo 2, sans-serif 45px;
 - Article headings h2: Roboto, sans-serif 24px;
 - Input, textarea: Roboto Condensed, sans-serif 16px;
 - General text: Roboto regular

![Exo 2, Roboto and Roboto Condensed fonts](https://https://github.com/timmoon7/profile/tree/master/assets/img/fonts.png)
 
### Images
Images are kept to a minimum and those that are present are mostly logo and icons. IN the absense of images, the spacious page layout and alternating background colours serve to break up the text.

### Logo
Made a simple logo which can be a representative of me. The 0 1 shell shape means a programmer and TM stands for my full name Tim Moon. To turn it into a logo I created it in Figma and changed the 0 1 colors based on the background color of heading. Then I gave it my initial on the right top corner.

Original sketch:

Final logo:

![My logo](https://https://github.com/timmoon7/profile/tree/master/assets/img/colors.png)

In keeping with the minimalist theme and to avoid "cartoonifying" the clean layout, the logo is only used once,in the header (left corner).

### Views
Pages should always load with the main header which is fixed.

For the mobile view, it will show menu icon on the top-right corner, and when it is clicked it will
show you vertial menus, it will be disappeared when clicked again like a toogle key.

On small screens On scrolling down the page, the main header is covered by the body and a smaller right justified header appears. This is not strictly necessary as people aren't likely to forget what page they're on. It also means logo and memu icon is always visible.

![site on a narrow screen - mobile](https://github.com/timmoon7/profile/tree/master/assets/img/mobile.png)

On screens wider than 768px this makes the big header overwhelming so it is converted to a smaller header with a nav bar. The bottom vertical menu bar is not shown. When clicking the menu icon, the vertical full menus will be appeared and disappeared when clicking again like a toogle key. 

![site on a wide screen - desktop](https://github.com/timmoon7/profile/tree/master/assets/img/mobile.png)

Sections are set to view height and are delineated by alternating background colour. Top paddings are set to avoid overlap with fixed headers. Vertical alignment is always centered in the flexbox.

On small screens the section content has alternating justification (right then left). On larger screens all content reaches max width and is centered.  

# Plan and Desgin
![Design from Figma](https://https://github.com/timmoon7/profile/tree/master/assets/img/figma.png)
