# Cheeky P's
This is your documentation. Feel free to make changes to it if I've not explained something very well, or if you keep forgetting how to do something in Shopify and want a place to put something so you remember.

## The main site
### Updating the fundraising total
This is within a file in this repository. It's located at `/src/Sections/Sustainability.svelte`. Click on the name of the file once you've found it, then you'll see the contents. There's a comment at the top which highlights the value you need to change. It's only the percetage that needs changing. To edit the value, click on the Pencil icon, make your changes and then Commit them at the bottom of the screen. The Commit will trigger something called a Deployment, which basically means the updated file is pushed across to the server. Allow up to a couple of minutes for that to happen.

### Updating other files
The site is built using a framework called Svelte. One of the advantages of Svelte is that anyone with basic knowledge of HTML and CSS can work with it. If you look around you should be able to edit some of the text yourselves, but please be careful doing any more than that!

## The Shopify site

### Description
The left-hand button has various levels of text (Paragraph, Heading 1-6).
We are only using Heading 2 and Paragraphs. You can create line-breaks without starting a new paragraph by using a soft-return. On Windows, that's CTRL+ENTER. On a Mac, it's probably CMD+ENTER.

### Tags
We use the tags for two things:
1. The background colour of the product page.
2. Ingredients and Nutrition Info.

For the background colour, your options are `orange`, `yellow`, `teal` and `red`. These are the only tags we're prepared for so don't use any other colours. They should be lower-case and spelt correctly.

For the Ingredients and Nutrition Info, the tags are a shortened version of the flavour, all in lowercase. In the Nutrition Info and Ingredients templates we look for this tag and display the appropriate details. These tags must match the tags used in the `Snippets > NutritionInfo.liquid` and `Snippets > Ingredients` templates in the theme's code editor.

### Editing the code
Go to `Online Store > Themes` and nfind the current theme's Actions button. Click on that and select Edit Code.
I strongly recommend you duplicate the current theme and give the duplicate a good name. Have a look at the names I've used. Then make your changes to the duplicate before publishing the duplicate to be your store's theme.

## Updating Shopify pages
Go to `Online Store` and click on `Pages`. There are three created already. You can use most of the formatting options here but try and stick to: `heading 2`, `heading 3`, `paragraph` and both types of lists.