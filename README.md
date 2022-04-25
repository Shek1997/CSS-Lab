# CSS-Lab
* {
    box-sizing: border-box;
}

body {
    background-color: #e0e4e9;
    /* 2. change the body text to Lora 400.
        don't forget to add the font to your HTML! */
        font-family: Lora 400;
        
}

a {
    color: #AB440D;
}

main {
    max-width: 1024px;
    margin: 2rem auto;
    overflow: hidden;
    /* 3. give the main element 2rem rounded corners */
    
    /* 4. give the main element a box shadow with
  
        - 0 pixels horizontal offset
        - 4 pixels vertical offset
        - 4 pixels blur radius
        - 2 pixels spread radius
        - use the color rgba(0,23,85,.3) */
        
}

h1 {
    margin: 0;
    padding: 1rem 0 .5rem;
    text-align: center;
    line-height: 1.1;
    /* 5. change the h1 text to Comfortaa 700, make the 
        font size 3.5rem, and make the text white */
    font-family: Comfortaa 700;
    /* 6. transform the text so every letter is capitalized */
    /* 7. apply a linear gradient to the background
  
        - #41589b at the top
        - #11286b at the bottom */
}

#quote {
    /* 8. set the padding of #quote to 30% at the 
        top and bottom, zero on the left and right */

            padding-top: 30%;
            padding-bottom: 30%;
            padding-right: 0;
    padding-left: 0;
    /* 9. set the background image to florian-wehde-nyc-skyline.jpg
  
        - set the background-position to center
        - set the background-size to cover
        - set the background color to #EE6920 */
background-image: url(florian-wehde-nyc-skyline.jpg);
position: center;
size:cover;
background-color: #EE6920;
    /* 10. set the background blend mode to luminosity */
    background-blend-mode: luminosity;
}

blockquote {
    padding: 1rem;
    width: 70%;
    margin: 0 auto;
    background-color: rgba(0, 23, 85, .8);
    color: #fff;
    font-size: 1.5rem;
}

footer {
    text-align: center;
}
