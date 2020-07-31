# Champions UK Code test

## PLAN:

1. Learn about Drupal and how to deploy a custom HTML site to the system.
2. Code the main design
3. Make the design responsive
4. Deploy to a Drupal site

## Issues encounted and how I overcame them:

1. Bootstrap responsive classes - I had some trouble with making sure I was using the correct flex classes for components - this was fixed by studying more of the documentation.

2. Drupal theming - I am completely new to twig templating so it was a challenge to understand the files, regions and making sure the structure was perfect in order for the theme to function properly. After reading Drupal documentation and through a process of trial and error, I was able to get the site fully responsive and functioning on Drupal.

3. Installing and testing Drupal - I used Acquia Dev Desktop 2 to install and setup Drupal 8. I had some directory issues locally and some issues with SSH keys hosting it on Acquiva Desktop, however after reading the documentation I was able to solve this.

## Issues unresolved:

1. I was unable to add the images and text as custom field types and the menu as a block - given more time, I would have studied the documentation and I would have altered the page.html.twig template so that the menu is displayed as a block and the text and images are displayed as fields.

2. I was unable to include the bootstrap.js in the code despite including it in the libraries.yml file. The mobile navigation does not expand on the live site due to this. With more time, I would look further into the documentation and the code to find out how to include this.

3. The admin login panel is in a strange place, on the site at the bottom to the left. I would look into creating a custom admin portal page for the login.

## Finished result:

- Fully responsive HTML site which is a replica of the provided image.
- Live and functioning site through Acquia Cloud.


