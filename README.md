# CSS Layout

-  Positioning the element in CSS

1. Flexbox
2. Grid

-  We are going to learn by cloning websites.

# Table of Contents

-  [Table of Contents](#table-of-contents)
   -  [Flexbox](#1.1-Flexbox)

# Requirement

1. VSC or text editors
2. Brave Browser or Chrome Browser.
3. Node.JS

# 1.1 Flexbox

-  "display: block": is a long rectangular block that prohibits other elements from coming in.
-  "display: inline": You put all the elements in the same line next to each other. However, by default, there will be spaces between them.
-  Before, we used to put boxes inline and move each box by giving margins. (ex. nth-child(3){margin-left: 20px})
-  This became an old method because people started accessing the web using different devices (screensizes vary).
-

## 1.1a Rule 1

-  If you want to move anything, you need to create a **flexbox-container**.
-  In order to make the flex-box, you use below:

```
display: flex;
```

-  If you make the parent element into a flex-container, the children will be changed to flexboxes.
-  Flexboxes are not seperated by spaces as inline.

## 1.1b Main Axis and Cross Axis

-  **justify-content** modifies the position of flex children on the horiontal axis.
-  Options:

   -  center
   -  space-between
   -  space-around

-  row - main axis - horizontal - Use justify-content
-  column - y axis - vertical - Use align-items
   -  flex-start
   -  flext-end
-  Once the position is set, you can adjust the height as below:

```
height: 100vh;
```
