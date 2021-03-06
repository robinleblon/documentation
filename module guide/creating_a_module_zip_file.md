# Creating a module.zip file

When you've finished your module, you will probably want to be able to easily install this in other websites. Since Fork CMS 3.0.0, it is possible to install packaged modules. Therefor, you'll need to create a .zip file.

## The .zip file

The zip file contains the absolute paths to the module, as you can see in the image below. This means that you should always have a structure that starts in the base directory of you project.

![Zip structure](https://raw.github.com/forkcms/documentation/master/module%20guide/assets/zip_structure.png)

## Required files

To install the module, some files are required. Each module should have a config.php file in both the backend and frontend.

In the backend, you also need an installer folder that contains an installer.php file. Next to this, you also need an info.xml file. This file is used to display information on the Extensions page in the backend. 

To create these files, we recommend you to take a look in the 'Module development' section.