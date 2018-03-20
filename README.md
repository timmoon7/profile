# Tim Moon's portfolio website
- Live at https://timmoon.netlify.com/

## Inspiration
 - [Pinterest board](https://www.pinterest.com.au/timmoon7/profile/)
 - [Figma design process](https://www.figma.com/file/GYrWtTlwfKlj7BBjGMvcdXbh/MyProfile)

---
## STYLE DEVELOPMENT AND GUIDE
### Layout
The layout is based on the cover design of D3cubed. The site layout is minimalist and spacious. Sections are horizontal and cover 100% of the page width. There are no borders, but instead sections are demarcated by a change in the background colour.

![D3cubed](http://demos.q-themes.net/dcubed/v1.1/#home "D3cubed, web design company")

### Colours
The colour scheme is from a page of 'The Tragical Death of an Apple Pye', printed in the 1800s and pictured on the [blog of Angela Voulangas](https://www.pinterest.com.au/pin/791648440723495868/).

![A page from The Tragical Death of an Apple Pye](http://1.bp.blogspot.com/-5hzM91_tqfA/T2ZCOZUSDNI/AAAAAAAAFNI/-FtBJ0h9VQ0/s400/apple+pie.jpg "The Tragical Death of an Apple Pye")

 - Background 'paper' yellow-y: #F2E4BD
 - Background alt light teal: #BACDA8
 - Text 'print' dark grey: #4B4B4B (may be darkened slightly for contrast against some colors)
 - Highlight red: #750417
 - Highlight teal: #528F7D
 - Highlight yellow: #ECBE69

![Site colour theme](https://github.com/Simbidion/portfolio-website/blob/master/assets/img/colours.png?raw=true "Site colour theme")

### Fonts
With the bookish theme, it was tempting to go heavy on the serif fonts, however these conflicted with the very clean layout. Instead I paired two full sans serif fonts. The wide loops in these fonts combined with the use of capitals, semi-bold and generous spacing meant that these two fonts retained the bookish feel while keeping clean and simple. Penguin Classics also use sans serif fonts.

 - Headings: Montserrat semi-bold (weight 600), usually capital
 - General text: Raleway regular

![Montserrat and Raleway fonts](https://github.com/Simbidion/portfolio-website/blob/master/assets/img/fonts.png?raw=true "Montserrat and Raleway fonts")
 
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