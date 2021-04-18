# Welcome to reading notes code 201 class 11:
 
## OUR First Topic is Images , how to control their dimensions and setting them as background.

![image bakcground](https://wpastra.com/wp-content/uploads/2021/04/set-website-background-image.png)

### Let’s make a quick recap, How to insert an image in html?
- By using <  img src=’’ > img tag with the link of the image in src attribute.

### How to control the dimensions of an image ?
- By using **width and height** properties in css.
- Also, you can add margins in order to keep the image away from other elements.

### How to align images next to each other:
- The most common way recently is to use the **float** property in css.

### How to place an image as center?
- We can set the display of the image to be block, as they are by default inline elements , and then either you center the container element of the image or giving the margin auto value.

### How to set an image as a background ?
- We can use the **background-image** property for the box /element that we want to set the image to be behind it.
- Also we add to its value which will be **url()** the link inside quotation inside the parentheses.

### Are my images will be displayed as the full size of the box?
- No, the default for background image is to be repeated both *horizontally and vertically* until it fill the entire box, so the value will be **repeat**.

### What to do in order not to repeat them?
- If we want the image to take the full size of the box without being repeated we use the **background-repeat** property and setting their value to be **no-repeat** .
- Also, we can set the value of this property to be **repeat-x**in order to repeat it only from the horizontal side or **repeat-y** if we want them to be repeated from the vertical side.

### Is there a shortcut for all these properties, like placing them in one property?
- Yes, sure by placing the properties in the following order:
 1- background-color 
 2- background-image 
 3- background-repeat 
 4- background-attachment 
 5- background-position.

### What if I want to place text on a background image ?
- You can do that but the image must be low contrast in order for the text to be legible.
- So, you can place a semi-transparent background color for it.

## Now, let’s talk about an interesting topic which is how to make your website a successful one.

- I will give you some pointers for what you need to be considering:
#### Search Engine Optimization (SEO):

- This is about helping your site to appear nearer the top of search engine results when people look for the topics that your website covers.
- It has some concepts to be aware of:
- **On-Page seo**: in every page of your website there are *seven* key places where keywords, which are the words people might search on to find your site, can appear.

1- **Page Title**; which is the content we place inside the title tag in html.

2- **URL / Web Address**

3-**Headings**

4-**Text**

5-**Link Text**: use keywords in the text that create links between pages.

6-**Image Alt Text**

7-**Page Descriptions**: the description also lives inside the title element and is specified using a tag.

### Google Analytics:
- It’s one of the best tools for you can use to start learning about your visitors and start analyzing how they found it, what they were looking at and at what point they are leaving.
- The informations which this tool can give you is a lot but we can summarize most of them as following; 

- **How many visitors are visiting your page**:
 - The following section for where this information locate in google analytics;
  - **Visits**
  - **Unique Visits**
  - **Page Views**
  - **Pages per Visit**


- **What they are looking at?**
- The following section for where this information locate in google analytics;
  - **Pages**
  - **Landing Pages**
  - **Top Exit Pages**
  - **Bounce Rate**


### As an important step of launching your website on the web, you will need to obtain a **domain name** and **web hosting**.
