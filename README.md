[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/1B5UfUNt)
# Keyframe-Animation-Project
Students will create a single web page project that animates one or more graphics using one or more keyframe animations and a variety of transitions and animation techniques.

## Project Requirements
Are listed in the README file in the `project` folder.
You must meet all requirements in the following areas:
* HTML You need 
  - at least 1 image, a `<main>` element that will act as the "stage" for your animation,
  - a `h1` for the title of your animation
* Validity - passes the W3C Validator (HTML and CSS)
* CSS 
  - you must have an external stylesheet ending in `.css`
  - you may NOT use a style attribute in your HTML
  - you must use the `animation` property on your image (at least one of the images)
  - you either need to have at least 4 percentage keyframes OR at least 6 keyframes in all
  - your animation must target at least 4 different properties (opacity, transform, height, etc.) 
    + ***NOTE: in the case of transform, each type of transform counts as a unique "property" (these would be `translate()`, `rotate()`, `skew()`, etc.)***
* Design - your design score will be assessed based on the video captures &/or screen captures (you'll want to see the rubric in the assignment description for the course)

## Instructions
1. Place all of your project files (HTML, CSS, images, etc.) into the simple_html_page folder.
2. Clone this project: `git clone `.
3. Open the projec tin VS Code (double click on `Image-Gallery-Project.code-workspace`)
4. Open the terminal (View > New Terminal).
5. Install the Python extension: ***Python extension for Visual Studio Code***
6. In the terminal, type `poetry shell`.
    - You should see a line saying something like `Spawning shell within C:\Users\my_username\AppData\Local\pypoetry\Cache\virtualenvs\Image-Gallery-Project-IMtvp_MA-py3.9`
7. Note the name of your virtual environment file, which will look something like `Image-Gallery-Project-IMtvp_MA-py3.9`
8. Open the Command Palette 
    - in the menu it's: View > Command Palette
    - you could also type `Ctrl + Shift + P`
9. Type Python: Select Interpreter
    - if you see the virtual environment file, click it.
    - if you don't see it, click `Select at Workspace level`
10. Select the virtual environment file from above (it should show the word Poetry in blue on the right)
    - if you don't see it, close VS Code and re-open it and repeat steps 8 and 9.
11. Type `poetry update` and wait for everything to install.
12. In the terminal, once everything is done installing, type `pytest`
13. If that doesn't work, click the Testing icon (looks like a beaker), then click the blue `Configure Python Tests` button, then select `pytest pytest framework` and choose the `tests` folder.
14. Place your content in the `image_gallery` folder.
15. Store all images (both full size and thumbnail sized images).
16. Select a theme for your images and style.
17. Test your code by running pytest. The goal is to pass all tests.
18. Record your final product before turning it in.
19. The recording should show you resizing and or zooming in and out to show a variety of widths and demonstrate the flex layout is working without ever making your site look broken.
20. Be sure to commit and push your changes at regular intervals, but particularly once you finish the project.
