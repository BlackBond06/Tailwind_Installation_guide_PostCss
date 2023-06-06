/*****************************************************************************************/
                            TAILWIND INSTALLATION WITH POSTCSS
/****************************************************************************************/
This is an installation guide for setting up tailwind to a project using PostCSS.

Introduction:
Tailwind is a utility-first CSS framework for creating modern designs quickly. By utility-first, it means Tailwind provides a set of predefined classes which applys a single style. For example, lets say a background property is needed in 3 div elements, one way to accomplish this would be to create 3 classes for each div element and apply the background property to each of them. This is not a proper way to use CSS. An Ideal way to use CSS in this regard would be to create 1 class, apply the needed background property and reuse in any element that requires this style.

This is the approach that Tailwind CSS uses. Tailwind CSS uses a massive portfolio of classes for almost any style a web project would need making modern designs easy to create and fast.

There are 3 ways to install Tailwind for use in a project:

1.Using CDN Link   /** Note this not suitable for production **/
2.Using PostCSS 
3.Using Tailwind CLI


/**********************  GET STARTED  *************************/

Installing Tailwind using PostCSS can be done with the following steps:

1. Create a folder where the installation will take place. Open the folder with your prefered IDE and then open the built-in terminal of your IDE. if you are using VSCode, the command to open the terminal is CTRL + ~.

2. Go to Tailwind's official website https://www.tailwindcss.com and click on "Get Started". On the installation section, click on "Using PostCSS". This will display an editable screen shot of a terminal. Copy the first command displayed on the editable terminal, go the buit-in IDE terminal you opened ealier, paste and run. After running the first command on the chrome official website, go back to the website, copy and run the second command on your IDE. This will create a config.js file in the root of your project.

3. Again, on Tailwind's official website, copy the "postcss.config.js" file, go to your project folder and create a new file called "postcss.config.js" and paste the copied code inside and save.

4. Go to the tailwind.config.js file at the root of your directory, in the module's object, edit the content property by adding the path to your html file like so: "./public/**/*.html".

5.
