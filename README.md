## **KNINE Coffee**

#### By Tanner Damron
###### Initiated May 5th, 2019.

----------
## Project Proposal
Name of Student:
> Tanner Damron

Name of Project:
> KNINE Coffee

Project’s Purpose or Goal:
> A website where users can browse products and information about KNINE Coffee as well as order KNINE Coffee products.

List the absolute minimum features the project requires to meet this purpose or goal:
> Routing to different pages (Home, Products, Strength, Core Values, Contact)
> Users Email and Password saved in a database
> Secure credit/debit card checkout page

What tools, frameworks, libraries, APIs, modules and/or other resources (whatever is specific to your track, and your language) will you use to create this MVP? List them all here. Be specific.
> Windows 10.1
> Visual Studio Code (Text Editor)
> Node.js v10.15.3
> npm v6.4.1
> React
> JSX
> JavaScript
> CSS
> Babel v7.0.0
> Firebase or MongoDB

If you finish developing the minimum viable product (MVP) with time to spare, what will you work on next? Describe these features here: Be specific.
> Instagram API to pull in recipe images and posts from themacrobarista

What additional tools, frameworks, libraries, APIs, or other resources will these additional features require?
> Instagram API

## Description
This web application was built with React, and will allow the user to create an account and password for KNINE Coffee, browse, search, and order KNINE Coffee products, and sign up for a mailing list.

# Layout/Design
### Home Page
![](Home-Design.png?raw=true)
### Products Page
![](Products-Design.png?raw=true)
### About Page
![](About-Design.png?raw=true)
### Recipes Page
![](Recipes-Design.png?raw=true)
### About Page
![](About-Design.png?raw=true)
### Strength Page
![](Strength-Design.png?raw=true)


# Component Trees
### Home Page
![](Home-Component-Tree.png?raw=true)
### Products Page
![](Products-Component-Tree.png?raw=true)
### About Page
![](About-Component-Tree.png?raw=true)
### Recipes Page
![](Recipes-Component-Tree.png?raw=true)
### About Page
![](About-Component-Tree.png?raw=true)

## Specifications

<details>
<summary>User stories and specifications</summary>

<table>
  <tr>
    <th> Scenario 01 </th><th></th>
  </tr>
  <tr>
    <td> Behavior </td>
    <td>As a user, I want to be able to create an account with KNINE Coffee.</td>
  </tr>
  <tr>
    <td> Input </td>
    <td>User enters an email and password to sign up</td>
  </tr>
  <tr>
    <td> Output </td>
    <td>User's information is saved in a database and will allow user to sign back in with the same credentials.</td>
  </tr>
  <tr>
    <td> Notes </td>
    <td> </td>
  </tr>
  <tr>
    <td> Completion </td>
    <td> False </td>
  </tr>
</table>

<table>
  <tr>
    <th> Scenario 02 </th><th></th>
  </tr>
  <tr>
    <td> Behavior </td>
     <td>As a user, I want to be able to browse this website for products</td>
  </tr>
  <tr>
    <td> Input </td>
    <td>User clicks "Products".</td>
  </tr>
  <tr>
    <td> Output </td>
    <td>User can view all KNINE Coffee products available.</td>
  </tr>
  <tr>
    <td> Notes </td>
    <td> </td>
  </tr>
  <tr>
    <td> Completion </td>
    <td> False </td>
  </tr>
</table>

<table>
  <tr>
    <th> Scenario 03 </th><th></th>
  </tr>
  <tr>
    <td> Behavior </td>
    <td>As a user, I want to be able to search for any specific product.</td>
  </tr>
  <tr>
    <td> Input </td>
    <td>User types in "Shirt" in search bar</td>
  </tr>
  <tr>
    <td> Output </td>
    <td>All products with "Shirt" in the name or description will be shown.</td>
  </tr>
  <tr>
    <td> Notes </td>
    <td> </td>
  </tr>
  <tr>
    <td> Completion </td>
    <td> False </td>
  </tr>
</table>

<table>
  <tr>
    <th> Scenario 04 </th><th></th>
  </tr>
  <tr>
    <td> Behavior </td>
    <td>As a user, I want to be able to add products to a shopping cart.</td>
  </tr>
  <tr>
    <td> Input </td>
    <td>User clicks "add product" button.</td>
  </tr>
  <tr>
    <td> Output </td>
    <td>The product that was added will be in a user's shopping cart.</td>
  </tr>
  <tr>
    <td> Notes </td>
    <td> </td>
  </tr>
  <tr>
    <td> Completion </td>
    <td> False </td>
  </tr>
</table>

<table>
  <tr>
    <th> Scenario 05 </th><th></th>
  </tr>
  <tr>
    <td> Behavior </td>
    <td>As a user, I want to be able to check out and purchase all products in my shopping cart.</td>
  </tr>
  <tr>
    <td> Input </td>
    <td>User clicks "Check Out" on the shopping cart page and is sent to a secure credit/debit card purchasing page.</td>
  </tr>
  <tr>
    <td> Output </td>
    <td>Display public profile</td>
  </tr>
  <tr>
    <td> Notes </td>
    <td> </td>
  </tr>
  <tr>
    <td> Completion </td>
    <td> False </td>
  </tr>
</table>

<table>
  <tr>
    <th> Scenario 06 </th><th></th>
  </tr>
  <tr>
    <td> Behavior </td>
    <td>As a user, I want to be able to enter my credit/debit card information to make a purchase.</td>
  </tr>
  <tr>
    <td> Input </td>
    <td>User enters credit/debit card info and clicks "Submit Purchase".</td>
  </tr>
  <tr>
    <td> Output </td>
    <td>User gets a confirmation (model & email) that the purchase was successful or denied</td>
  </tr>
  <tr>
    <td> Notes </td>
    <td> </td>
  </tr>
  <tr>
    <td> Completion </td>
    <td> False </td>
  </tr>
</table>

<table>
  <tr>
    <th> Scenario 07 </th><th></th>
  </tr>
  <tr>
    <td> Behavior </td>
    <td>As a user, I want to be able to add my email to the newsletter mailing list</td>
  </tr>
  <tr>
    <td> Input </td>
    <td>User selects "Join Newsletter" and types in user's email.</td>
  </tr>
  <tr>
    <td> Output </td>
    <td>Confirmation that the user has been added to the mailing list pops up</td>
  </tr>
  <tr>
    <td> Notes </td>
    <td> </td>
  </tr>
  <tr>
    <td> Completion </td>
    <td> False </td>
  </tr>
</table>

<table>
  <tr>
    <th> Scenario 08 </th><th></th>
  </tr>
  <tr>
    <td> Behavior </td>
    <td>As a user, I want to be able to view the about us page</td>
  </tr>
  <tr>
    <td> Input </td>
    <td>User selects "Core Values" link.</td>
  </tr>
  <tr>
    <td> Output </td>
    <td>User is taken to the about us page with all information on KNINE Coffee</td>
  </tr>
  <tr>
    <td> Notes </td>
    <td> </td>
  </tr>
  <tr>
    <td> Completion </td>
    <td> False </td>
  </tr>
</table>

<table>
  <tr>
    <th> Scenario 09 </th><th></th>
  </tr>
  <tr>
    <td> Behavior </td>
    <td>As a user, I want to be able to view the "Recipes" page</td>
  </tr>
  <tr>
    <td> Input </td>
    <td>User selects "Recipes" link.</td>
  </tr>
  <tr>
    <td> Output </td>
    <td>User is taken to the recipes page with all recipes and links to Instagram</td>
  </tr>
  <tr>
    <td> Notes </td>
    <td> </td>
  </tr>
  <tr>
    <td> Completion </td>
    <td> False </td>
  </tr>
</table>

</details>


## Notes
* >
