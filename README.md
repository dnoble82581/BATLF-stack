About
This skeleton project is good for anyone who is familiar with Tailwind, LiveWire or Bootstrap and Alpine. It gives you a blank slate with some power in the back end if you choose to use it. I made it as un-opinionated as I possibly could so whatever you create is completely you but the initial set up is done for you saving some time.

Under The Hood
This is a basic starter file using the following laravel packages installed and ready to use.

Tailwind CSS.
Alpine JS.
LiveWire.
Fortify.
Bootstrap
Tailwind CSS
Installed out of the box, no further configuration has been done.

Alpine JS
Installed using the package manager for more robust control.

LiveWire
Installed out of the box with no further configuration done.

Fortify
I use this because I like that it is un-opinionated and I can create all of my auth pages myself and use its backend. All the backend routes are available you just need to configure them. If you are unfamiliar with how to do this check out Laravels Documentation. I configured this enabling the registration, reset password and email verification features. All other features are commented out so if you want them you just need to configure them.

Bootstrap
I personally do not like using bootstrap, but I kept it in here in case someone does. You will need to import it in the main JS file and it is ready to use.

File Structure
Resources
In the resources folder I created an assets folder for images and favicons. The files in there are my personal images and can be changed to whatever you want. In the views.partials.layouts.main folder you will find the _header file. Here I imported all the favicons using the Vite:asset() function. You will need to update those to your own files. The rest is a standard HTML5 boilerplate.

Layouts
I wanted this to accommodate projects that had multiple layouts so the main directory can be changed to what ever you want. You will just need to make changes the appropriate references. From there you can add as many different layouts as you want. I used laravels component feature for the layout component and everything is echoed through the $slot variable.
