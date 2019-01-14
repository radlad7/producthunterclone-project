# producthunterclone-project

The final project in Nick Walter's Django 2 and Python 3 Web Developer course on Udemy is based off the Product Hunt web site.

This clone website features 3 Django apps:
  * product hunter - the core app
  * products
  * accounts

The product hunter core app features the navbar complete with Sign Up/Login buttons. The products and accounts app are extended by the core app.

  The products app features 3 pages:
	* Create - Features a form field for Title/Body/URL/Icon (Image), and Image with a Submit button to add the product.
	* Home Page - features all the products created listing its title, summary and total votes.
		The upvote button allows the product to be voted on.
	* Detail Page - if a particular product is clicked, you will be taken to its page and be shown the title, photos, have an option to vote, and see who "hunted" i.e. created the product, in addition to the date it was hunted.

The accounts app features two pages:
	* Sign Up - Create a new account to access the product hunt functionality
	* Login - Username/Password are required in order to view, vote on, and create products to be hunted.
