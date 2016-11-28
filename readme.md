# ExtJS 6.2.0 GPL Demos

-	I'm using Sencha Cmd 6.2.1.29 for building these demo apps
-	The projects under located under the demos directory and are using the ExtJS 6.2.0 GPL framework

Note: Currently there is only 1 single project in this repo.

## demos/mobiledemo

Live Link: http://www.claudegauthier.net/demos/MobileDemo/

The purpose of this app is to demonstrate how to properly set a mobile application so that it can navigate with a combination of static and dymamic pages.

- Static pages are pages already loaded in Main.js (card layout)
- Dynamic pages will be created on-the-fly.

Each of these pages are based from an app-base class which provides a scaffolding allowing various parameters to be set such as:
-	personalized toolbar menu (each page has a potential for their unique configuration)
-	navigation (static and dynamic) (work in progress)
-	page type (static / dynamic) (currently only static, will soon change)
-	other configs are added to help with navigation and page construction and behavior logic

All of this is work in progress at the moment..

### What's done

-	fake login
-	home page scaffolding
-	context menu
-	return home
-	logout

### To do
-	add a few dynamic pages
-	have some of these pages load content via an ajax call
-	have parameters involving adding callback to back button for extra code cleanup
-	reuse some of the pages like a search which can be chained dynamically
-	create a logo for the home page (minor detail)
-	create an about page and add it to the context menu.

### Later down the road
-	Use this base code to create an app (iPhone, Android)

This list is far from complete, more ideas will come to me as I go along.

#### Testing this app
 Obviously, this is a mobile application, so, it is best to test it with a mobile phone, however, you can use Chrome in developer/debugger mode and change your view to a mobile phone, which is what I mostly do for testing this app at this current stage of development.

