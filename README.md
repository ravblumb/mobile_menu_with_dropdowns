# mobile_menu_with_dropdowns
Here is a menu format with dropdowns that relies on a short Javascript.

I am transitioning my agency's web portal to mobile format.  There are many pretty mobile menus availabe, but they all seem to rely on the menu existing in the same div as the open/close buttons.  They also require fancy CSS tricks.

I needed to place the menu button above some other elements in the header, but show the menu below the header.

This javascript takes the id of the target section as a variable.  The open and close buttons are named `${section}Openbtn` and `${section}Closebtn`.  

You can substitute the buttons for image tags for greater versatility.
