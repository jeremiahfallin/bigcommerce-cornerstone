## BigCommerce details

BigCommerce Store: https://tacit.mybigcommerce.com/
Preview Code: q6rlqxhp41

## Overview

This is a copy of the [Cornerstone](https://github.com/bigcommerce/cornerstone) template from BigCommerce.
I used css to hide the primary image and show the second product image when hovering over the product card on the Special Items category page.
I used the [BigCommerce API](https://developer.bigcommerce.com/api-reference/) to add the product to the cart when the Add All To Cart button is clicked. I also used their API to delete the cart when the Empty Cart button is clicked.
The details about the logged in customer are displayed conditionally with Handlebars.

## Task

[x] Create a product called Special Item which will be assigned to a new category called Special Items. Be sure to add at least 2 images during the product creation
[x] The Special Item should be the only item which shows in this category - create a feature that will show the product's second image when it is hovered on.
[x] Add a button at the top of the category page labeled Add All To Cart. When clicked, the product will be added to the cart. Notify the user that the product has been added.
[x] If the cart has an item in it - show a button next to the Add All To Cart button which says Remove All Items. When clicked it should clear the cart and notify the user.
[x] Both buttons should utilize the Storefront API for completion.

## Bonus

[x] If a customer is logged in - at the top of the category page show a banner that shows some customer details (i.e. name, email, phone, etc). This should utilize the data that is rendered via Handlebars on the Customer Object.

## Submission

[x] Create a GitHub repo for your codebase. In the Readme file remove the current data and add your own which describes a brief overview of your test.
[x] Be sure you include the Preview Code for the Bigcommerce Store, along with its URL, so we can view it. Then reply to this email with the Github repo link.
