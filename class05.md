# Welcome to reading notes code 201 class 5:
## Adding Images to a webpage.
## How we can address an image to html file?
![image format](https://ignitiondrawing.files.wordpress.com/2018/05/jpg-png-gif.gif?w=379)
- We can use < img > tag –which we call it empty tag as it does not have closing tag- with:
   - src attribute : the value for this attribute can be relative URL or absolute depending where the picture is, locally or on the web.
   - alt attribute: this attribute hold text value to show for the user in case the link did not work.
   - title attribute: also this attribute hold text value to provide additional information about the image.
   - width and height attribute controls the size of the image.

## What to consider when you add the image to the page?
 - You need to make sure to save it in the:
1- Right Format (there are common three formats JPEG, GIF, PNG).
2-Right Size (The images you use on your website should be saved at the same width and height that you want them to appear on the page).
3-Correct resolution.


**What is the best format to use?**
- Actually it depends on specific use cases:
1- Use **JPEG** format for all images that contain a natural scene or photograph where variation in colour and intensity is smooth. 
2-Use **PNG** format for any image that needs transparency or for images with text & objects with sharp contrast edges like logos. 
3-Use **GIF** format for images that contain animations.

## Can I add a caption with my photo ?
- Yes using an attribute called figcaption.
> < figcaption> *here we put the caption you want*< /figcaption

## Let’s talk about Colors and its role in styling webpages. 

![colorspicture](https://upserve.com/media/sites/2/bigstock-Opened-paint-buckets-with-vari-17866592.jpg) 

## Why do we need colors for webpages?!
 - Color brings website to life, also helps make it more appealing which could trigger more user reactions.
## How Colors are generated?!
 - Every color on a computer screen is created by mixing amounts of red, green, and blue.
## How can we select Colors?!
 - To find the color you want, you can use a color picker.
 - There are three ways to specify colors in CSS:
    - RGB values.
    - Hex codes. 
    - Color names.
    - HSL colors.

### RGB values:
- It represent values for Red, Green, and Blue, which are expressed as numbers between 0 and 255.
    - Example : rgb(102,205,170)This color is made up of the following values:102 red,205 green,170 blue.

### Hex codes:
 - Hex values represent values for red, green, and blue in hexadecimal code.
 - **Example**: #66cdaa,The value of the red, 102, is expressed as 66 in hexadecimal code. The 205 of the green is expressed as cd and the 170 of the blue equates to aa.

### Color names:
- Colors are represented by predefined names. There are 147 color names supported by browsers.

### HSL colors:
- HSL indicates for hue, saturation, and lightness values. 
- Hue is often represented as a color circle where the angle represents the color (between 0 and 360 degrees).
- Saturation is the amount of gray in a color.
- Lightness is the amount of white (lightness) or black (darkness) in a color.

## Now, let’s move to another important topic which is styling Text: 

- First let me explain to you an important concept which is, **typeface**.

- We can define it as the design of lettering that can include variations, such as extra bold, bold, regular, light, italic, condensed, extended, etc. Each of these variations of the typeface is a font. 

### There are some terminology you need to be familiar with:

+ **Serif** : serif fonts have extra details on the ends of the main strokes of the letters. 
+ **Monospace**: every letter in a monospace font is the same width.
+ **Fantasy**: fantasy fonts are usually decorative fonts and are often used for titles. 
+ **Font Weight** : which gives options from light –Medium-Bold-Black.
+ **Font style**: which gives options from italic-normal-oblique.
+ **Font Stretch**: the stretch meaning that how much the letters are thinner and closer together, which gives options from condensed –regular-extended. 

- There are many properties to control the appearance and style of the text , I will mention most of them below:
 
1- **font-family property**: The value of this property is the name of the typeface you want to use.
2- **font-size property**: The value of this property is the size of your font, which you can specify it in percentages or pixels. 
  - The default size of text in a browser is 16 pixels. So if you use percentages or ems, you calculate the size of text you want based on the default size of the text used in browsers.

3-**@font-face**: -Sure thing to take into consideration while choosing a typeface,
       > it is important to understand that a browser will **only display type face if it is installed on that user's computer**.
  - So if you want to use a font, even if it is not installed on the computer of the person browsing, what to do? You can use the font-face.
     - It holds two values : *font-family* the name of the font you want to use, and *src* to specifies the path to the font.

4-**text-transform** property: this property have the following values:
    -lowercase, uppercase and capitalize (his causes the first letter of each word to appear capitalized).
5-**text-align** property: this property allows you to control the alignment of text, which has the following values, left ,right ,center, and justify(his indicates that every line in a paragraph, except the last line, should be set to take up the full width of the containing box).

- There are many more property but I have mentioned the most common ones.

### There are attribute selectors that allow you to create rules that apply to elements that have an attribute with a specific value. I will mention some below: 
- *Existence selector* ,[]:
  >For example : 
  >p[ class] will Targets any <p> element with an attribute called class.
- *Suffix selector* , [ $=]:
  >For example:
  >p[ attr$”o”]
  >argets any <p> element with an attribute whose value ends with the letter "o".
