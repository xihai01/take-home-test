# Shopify Projects - Take Home Test

Thank you for taking time out to complete this test.

It's not too scary, just a snapshot of the type of work we do on a day to day basis.

What we're looking to see is:

- Can you work GIT?
- Can you get connected to a Shopify Dev Store?
- Can you figure out the Shopify theme file structure?
- Can you make some basic changes in files to see the results?

There's a stretch goal at the end which gives you a chance to show off your wicked awesome coding skills - totally optional, but it helps us get to know you better.

## Getting set up

1. Fork this repository, commit changes often so we can see progress
2. Sign up to Shopify partners over at https://www.shopify.ca/partners
3. Create a new dev store once you're registered
4. Install Shopify CLI - https://shopify.dev/themes/tools/cli/installation
5. MacOS users may need to install xcode command line tools via.  xcode-select --install

## Setting up development environment

1. Use `shopify theme pull` to download the default live theme in your dev store, into a new folder in your forked repository.
2. Commit this into git as a baseline.
3. CD into the new folder and run `shopify theme serve`, take a look at the theme and back end pages to get familiar with the theme.

## The Test

1. Create a product in dev store, or seed it with test data. There's a option to seed test products, check out the Shopify CLI for details.
2. Change the colour (something vivid, like red) of the Price on the product detail page - a.k.a. PDP - commit this into the repository.
3. Change the border of a product that shows on listing page, a.k.a. PLP or Collection. - make the change really obvious and commit this into the repo.
4. Create a button on the cart page that makes an AJAX call to clear the cart contents - https://shopify.dev/api/ajax/reference - commit this to the repo when done.
5. STRETCH excercise - add an option into the Product template that offers a rich text input in the Theme Customize as follows:
   name: Product Extra Info
   type: richtext

Render this field onto the product detail page (PDP) after the product description. Render it conditionally to show if 'Product Extra Info' has been entered. Once it's showing on the PDP - commit this to the repo.
Here's your chance to get creative; is there anything else you could do for mobile/desktop modes that would show a super long 'Product Exta Info' in a better way for the screen size?

## Submitting the test over to us

1. Email us a link to the dev store you created along with a password if the front end is protected with a password.
2. Email us a link to your git repository.
3. Feel free to give us any important info you have or feedback on how things went.