# CIIC4030_PL_Project

## IDEA
 Almost every developer who has worked on a front-end project has had to work through making every small portion of the GUI wishes it could’ve been developed faster and in a less tedious manner. This programming language is intended for helping the front-end developer generate their designs and drafts of what their front-end should look like. With simple to use syntax, and quick generation of shapes and the manipulation of these, U-GUI is sure to help any developer create their designs and drafts in a quick simple manner. 


## TEAM
- Francisco Gomez
- Javier Maldonado

## DETAILS
U-GUI utilizes the lexer.py module and U-GUI Parser.py. U-GUI Parser.py is the module where the application runs and initializes the terminal. Input is parsed by yacc using the PLY library. U-GUI makes heavy use of the Tkinter Python library and relies on this to generate the shapes and other objects.


## FEATURES
- Easy and intuitive sintax.
- Easy creation of shapes, labels and lines.
- Option to alter the background color of the window. 
- Option to modify already created shapes, labels and lines.
- Ability to reset window and remove some or all objects.


## COMMANDS

- start(width, height) - creates the window with the specified width and height.
- check - It displays a preview of the windows current configuration.
- background - Offers color options to paint the background of the window.
- oval(x, y, width, height) - creates an oval shape with the given attributes.
- square(x, y, width, height) - creates an square shape with the given attributes.
- line(x, y, width, height) - creates an line shape with the given attributes.
- update **shape**(x, y, width, height) - updates any shape with the new parameters given.
- reset - gives you the option to delete all or a certain type of shape.
- label(x, y, size) - creates a text label with the text you input and with the attributes declared.

## VIDEOS
- Comercial video : https://youtu.be/YuGE9gfg9rA
- Demonstration video : https://youtu.be/ZNhs1N1_VuY





