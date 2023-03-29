# First Challenge
## Welcome to your Lesson 5 - Challenge 1
## Challenge: Breathing space, expansion and contractions

Our recipe site is really coming together now. We next need to make sure that its design and structural integrity is maintained across device sizes. Your challenge is to make your recipe page be responsive to the size of the screen that it is viewed on.

In particular, you will:

- Add an outer container that wraps around all the content of the page
- Target that container with a style that sets the container width and also centers the container
- Target that container with a media query that contains styles that are triggered once the screen size goes below a certain value


**Steps**

1. On line 13 a  **\<div\>** element that acts as the parent for all content has been created for you. Add an  **id attribute** to that  **\<div\>** element with the value of  **container**
2. Create a style rule with an id selector that targets the  **container** id
3. Inside the  **#container** rule set the **width** to **60%**
4. Inside the  **#container** rule set the **margin** to **auto**
5. Create a  **media query**  that will apply styles for  **screen** size up to a  **max-width**  of  **768px**
6. Reuse the  **#container** style rule inside the **media query** and set the **width** to **90%**
7. Reuse the  **h1** style rule inside the   **media query** and set the  **font-size** to  **200%**

**Tips**

Drag the panel separator bar to the left of this text to resize the result pane and see the media queries being triggered

If you're stuck, the  **Recipe: Media Queries ** video will give you everything you need to succeed.

Enjoy!
#
#
#
# Second Challenge
## Welcome to your Lesson 5 - Challenge 2
## Challenge: Iconography

Discerningly placed icons can draw the user's eye to important content on a site.

Your challenge is to add external font icons to your recipe.

In particular, you will:

- Place an icon within your ingredients sub-heading
- Place an icon within your preparation sub-heading

**Result**

Your result should look similar to the image below

![Shape1](RackMultipart20230329-1-yw6c2y_html_49ac0cb03196381.gif)

**Steps**

1. Copy the font awesome link and paste it into the  **head** area of your HTML  **:\<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css" type="text/css" /\>**Place it above the link to the index.css file.
2. Go To the Font Awesome website below and choose fonts from the 4.7 icon set: _ **https://fontawesome.com/v4.7.0/icons/** _
3. Add a font icon to the  **ingredients** sub-heading
4. Add a font icon to the  **preparation** sub-heading

**Tips**

If you're stuck, the  **Recipe: Awesome fonts** video will give you everything you need to succeed.

Enjoy!
#
#
#
# Third Challenge
## Welcome to your Lesson 5 Challenge 3
## Challenge: Interactions


At this point, you have all your HTML structure and CSS styling in place. Well done for getting this far! In this challenge, you will add some JavaScript interactivity to the recipe site. Interactivity can be as simple or complex as needed. Our interactivity is used to draw the user's attention to the recipe ingredients and preparation steps when moving their mouse on the page

In particular, you will:

- Trigger an event that increases the size of the ingredients Font Awesome icon when a user's mouse passes over the ingredients section
- Trigger an event that returns the ingredients Font Awesome icon to normal size when a user's mouse passes out of the ingredients section
- Trigger an event that increases the size of the preparation Font Awesome icon when a user's mouse passes over the preparation section
- Trigger an event that returns the preparation Font Awesome icon to normal size when a user's mouse passes out of the preparation section

**Result**

Your result should look similar to the image below

**Steps**

Take a look at lines  **22** and  **33**. You'll see that there are two of what are called  **event listeners** added as attributes to the ingredients and preparation  **sections**. Their job is to listen for and react to two particular  **events**. One reacts when a user's mouse passes into the section area (  **onmouseover** ) and the second reacts when a user's mouse passes out of the section (  **onmouseout** ).

When one of these events occurs the appropriate event listener calls a  **function**. For example, when the user's mouse passes into the ingredients section the  **onmouseover** event listener will call a function named **ingredientsHover()**. This is function is written by the programmer.

- You will create a function with the same name as the function referred to in the event listener.
- Inside that function, you will write the code that resizes the icon when the event happens.
- You will write  **four** functions.
- **Two** for the  **ingredients** section and  **two** for the  **preparation** section.
- A  **\<script\>** element has already been created for you. You will add your JavaScript functions within that element

**Ingredients**

- Create the function that is called when the ingredients onmouseover event is triggered. The code is shown below. Notice how the function name tries to indicate its purpose

function ingredientsHover(){

}

- Add the code that changes the ingredients icon size. This will be placed inside the function's curly braces {}. The code is shown below. Try and understand how it works. Read it from left to right. The document represents the web page

document.getElementById("ingredients").style.fontSize = "300%";

- Create the function that is called when the ingredients onmouseout event is triggered. The code is shown below

function ingredientsNormal(){

}

- Add the code that resets the ingredients icon size to its default size. This will be placed inside the function's curly braces {}. The code is shown below. Try to understand how it works.

document.getElementById("ingredients").style.fontSize = "100%";

**Preparation**

- Create the function that is called when the preparation onmouseover event is triggered. The code is shown below

function preparationHover(){

}

- Add the code that changes the preparation icon size. This will be placed inside the function's curly braces {}. The code is shown below. Try to understand how it works.

document.getElementById("preparation").style.fontSize = "300%";

- Create the function that is called when the preparation onmouseout event is triggered. The code is shown below

function preparationNormal(){

}

- Add the code that resets the preparation icon size to its default size. This will be placed inside the function's curly braces {}. The code is shown below. Try to understand how it works.

document.getElementById("preparation").style.fontSize = "100%";

**And That's it!**

Well done on completing your challenges. We hope this inspired you to explore the world of software development even further. Whatever you decide to do next, do what you love. Life is too short to do anything less.

The Code Institute Team
