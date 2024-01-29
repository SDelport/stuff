# How to add custom TODO's in Rider

Image 1
<a href="https://imgbb.com/"><img src="https://i.ibb.co/GPnLc7s/Screenshot-2024-01-29-103925.png" alt="Screenshot-2024-01-29-103925" border="0"></a>

Go to View -> Tool Windows -> TODO (It's near the bottom)

Image 2
<a href="https://ibb.co/XYFhy5y"><img src="https://i.ibb.co/Y0fzDdD/Screenshot-2024-01-29-104331.png" alt="Screenshot-2024-01-29-104331" border="0"></a>

This will open your TODO window at the bottom to view all TODO's

On this screen will be a filters button, clicking it will present you with the option to "Edit Filters".

Image 3
<a href="https://ibb.co/zZZ1QYx"><img src="https://i.ibb.co/QMMZpRQ/Screenshot-2024-01-29-104550.png" alt="Screenshot-2024-01-29-104550" border="0"></a>

On the screen that is opened after clicking on "Edit Filters", you will be able to see all the patterns that Rider currently uses to match TODO's you will need to add a pattern first, the pattern "\b{Your Identifier}\b is sufficient.

Remember to uncheck "Use color scheme TODO default colors" to make sure your new pattern stands out. Also remember to not make it "Case sensitive"

After adding the pattern, add a filter where you will simply name your filter and select your pattern you just created.

Image 4
<a href="https://ibb.co/SDgJmpC"><img src="https://i.ibb.co/Q7VXHGw/Screenshot-2024-01-29-105317.png" alt="Screenshot-2024-01-29-105317" border="0"></a>

To finish off, just click the button highlighted in Image 3 to select the filter you've created to view all the TODO's matching your new pattern in the whole codebase.

If you created custom highlighting, your TODO's should also now look similiar to Image 1.

Happy TODOing
