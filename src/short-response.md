Short Response Questions
========================

Answer the following questions in 2-4 sentences each. Be specific and use vocabulary from the lessons.

Question 1: Flexbox Basics
--------------------------

What is the difference between a **flex container** and a **flex item**? How do you make an element a flex container?

**Your Answer:**

The difference between a flex container and a flex item is that a flex item is an element inside of a flex container. You make an element a flex container by setting its `display` property to `flex`.

Question 2: Main Axis vs Cross Axis
-----------------------------------

In Flexbox, what is the **main axis** and what is the **cross axis**? How do `justify-content` and `align-items` work with these axes?

**Your Answer:**

In Flexbox, the main axis is the direction that flex items flow in. The cross axis is the direction perpendicular to it. `justify-content` sets the spacing along the main axis, while `align-items` determines the alignment of items on the cross axis.

Question 3: Flexbox vs Grid
---------------------------

When would you use **Flexbox** vs **CSS Grid**? Give an example of a layout that would be better suited for each.

**Your Answer:**

You would use CSS Flexbox if you were trying to make a page that only requires a single row/column layout (Example: Marcy Gitbook). CSS Grid would be used if you needed a layout that required multiple rows/columns (Example: Slack).

Question 4: The `fr` Unit
-------------------------

What does the `fr` unit do in CSS Grid? Explain what `grid-template-columns: 1fr 2fr 1fr` would create.

**Your Answer:**

The `fr` unit in CSS grid is a fractional unit and it determines how much space in a grid container grid items are going to take. `grid-template-columns: 1fr 2fr 1fr` would create 3 columns with the middle column taking up `2fr` of the space.

Question 5: Media Queries
-------------------------

What is a **media query** and why are they important for **responsive web design**? Write an example of a media query that applies styles for screens 768px and wider.

**Your Answer:**

A media query allows developers to set CSS rules to be applied based on a device's screen size. This allows the developer to create websites that adapt their layout and content to different devices, therefore practicing responsive web design.

    @media (min-width: 768px) {
      .picture-grid > ul {
        grid-template-columns: repeat(2, 1fr);
      }
    
      #profile-pic {
        flex-direction: row;
      }
    
      .profile {
        flex-direction: row;
        margin: auto;
      }
    
      .profile > figure > p {
        flex-direction: row;
      }
    }

Question 6: Mobile-First Design
-------------------------------

What does **mobile-first design** mean? What are the benefits of taking a mobile-first approach versus a desktop-first approach?

**Your Answer:**

Mobile-first design means that you start designing an app's layout for mobile devices first, then scale the layout for bigger screens. The benefits of this approach are more efficient and user-friendly layouts.