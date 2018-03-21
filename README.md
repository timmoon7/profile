# Tim Moon's portfolio website
- Live at https://timmoon.netlify.com/

## Inspiration
 - [Pinterest board](https://www.pinterest.com.au/timmoon7/profile/)
 - [Figma design process](https://www.figma.com/file/GYrWtTlwfKlj7BBjGMvcdXbh/MyProfile)

---
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

![Site colour theme](https://github.com/timmoon7/profile/tree/master/assets/img/colors.png "Site colour theme")

### Fonts
 - Google Fonts: Exo 2, Roboto and Roboto Condensed
 - Article headings h1: Exo 2, sans-serif 45px;
 - Article headings h2: Roboto, sans-serif 24px;
 - Input, textarea: Roboto Condensed, sans-serif 16px;
 - General text: Roboto regular

![Exo 2, Roboto and Roboto Condensed fonts](https://https://github.com/timmoon7/profile/tree/master/assets/img/colors.png "Exo 2, Roboto and Roboto Condensed fonts")
 
### Images
Like a book or a Penguin Classic cover, images are kept to a minimum and those that are present are mostly logos. Monochrome logos that match the dark grey text colour are preferred. IN the absense of images, the spacious page layout and alternating background colours serve to break up the text.

### Logo
Penguin has a penguin. Conveniently, my usual avatar is also a bird - a cartoon sketch I did of our pet chicken, Pirate Chicken. This also reflects my personality (animals etc). To turn it into a logo I created paths in Photoshop and stroked them with a tapered brush. Then I gave it a black circle background.

Original sketch:

![Pirate Chicken sketch](https://github.com/Simbidion/portfolio-website/blob/master/assets/img/piratechicken-sketch.jpg?raw=true "Pirate Chicken sketch")

Sketch converted to paths and stroked:

![Pirate Chicken stroke](https://github.com/Simbidion/portfolio-website/blob/master/assets/img/piratechicken-stroke.png?raw=true "Pirate Chicken stroke")

Final logo:

![Pirate Chicken logo](https://github.com/Simbidion/portfolio-website/blob/master/assets/img/pirateroundtrans.png?raw=true "Pirate Chicken logo")

In keeping with the minimalist theme and to avoid "cartoonifying" the clean layout, the logo is only used once, in the footer.

### Views
Pages should always load with the main header and the intro fitted to the screen.

On small screens (where width is generally less than height and therefore more book-shaped) 50% of the page is the big-header and 50% the intro text. On scrolling down the page, the main header is covered by the body and a smaller right justified header appears. This is not strictly necessary as people aren't likely to forget what page they're on, but it is reminiscent of where author might appear in the header of a printed page. It also means my name is always visible.

![site on a narrow screen](https://github.com/Simbidion/portfolio-website/blob/master/assets/img/narrow-shot.png?raw=true "site on a narrow screen")

On screens wider than 768px this makes the big header overwhelming so it is converted to a smaller header with a nav bar. The bottom av bar is not shown. It has a lower yellow highlight border consistent with the small header bar that shows after scrolling down on narrower screens. (This makes the small header redundant on wider screens so it is not shown.) The rest of the screen is taken up with the intro text and this time the Linked In etc links show.

![site on a wide screen](https://github.com/Simbidion/portfolio-website/blob/master/assets/img/wide-shot.png?raw=true "site on a wide screen")

Sections are set to view height and are delineated by alternating background colour. Top paddings are set to avoid overlap with fixed headers. Vertical alignment is always centered in the flexbox.

On small screens the section content has alternating justification (right then left). On larger screens all content reaches max width and is centered.  