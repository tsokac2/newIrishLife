<h1 align="center">New Irish Life</h1>

Web-based travel guide for providing correct information for a fresh start on Irish grounds.
Finding work, a place to stay, where to buy good cheap food in Ireland. 
All of this can be difficult in the beginning but with the correct preparation,
advice, and planning this task can be made a lot easier.
**[New Irish Life](https://newirishlife.herokuapp.com/)** is a great starting point.

![Website Main Mockup](https://github.com/tsokac2/newirishlife/blob/main/static/wireframes/W4_Main.jpg)

## Contents
* **[User Experience Design (UX)](#UX)**
    * **[User Story](#User-Story)**
    * **[Design process](#Design-process)**
* **[Features](#FEATURES)**
    * **[Home](#HOME)**
    * **[Trip](#TRIP)**
    * **[Work](#WORK)**
    * **[Life](#LIFE)**
    * **[Login](#LOGIN)**
    * **[Signup](#SIGNUP)**
    * **[Profile](#PROFILE)**
    * **[Shop](#SHOP)**
    * **[Product Details](#PRODUCT-DETAILS)**
    * **[Bag](#BAG)**
    * **[Checkout](#CHECKOUT)**
    * **[Footer](#FOOTER)**
    * **[Cross Project Features](#CROSS-PROJECT-FEATURES)**

* **[Technologies used](#TECHNOLOGIES-USED)**
* **[Testing](#TESTING)**
* **[Deployment](#DEPLOYMENT)**
* **[Credits](#Credits)**

****

# UX
<h2 align="center">Story</h2>
<h3 align="center">Four years ago, one Croatian landed in Ireland.
There was a lot of info about life in Ireland on the internet, but not essentials information in one place.
</h3>
<h2 align="center">Well, not anymore!</h2>


## Project Goals
This project is my final project for the Code Institute's Full stack development programme. The main goal of this project is to create an e-commerce site using Django framework, which is hosted with AWS as well as implementing a fully functional payment system with Stripe.

## Site Owner Goals
* Provide the users with a professional e-commerce online shop to allow secure purchases.
* Make a profit selling traditional Irish souvenirs.
* Promote Ireland and the Irish way of living.


## User Story
User stories are presented for 3 different User types:
* **First Visitor**
* **Active User**
* **Superuser**

**[Back to content](#contents)**

### First Visitor
* As a new Irish resident, I want all **NECESSARY AND IMPORTANT** information for my **[New Irish Life](https://newirishlife.herokuapp.com/)** in one place and available from any device connected to the internet, so I can organize my life in a fun and simple way.
* Visibly accessible **Main Menu** configure for any screen size with quick access to all website sections. 
* In the **Trip** section, I want to have quick access to the most popular online travel brands and quick link options to chose from.
* The **Trip** section will contain custom configurated Google Maps API with some options for bus, train, or tram stations with visible markers in different colors for the fastest navigation.
* I the **Work** section, I want to have quick access to the most popular recruitment websites and quick link options to chose from.
* I the **Life** section, I want to have quick access to the most up-to-date rental website,  most popular Irish mobile network providers, most popular grocery shop brands, and quick link options to chose from.
* In the **Shop** section, I want to have the option to sort and search all displayed products by categories, prices, and keywords including quick links for the different product categories, ability to purchase _without_ a User Login process.
* In the **Shop/checkout** section visible option to create a User Profile and save delivery information.
* I want to have the ability to create my profile for the full **[New Irish Life](https://newirishlife.herokuapp.com/)** user experience (UX).
* In the **Footer** section, I want to have main section links with the Newsletter User form following by Social media links/logo icons.
* I want to stay up-to-date with all fresh information regarding work and lifestyle by subscribing to my email for newsletter services without creating the User Profile account.
* Browsing through the website I want to have access to each URL directly so it feels like a single app website.
* I want to receive a friendly message if I try to access a **URL** that doesn't exist or I don't have access to instead of the default browser **404** messages.


### Active User
* I want to have the ability to register with my _Email Address_ or _User Name_, and _Password_ strength of my choice with error validation notifications for non-valid input.
* I want to receive a link for the _User Email_ confirmation process into my mailbox.
* I want to Login with my _Username or Email_ and _Password_ with an error validation notification for non-valid input.
* I want to have the option _"Remember Me"_ for my login credentials.
* As an **Active User**, I want to have the option to reset my _Login credentials_.
* On my profile page I want to have the following features listed:
    * My Full name
    * My Full name
    * My Username
    * My Email
    * My Profile image
    * My Phone Number
    * Full Address
    * Ability to **Edit** and **Update** all my profile details.
    * List of my orders history, if none a quick link for the **[SHOP](https://newirishlife.herokuapp.com/products/)** section.
    * Orders history card has to contain a _Link/order_ number with full order details, _Order Date_, _Item Quantity + Item Name_, _Total_ amount spent per order. 
    * Ability to **Delete** my profile with a confirmation message.


### Superuser
* As a Superuser access, I want to have the ability to access the admin console.
* As a Superuser I want to have the ability to upload a new product for the **[SHOP](https://newirishlife.herokuapp.com/products/)** section with success confirmation messages. 
* As a Superuser I want to have direct links displayed for _Edit_ and _Delete_ products on the products detail page.
* As a Superuser I want to have the ability to **Delete** existing products with a confirmation message.

**[Back to content](#contents)**

### Testing User Stories from User Experience (UX)
* **MAIN MENU** - As a _First Visitor_, I want to easily understand the main menu and links for different website sections:
    * Upon entering the site user can see a clear navigation bar and site logo.
    * Each menu link is self-explanatory and as a _First Visitor_, the user can understand the main purpose of the link section.
    * The main menu is visible in the **Footers** section with a _"mirror image"_ of the top main menu navigation links.

* Definition by **[HOME](https://newirishlife.herokuapp.com/)** section - As a _First Visitor_, I want to easily understand the main purpose of the site and my benefit of the **[New Irish Life](https://newirishlife.herokuapp.com/)**:
    * The main purpose is represented with a short introduction paragraph and a _"HERO"_ image gallery.
    * Website content is pointed with four visual design cards for the top section of the site.
    * Footer is well structured and offers links for the main site section and full operating **Newsletter** form service.
    * Users can share **[New Irish Life](https://newirishlife.herokuapp.com/)** on four social media links presented in the bottom part of the footer.
    * The main navigation menu and footer are replicated through all main sections of the website.

* Definition by **[TRIP](https://newirishlife.herokuapp.com/trip)** section - As a _First Visitor_, I want to easily understand section purpose with a short and fun intro paragraph and slide-show intro gallery:
    * Users can choose the most popular online travel brands to organize in card elements.
    * Each card element contains the main link, the brand website screenshot, the _"Quick links..."_ option, and a brand description.
    * Users can have access to the best Irish public transportation services.
    * Users can navigate through embedded **[Google Maps API](https://newirishlife.herokuapp.com/trip)** with colorful markers representing the most important bus stations, train stations, and tram stations in Dublin, Ireland.

* Definition by **[WORK](https://newirishlife.herokuapp.com/work)** section - As a  _First Visitor_, I want to easily understand how to start a job search process with the best possible preparation for the Irish work market:
    * Users can quickly understand where to start the job search process.
    * Users can understand what kind of **[CV](https://newirishlife.s3.eu-west-1.amazonaws.com/static/downloads/Tomislav+Sokac_CV.pdf)** template is necessary for a successful job search mission.
    * Users can find the best option for online education with the best offers.

* Definition by **[LIFE](https://newirishlife.herokuapp.com/life)** section - As a _First Visitor_, I want to easily find the best online rental marketplaces, the most popular mobile networks provider, and large-chain grocery shops:
    * Users can choose one of the four most popular Irish online rental portals with quick links for share accommodation or buy options.
    * Users can quickly decide for best mobile network providers regarding broadband speed, bill pay offers, TV broadband offers.
    * Users can check the four largest grocery shop chains with previous user reviews, best deals, work offerings.

**[Back to content](#contents)**

* Definition by **[LOGIN](https://newirishlife.herokuapp.com/accounts/login/)** section -  I want to easily login with my _email-or-username_ or and _password_ and be redirected to the HOME page with an updated menu with access to the **Profile** page and success login message:
    * If the user is not registered there is a **["Create profile"](https://newirishlife.herokuapp.com/accounts/signup/)** link for the registration process form. 
    * If the user forgot login credentials she/he can reset the password with the **["Forget Password?"](https://newirishlife.herokuapp.com/accounts/password/reset/)** link.
    * If the user enters incorrect credentials, the login form will prompt a login _error_ message.
    * Users have an option to save login credentials with the **"Remember me"** check box.
    * The **[LOGIN](https://newirishlife.herokuapp.com/accounts/login/)** section contains quick _"cards"_ overview of the site and short introduction paragraph and a _"HERO"_ image gallery.

* Definition by **[SIGNUP](https://newirishlife.herokuapp.com/accounts/signup/)** section - I want to easily register with my _email_, _username_, and _password_ with a minimum of 8 characters of my choice and be redirected to the **Confirmation** link page with a message to **![CONFIRM](wireframe link)** my email address:
    * If the user is registered there is a **[LOGIN](https://newirishlife.herokuapp.com/accounts/login/)** link for register users.
    * For a successful registration process user must enter the following:

        | **Registration Form** |
        --- | 
        E-mail address |
        E-mail address confirmation |
        Username |
        Password |
        Password (again) |
   
    * The **[SIGNUP](https://newirishlife.herokuapp.com/accounts/signup/)** section contains quick _"cards"_ overview of the site and short introduction paragraph and a _"HERO"_ image gallery.

**[Back to content](#contents)**

* Definition by **[PROFILE](https://newirishlife.herokuapp.com/accounts/login/)**  section - On my **Profile** page I want to have the option to **UPDATE** my profile details, **LOGOUT** from my profile and **DELETE** my profile:
    * User ![Profile Details]( wireframe image ) are listed in the following order:
        * Profile image
        * Full Name (If updated)
        * Username
        * Email 
        * Create profile date
    * User update form contains the following fields:
    * The user has an option to update profile details.

        | **Profile Update Form** |
        --- | 
        Full name |
        Phone number |
        Street address 1 |
        Street address 2 |
        City |
        County |
        Postcode |
        Country |

    * Users can see Orders history details on the right side of the profile page.
    * Order history details contain the following details:
        * Link Order number for full order details
        * Order data
        * Order Items
        * Total amount spent

**[Back to content](#contents)**

* Definition by **[SHOP](https://newirishlife.herokuapp.com/products/)** section - As a _First Visitor_, I want to see all listed products that **[New Irish life](https://newirishlife.herokuapp.com)** is offering with corresponding product categories:
    * Users can quickly browse through the **[SHOP](https://newirishlife.herokuapp.com/products/)** section and view products and products categories.
    * Users can select one of five categories from the categories menu and browse only that type of product.
    * Users can sort all products by the following queries with a sort _dropdown menu_.
    * Users can search for a product by using a _search bar_ with the specific _keyword_ of their choice.
    * Users can quickly understand what is product _name_, _price_, _rating_, and _product categories_ from the product detail card.
    * If the user is a **SUPERUSER** then the _superuser_ has the option to ["Add New Product"]( wireframe link).


* Definition by **[PRODUCT DETAIL](https://newirishlife.herokuapp.com/products/4/)** section - As a _First Visitor_, I want to understand quickly what kind of type of product is on the selected **[PRODUCT DETAIL](https://newirishlife.herokuapp.com/products/4/)** page:
    * Users can view 3 product images browsing through image gallery thumbnails.
    * Users can view _product name_, _rating_, _special offer_, _product price_, chose _product quantity_, view product _description_.
    * Users have two options, a **["Keep Shopping"](https://newirishlife.herokuapp.com/products/)** link to browse different products or an **["Add To Bag"](https://newirishlife.herokuapp.com/bag/)** option for the browsed product.
    * If the user is a **SUPERUSER** then the _superuser_ has the option to **"EDIT"** or to **"DELETE"** browsed product.


* Definition by **[BAG](https://newirishlife.herokuapp.com/bag/)** section -  As a _First Visitor_, I want to view my **[BAG](https://newirishlife.herokuapp.com/bag/)** items by clicking on the BAG link in the menu:
    * Users can view items they "Add to Bag" with the following item(s) details:
        * _Item Name_
        * _Item Image_
        * _Item SKU Number_
        * _Item Price_
        * _Item Description_
        * _Quantity_
    * Users have the option to update item Quantity to **"Add"** or **"Deduct"** item quantity from the shopping **[BAG](https://newirishlife.herokuapp.com/bag/)**.
    * Users can easily view the **"Grand Total"** amount of their shipping **[BAG](https://newirishlife.herokuapp.com/bag/)**.
    * Users can easily understand delivery charges according to of amount they are planning to spend.
    * Users can completely remove the item from shopping **[BAG](https://newirishlife.herokuapp.com/bag/)** by pressing red **"X"** in the top right corner of the item details card.
    * Users have the option to **"Keep Shopping"** or to **"Checkout"** requested items from shopping **[BAG](https://newirishlife.herokuapp.com/bag/)**. 

**[Back to content](#contents)**

* Definition by **CHECKOUT** section - As a _First Visitor_, I want to **CHECKOUT** securely with my valid credit card:
    * For the successful CHECKOUT process user must enter the following details:

        | **Details** |
        --- | 
        Full name * |
        Email Address * |
        | **Shipping Details** |
        Phone number *  |
        Street address 1 * |
        Street address 2 |
        Town or City * |
        County |
        Postal Code * |
        Country * |

        | **Payment details** |
        --- | 
        Card Number * |
        Expiry Date * |
        CVC Number * |
    
    * Users have the option to **["Adjust Bag"](https://newirishlife.herokuapp.com/bag/)** which will redirect them to their **["BAG"](https://newirishlife.herokuapp.com/bag/)** or **"Complete Order"** if all the details are correct will charge their card for the **Grand Total**  **["BAG"](https://newirishlife.herokuapp.com/bag/)** amount.
    * Users can view **"SUMMARY"** of their requested items with the following details:
        * Total number or ordering items
        * Item Main Image
        * Item Name
        * Item Quantity
        * Item Price
        * Item Details Link
    * If the user is a **"Register"** user then there is a checkbox to **_"Save this delivery information to my profile"_**
    * If the user is not a "Register" user the there are 2 options:
        * **[Create an account](https://newirishlife.herokuapp.com/accounts/signup/)**
        * **[Login](https://newirishlife.herokuapp.com/accounts/login/)**
    
    **_NOTE: This is a school project, hence the products are NOT for "real-world" order purposes. For testing the payment process please use the following test card details:_**

    | **Test Card Details** |
    --- | 
    Card Number:  **4242 4242 4242 4242** |
    Expiry Date: any valid date ex. **02/25** |
    CVC Number: any 3 digits number ex. **555** |

**[Back to content](#contents)**

* Definition by **CHECKOUT SUCCESS** section - As a _First Visitor_, I want to see all order details with **_"Checkout success message"_**:
    * If the checkout process was successful user will receive an email Confirmation for Order Number - ![Email example](wireframe link).
    * Users can quickly view orders details on generated order **"CHECKOUT SUCCESS"** page.
    * Users can view the following order details on the **CHECKOUT SUCCESS** page:
        * _Order Number_
        * _Order Date_
        * _Order Details_
        * _Delivery addrress_
        * _Billing Info_
    * Users have a link to go back to the **[SHOP](https://newirishlife.herokuapp.com/products/)** section and continue shopping.


* Definition by **ADD NEW PRODUCT** section -  As a _Superuser_, I want to have the ability to **"Add New Product"** in a **[SHOP](https://newirishlife.herokuapp.com/products/)** section:
    * Superusers can **"Add New Product"** by entering the following inputs fields:
        * _Product Category_
        * _Product SKU Number_
        * _Product Name_
        * _Product Description_
        * _Product Price_
        * _Product Sales Price_
        * _Product Rating_
        * _Product Image 1_ - Mani image
        * _Product Image 2_
        * _Product Image 3_
    * Superusers will receive form validation errors if inputs fields are not valid.
    * If the **"Add New Product"** process is completed, the superuser will be redirected to the _new dded product_ detail page to review added product detail page.
    * **"Add New Product"** detail page **[view](https://github.com/tsokac2/newirishlife/blob/main/static/wireframes/https://github.com/tsokac2/newirishlife/blob/main/static/wireframes/W4_Home.png)**


* Definition by **EDIT PRODUCT** section -   As a _Superuser_, I want to have an ability to **"EDIT"** product that is already listed in a **[SHOP](https://newirishlife.herokuapp.com/products/)** section:
    * Superusers can **"EDIT"** by _updating_ the following inputs fields:
        * _Product Category_
        * _Product SKU Number_
        * _Product Name_
        * _Product Description_
        * _Product Price_
        * _Product Sales Price_
        * _Product Rating_
        * _Product Image 1_ - Mani image
        * _Product Image 2_
        * _Product Image 3_
    * Superusers will receive form validation errors if inputs fields are not valid.
    * If the **"EDIT"** process is completed successfully, the superuser will be redirected to the _edited product_ detail page to review product updates.
    * Superuser has an option to **"DELETE"** product with the **_"Are you sure you want to delete product?_"** confirmation option.
    * **EDIT PRODUCT** detail page **[view](https://github.com/tsokac2/newirishlife/blob/main/static/wireframes/https://github.com/tsokac2/newirishlife/blob/main/static/wireframes/edit_new_product.png)**

**[Back to content](#contents)**

### Design process

**1.** Draft basic UX sections:
* **[HOME](https://newirishlife.herokuapp.com/)**
* **[TRIP](https://newirishlife.herokuapp.com/trip)**
* **[WORK](https://newirishlife.herokuapp.com/work)**
* **[LIFE](https://newirishlife.herokuapp.com/life)**
* **[LOGIN](https://newirishlife.herokuapp.com/accounts/login/)**
* **[SIGNUP](https://newirishlife.herokuapp.com/accounts/signup/)**
* **[PROFILE](https://newirishlife.herokuapp.com/accounts/login/)**
* **[SHOP](https://newirishlife.herokuapp.com/products/)**
* **[PRODUCT DETAIL](https://newirishlife.herokuapp.com/products/4/)**
* **[BAG](https://newirishlife.herokuapp.com/bag/)**

**2.** Brief list of all pop-ups, alert messages, email layouts and their front-end placement.

**3.** List all color pallets - usage - background color, font color, border.

**4.** List all font styles for best UX, regarding user profile details, movie quotes, post titles, and descriptions.

**5.** A list of free images from the free-image web platforms for each project section.

**6.** Draft web-page layout using Adobe Photoshop and Balsamiq for the main layout and Adobe Illustrator for layout components such as Logo, borders, navigation elements.

**7.** List possible Fowtawesome Icon for best UX in picture experiences and a draft of custom icons.

**8.** Plan Python and Django apps implementation into the project.

**9.** List Semantic Mark-up to structure HTML code.

**10.** List CSS folder structure for SASS Pre-processor configuration.

**11.** List of preferable Django packages for website front-end and backend performance.

**12.** Plan Django apps installation and main usage per website section.

**13.** Plan Django Templates structure and static files structure.

**14.** Plan database Django Forms and Models structure for the following website sections:
* **[SIGNUP](https://newirishlife.herokuapp.com/accounts/signup/)**
* **[SHOP](https://newirishlife.herokuapp.com/products/)** section products details
* User **[PROFILE](https://newirishlife.herokuapp.com/accounts/login/)** section
* Shopping **[BAG](https://newirishlife.herokuapp.com/bag/)** Checkout
* **Add New Product** - (Superuser access only)

**15.** Create and configure **[Amazon S3](https://aws.amazon.com/s3/?nc2=h_ql_prod_fs_s3)** bucket for website static files structure and purposes.

**16.** Plan and implement **[Google Maps API](https://developers.google.com/maps/gmp-get-started#quickstart)** for orientation purposes.

**17.** Plan and implement **[Emailjs API](https://dashboard.emailjs.com/sign-in)** service for Newsletter form.

**18.** Take notes for all major development issue, their solutions, challenges, project credits, and SLACK community guidance.

**[Back to content](#contents)**

### Wireframes
* **[HOME](https://newirishlife.herokuapp.com/)** section general idea - for Large and Small screens devices - **[View](https://github.com/tsokac2/newirishlife/blob/main/static/wireframes/W4_Home.png)**
* **[TRIP](https://newirishlife.herokuapp.com/trip)**, **[WORK](https://newirishlife.herokuapp.com/work)**, and **[LIFE](https://newirishlife.herokuapp.com/life)** sections general idea - for Large and Small screens devices - **[View](https://github.com/tsokac2/newirishlife/blob/main/static/wireframes/W4_Trip.png)**
* **[TRIP GOOGLE MAPS](https://newirishlife.herokuapp.com/trip)** section general idea - for Large and Small screens devices **[View](https://github.com/tsokac2/newirishlife/blob/main/static/wireframes/W4_Google_Maps.png)**
* **[SIGNUP](https://newirishlife.herokuapp.com/accounts/signup/)** section general idea - for Large and Small screens devices - **[View](https://github.com/tsokac2/newirishlife/blob/main/static/wireframes/W4_Signup.png)**
* **[LOGIN](https://newirishlife.herokuapp.com/accounts/login/)** section general idea - for Large and Small screens devices - **[View](https://github.com/tsokac2/newirishlife/blob/main/static/wireframes/W4_Login.png)**
* **[SHOP](https://newirishlife.herokuapp.com/products/)** section general idea - for Large and Small screens devices - **[View](https://github.com/tsokac2/newirishlife/blob/main/static/wireframes/W4_Shop.png)**
* **[PRODUCT DETAIL](https://newirishlife.herokuapp.com/products/11/)** section general idea - for Large and Small screens devices - **[View](https://github.com/tsokac2/newirishlife/blob/main/static/wireframes/W4_Product_Detail.png)**
* **[BAG](https://newirishlife.herokuapp.com/bag/)** section general idea - for Large and Small screens devices - **[View](https://github.com/tsokac2/newirishlife/blob/main/static/wireframes/W4_Bag.png)**
* **FOOTER** section general idea - for Small devices - **[View](https://github.com/tsokac2/newirishlife/blob/main/static/wireframes/W3_Footer.png)**

**[Back to content](#contents)**

****

# FEATURES

## MAIN MENU
Formatted in three main sections:
* Website logo
* Website sections **[HOME](https://newirishlife.herokuapp.com/)**, **[TRIP](https://newirishlife.herokuapp.com/trip)**, **[WORK](https://newirishlife.herokuapp.com/work)**, **[LIFE](https://newirishlife.herokuapp.com/life)**.
* _First Time Visitor_ User action links **[LOGIN](https://newirishlife.herokuapp.com/accounts/login/)**, **[SHOP](https://newirishlife.herokuapp.com/products/)**, **[BAG](https://newirishlife.herokuapp.com/bag/)**.
* _Active User_ action links **[SHOP](https://newirishlife.herokuapp.com/products/)**, **[BAG](https://newirishlife.herokuapp.com/bag/)**, **PROFILE**.

## HOME
Simple introduction of web page purpose and what value it is bringing to an end-user.

Formatted in three main sub-sections:
* Movie reference pitch - from -  _"The Hobbit: An Unexpected Journey"_.
* Welcoming **_"HERO"_** area with image composition.
* Quick box-model overview of the web page main sections  **[TRIP](https://newirishlife.herokuapp.com/trip)**, **[WORK](https://newirishlife.herokuapp.com/work)**, **[LIFE](https://newirishlife.herokuapp.com/life)**, **[SHOP](https://newirishlife.herokuapp.com/products/)** sections.

## TRIP
Section introduction with intro reference and **"call-to-action"** headings.

Formatted in two main sub-sections:
* **_CHOOSE WISELY_** Flights booking web services.
* **_HOP ON_** Ireland public transportation's most popular options and guidelines.
* **Google Maps** with a tracker for public transportation and _"Hot"_ locations in Dublin city with 3 markers in different colors for **Dublin Bus**, **Dart Train**, and **Luas** services - **[View Screenshot](https://github.com/tsokac2/newirishlife/blob/main/static/wireframes/google_maps_overview.png)**.

## WORK
Introduction and quick links of the most popular Irish online recruitment sites with an additional section for online education possibilities.

Formatted in two main sub-sections:
* **_START HERE_** Most popular job search services for the Irish job market.
* **_BACK TO SCHOOL_** Most popular online courses and full-time education institutions.

## LIFE
Section with life essentials factors after moving to Ireland.

Formatted in three main sub-sections:
* **_ACCOMMODATION_** Online rental agencies.
* **_MOBILE NETWORKS_** Mobile/internet networks providers.
* **_GROCERY SHOPS_** Irish Top food chains for grocery shopping.

**[Back to content](#contents)**

## LOGIN
Section with the option to **[LOGIN](https://newirishlife.herokuapp.com/accounts/login/)** to a user profile for full website management.

Formatted in three main sub-sections:
* **_Enter your login details!_** Login form including inputs fields for; _Username or e-mail_ and  _Password_.
* Call-to-action links; **_"Remember Me"(save login details)_**, **_[Forgot Password?](https://newirishlife.herokuapp.com/accounts/password/reset/)_**, **_[Create profile](https://newirishlife.herokuapp.com/accounts/signup/)_** link.
* Overview of the website purpose displayed in four cards - **[TRIP](https://newirishlife.herokuapp.com/trip)**, **[WORK](https://newirishlife.herokuapp.com/work)**, **[LIFE](https://newirishlife.herokuapp.com/life)**, **[SHOP](https://newirishlife.herokuapp.com/products/)**.
* Introduction of web page purpose and what value it is bringing to an end-user.

## SIGNUP
Section with the option to **_[Create profile](https://newirishlife.herokuapp.com/accounts/signup/)_** for full website management.

Formatted in three main sub-sections:
* **_[Create profile](https://newirishlife.herokuapp.com/accounts/signup/)_** Registration form including inputs fields for; __E-mail address_, _E-mail address confirmation_, _Username_, _Password_, _Password (again)_, and _SIGN UP_ button.
* Call-to-action link: **_"Already have an account? [Login](https://newirishlife.herokuapp.com/accounts/login/)"_**.
* Overview of the website purpose displayed in four cards - **[TRIP](https://newirishlife.herokuapp.com/trip)**, **[WORK](https://newirishlife.herokuapp.com/work)**, **[LIFE](https://newirishlife.herokuapp.com/life)**, **[SHOP](https://newirishlife.herokuapp.com/products/)**.
* Introduction of web page purpose and what value it is bringing to an end-user.

**[Back to content](#contents)**

## PROFILE
Section for Active User profile details and shipping details.

Formatted in three main profile sections:
* **_Profile Details_**  section includes; _Profile Image_, _Full Name_, _Username_, _Email_, _Create Date_.
* **_Delivery address user details_**:
    * Full name
	* Phone number
	* Street address 1
	* Street address 2
	* City
	* County
	* Postcode
	* Country
* **Order History** section includes order card element with order details; 
    * Link Order number for full order details.
    * Order data
    * Order Items
    * Total amount spent
* Call-to-action buttons: **Logout**, **Update Details**, **DELETE PROFILE**.

## SHOP
A section that offers traditional Irish Souvenirs purchasing options.

Formatted in three main profile sections:
* Section introduction with an image slide show.
* Categorise menu including _search_ input field and product _sorting_ options.
* **20** Products cards elements with the following details:
    * Product Name (action link)
    * Product Image (action link)
    * Product Price (action link)
    * Product Rating
    * Product Category (action link)

## PRODUCT DETAILS
A section for each individual product and call-to-action buttons.

Formatted in four main profile sections:
* Categories menu including a search input field.
* Product image slide show with image thumbnails.
* Product detail card including:
    * Product Name 
    * Product Rating 
    * Special Offer 
    * Product Price 
    * Quantity input field 
    * **["Keep Shopping"](https://newirishlife.herokuapp.com/products/)**
    * "Add To Bag"(action link)
* Product description section.

**[Back to content](#contents)**

## BAG
A section review and start **"Checkout"** process for requested items.

Formatted in two sections:
* Shopping **[BAG](https://newirishlife.herokuapp.com/bag/)** Total spending amount including:
    * Bag Total amount
    * Delivery charges amount
    * Grand Total amount
    * **["Keep Shopping"](https://newirishlife.herokuapp.com/products/)** button
    * The "Checkout" button
* **[BAG](https://newirishlife.herokuapp.com/bag/)** Products info section contains a product card element with the following details and call-to-action buttons/links:
    * Product Name
    * Product Image
    * Product Rating
    * Product SKU number
    * Product Price
    * Product Description
    * Product Quantity input field
    * Update button
    * **"X"** remove an item from the shopping **[BAG](https://newirishlife.herokuapp.com/bag/)** button

## CHECKOUT
A section review and finish **"Checkout"** process for requested items.

Formatted in two sections:
* _"Complete your order"_ form including the following form sections:
    * User Details
    * Shipping details
    * Payment Details
* Summary section includes:
    * Number of Items
    * Order Item details
    * Order Total
    * Delivery Cost 
    * Grand Total

## FOOTER
Replicated through all website sections.

Formatted in 4 sections:
* Mani menu links including **[HOME](https://newirishlife.herokuapp.com/)**, **[TRIP](https://newirishlife.herokuapp.com/trip)**, **[WORK](https://newirishlife.herokuapp.com/work) [LIFE](https://newirishlife.herokuapp.com/life)**.
* _Newsletter_ user form with inputs fields: _Name_, _Email_ and _Submit_ button.
* Social links for sharing purposes including **[Instagram](https://www.instagram.com/)**, **[Twitter](https://twitter.com/)**, **[Facebook](https://www.facebook.com/)**, **[Pinterest](https://www.pinterest.ie/)**.
* Credits with developer **[website link](http://www.tomislavsokac.com/home)**.

## CROSS-PROJECT FEATURES
* Alert messages for action confirmation regarding call-to-action purposes **[View Screenshot](https://github.com/tsokac2/newirishlife/blob/main/static/wireframes/messages_overview.png)**.
* **_Quick Links..._** Quick link option for precise user search in specified link area - **[View Screenshot](https://github.com/tsokac2/newirishlife/blob/main/static/wireframes/quicklinks.png)**.
* Image slide-show representation section elements.
* Welcoming **[HOME](https://newirishlife.herokuapp.com/) _"HERO"_** section; **[HOME](https://newirishlife.herokuapp.com/)** image composition section followed with four cards with **[TRIP](https://newirishlife.herokuapp.com/trip)**, **[WORK](https://newirishlife.herokuapp.com/work)**, **[LIFE](https://newirishlife.herokuapp.com/life)**, and **[SHOP](https://newirishlife.herokuapp.com/products/)** headings is replicated through the website.

### Features Left to Implement
Expansion plan:
* Implementing "post a comment" section in a footer, regarding specific website content and website idea proposals.
* Implement section for all necessary documentation in Ireland, regarding and PPS number, Bank Account option.
* Implement section regarding social events and gathering for necessary user connection expansion.
* Offer **_" Jobs Adds"_** section for recruitment agencies  - a connection between end-user and possible employer or recruitment agent.
* Create an email alert for admin and a friendly auto reminder for a user in case the user didn't finish the **_"Checkout/Payment"_** process.


**[Back to content](#contents)**

****

# TECHNOLOGIES USED

## # [HTML](https://en.wikipedia.org/wiki/HTML)
**Semantic elements**: _nav_, _section_, _footer_, _div_(content division element), _span_(inline container), _i_ (text element).

## # [CSS3](https://en.wikipedia.org/wiki/CSS)
**Modules:** Borders, Background and text-effects, Flexible Box Layout, CSS Grid Layout, CSS Transitions, CSS Image Values & Replaced Content, CSS Values & Units.

## # [SASS PRE-PROCESSOR](https://sass-lang.com/)
**TOOLS INCLUDED:**
* SASS interpolation
* SASS Mixings - Responsive layout functions
* SASS Variables
* SASS Nesting
* SASS Compiler

**COMPILER IMPLEMENTATION:**
* Open Command Prompt
* Navigate to the root project folder
* Enter commands in the following order:
  * `npm init --yes` - **PRESS ENTER**
  * `npm i -g node-sass` - **PRESS ENTER**
  * In `{} package.json` file under the `"scripts"` type the **[FOLLOWING](https://github.com/tsokac2/newirishlife/blob/main/static/wireframes/sass_01.png)**
* To start **SASS Compiler** enter the following command: `npm run watch` - **PRESS ENTER**
* If no errors the compilation process _NPM SERVER_ will start with the following console log message:
    ```
    > new@1.0.0 watch C:\Users\Tomislav\Desktop\new
    > node-sass -o assets/css assets/scss/index.scss -w
    ```
**SASS IMPLEMENTATION AND FOLDER STRUCTURE**
* Create the following folder structure:
  * assets/scss/abstracts - global SASS **variables** and **mixins** function
  * assets/scss/base - global styles for html, body and special helper classes
  * assets/scss/components - carousel image slideshow, small screen navigation menu
  * assets/scss/layout - styling for _HOME_, _TRIP_, _WORK_, _LIFE_, _TIPS_, _SIGN UP_, _LOGIN_
  * assets/scss/_index.scss - referencing all `*.scss` files in folder structure, **[EXAMPLE](https://github.com/tsokac2/newirishlife/blob/main/static/wireframes/sass_02.png)**
  * **SASS RESPONSIVE Mixins** function **[EXAMPLE](https://github.com/tsokac2/newirishlife/blob/main/static/wireframes/sass_03.png)**
* All files in the above folders **MUST** be named with the following naming conventions: `_filename.scss`

**[Back to content](#contents)**

## # [NODE.JS](https://nodejs.org/en/)
* Use for NPM `package.json` file implemetation in to project root

## # [NPM](https://www.npmjs.com/)
* Package manager - Use package - `node-sass`

## # [JAVASCRIPT](https://www.javascript.com/)
Features: _Dom Events_, _Validation of User’s Input_, _Else and If Statement_, _Handling Events_,  _In Built Function_

## # [JQUERY](https://fonts.google.com/)
**APPLIED jQuery DOM EVENTS** for highlighting **_"Quick Links"_** cards elements.

**[TRIP](https://newirishlife.herokuapp.com/trip)**, **[WORK](https://newirishlife.herokuapp.com/work)**, and **[LIFE](https://newirishlife.herokuapp.com/life)** sections are containing **_Quick Links_** card elements.

Every card element contains the _MAIN LINK_ source to the external services provider and a **_"Quick Links..."_** button element for loading detailed links when the user chose the services provider destination. **[EXAMPLE](https://github.com/tsokac2/newirishlife/blob/main/static/wireframes/quicklinks_life.png)**

**_base.html_** template contains <div class="blur"> just after opening tag for the background _"fade-out"_ effect

**jQuery DOM Events** used for above-mentioned cards element functionality:

* Element with id **#showLinks1** was clicked
* `var thisCardLinkShow = "." + this.id + "-grid";` checking for `<div>` element with class `.showLinks1-grid`
* `$(thisCardLinkShow).show(300)` referring to `this` element to `.show()` with speed of 300 milliseconds
* `$(".blur").fadeIn(400)` loading background "blur" effect with speed of 400 milliseconds
* `$(thisCardLinkShow).addClass("rel-card");` adding class `.addClass("rel-card")` to element that is referring to `this` element
* `$("#Card1").addClass("wrap-rel");`  adding class `.addClass("rel-card")` to element with id **Card1**

The process is replicated for the `<button id="#hideLinks1">` element with the id of `#hideLinks1` for the "hiding" effect with `.removeClass("wrap-rel");` - **[SOURCE CODE](https://github.com/tsokac2/newirishlife/blob/main/static/js/cards.js)** from lines **9 - 14** 

If user click anywhere on the screen _"loaded"_ elements will _"hide"_ and that is achieved with following `.click()` DOM effect on `<div class="blur>`.
`.blur` element contains absolute position properties with a z-index of 1000: **[SOURCE CODE](https://github.com/tsokac2/newirishlife/blob/main/static/js/cards.js)** from lines **34 - 38** 

**FULL SOURCE CODE:** for jQuery Cards DOM Events **[cards.js](https://github.com/tsokac2/newirishlife/blob/main/static/js/cards.js)**

**[Back to content](#contents)**

## # [BOOTSTRAP v4.5.2](https://getbootstrap.com/docs/4.5/getting-started/introduction/)
* Bootstrap was used to assist with the responsiveness and styling of the website
* Mani layout control - responsive layout usage - helper classes included - example -  .mt, .pt, .d-none .d-md-block, .col, col-sm, col-md, col-lg, etc...

## # [PYTHON DJANGO](https://www.djangoproject.com/)
Python Modules Full list in **[requirements.txt](https://github.com/tsokac2/newirishlife/blob/main/requirements.txt)**

## # [POSTGRESQL](https://www.postgresql.org/)
PostgreSQ open source object-relational database system.

## # [STRIPE](https://stripe.com/ie)
Stripe's software and APIs online payments provider.

For testing product purchasing and ordering functionality use the following details:

| **Title** | **Database Key** | **Field Type** | **Validation** |
--- | --- | --- | ---
 Username | user | OneToOneField 'User' |  on_delete=models.CASCADE
 Full Name | default_full_name | CharField | max_length=200, null=True, blank=True
 Phone number | default_phone_number | CharField | max_length=20, null=True, blank=True
 Address Line1 | default_address_line1 | CharField | max_length=80, null=True, blank=True
 Address Line2 | default_address_line2 | CharField | max_length=80, null=True, blank=True
 Town/City | default_town_or_city | CharField | max_length=40, null=True, blank=True
 County | default_county | CountryField | blank_label='County', null=True, blank=True
 Postcode | default_postcode | CharField | max_length=20, null=True, blank=True
 Country | default_country | CountryField | blank_label='Country', null=True, blank=True

More details for the **"CHECKOUT"** testing steps view in _*.xlsx_ file test case number: **[TC021](https://github.com/tsokac2/newirishlife/blob/main/static/wireframes/M4_Testing.xlsx)**

## # [AWS S3](https://aws.amazon.com/s3/)
Amazon Simple Storage Service (Amazon S3) object storage service.

AWS S3 bucket was used for storing the following static files:
* Image file for a specific section and custom png icons
* JavaScript files
* Global index.css file
* Downloads files
* Media files for SHOP section - 3 images pre one product item

**[Back to content](#contents)**

## # [EMAILJS](https://dashboard.emailjs.com/sign-in)
**IMPLEMENTATION**
* Add New Service - Gmail
* Email Templates - Create New Template
* Use following syntax for form attributes, syntax {{form_name}}
* SENT Email content from a user
* Select the Auto-Reply option and place the following: **_SUBJECT**: On behalf of all of us from New Irish Life, welcome onboard!_
* **WELCOMING** **[Email](https://github.com/tsokac2/newirishlife/blob/main/static/wireframes/email.png)** content sent to the user after successful submission

**SCRIPTS INTEGRATION:**
 * Before closing **`<head>`** element place following **CDN** script tag:
    * `<script src="https://cdn.jsdelivr.net/npm/emailjs-com@2/dist/email.min.js"></script>`
  * Place following call-back function after **CDN** link

  ```
  <script type="text/javascript">
        (function() {
        emailjs.init("user_hI6S08d1aK1XKKU2VWtOI");
        })();
  </script>
  ```
  * Check `User ID` under "Integration" option on EmailJS dashboard
  * Create `sendEmail` function **[CODE EXAMPLE](https://github.com/tsokac2/newirishlife/blob/main/static/js/emailnews.js)** from lines **88 - 103** 

**FROM VALIDATION DEVELOPMENT**
* Create **[EventTarget](https://github.com/tsokac2/newirishlife/blob/main/static/js/emailnews.js)** method addEventListener() sets up a function that will be called whenever the specified event is delivered to the target, in this case `newsletter()` function - **[CODE EXAMPLE](https://github.com/tsokac2/newirishlife/blob/main/static/js/emailnews.js)** from lines **1 - 3** 
*  Create 2 validation function for UX purposes, `validateName()` and `validateEmail()` function.
* `validateName()` function is _**returning**_ Boolean value `true` or `false` that is stored in empty variable `var valid;` depending of a user input string value - **[CODE EXAMPLE](https://github.com/tsokac2/newirishlife/blob/main/static/js/emailnews.js)** from lines **5 - 22**
* Implement call-back functions regarding what kind of input value was submitted by a user.
* `pushSuccessFor()` function is adding a `.success` class to the input element when user input is valid - **[CODE EXAMPLE](https://github.com/tsokac2/newirishlife/blob/main/static/js/emailnews.js)** from lines **55 - 58**
* User email validation is stored in the `validateEmail()` function with a call-back function that is checking user email - **[SOURCE](https://github.com/tsokac2/newirishlife/blob/main/static/js/emailnews.js)**
* To get a valid email id we use a regular expression
* Regular Expression Pattern : `/^(([^<>()\[\]\\.,;:\s@"]+(\.[^<>()\[\]\\.,;:\s@"]+)*)|(".+"))@((\[[0-9]{1,3}\.[0-9]{1,3}\.[0-9]{1,3}\.[0-9]{1,3}])|(([a-zA-Z\-0-9]+\.)+[a-zA-Z]{2,}))$/`
* `testEmail()` function:

  ```
    function testEmail(email) {
        return /^(([^<>()\[\]\\.,;:\s@"]+(\.[^<>()\[\]\\.,;:\s@"]+)*)|(".+"))@((\[[0-9]{1,3}\.[0-9]{1,3}\.[0-9]{1,3}\.[0-9]{1,3}])|(([a-zA-Z\-0-9]+\.)+[a-zA-Z]{2,}))$/.test(email);
    };
  ```

* To submit user data to the server we are declaring `send()` function in variable `var send = function(){...};` and calling that function when submit `<button>` is triggered - **[CODE EXAMPLE](https://github.com/tsokac2/newirishlife/blob/main/static/js/emailnews.js)** from lines **60 - 76**

* Validation tests are covered in **[TESTING.MD](https://github.com/tsokac2/newirishlife/blob/main/TESTING.md)** file

**[Back to content](#contents)**

## # [GOOGLE CDN's](https://fonts.google.com/) and [GOOGLE API](https://developers.google.com/maps/gmp-get-started#quickstart)
* Google Fonts - **[Merienda](https://fonts.google.com/specimen/Merienda?preview.text=&preview.text_type=custom&query=mer)**
* Google Fonts - **[Lato](https://fonts.google.com/?preview.text=&preview.text_type=custom&query=LATO)**
* Google Fonts - **[Josefin](https://fonts.google.com/specimen/Josefin+Sans?preview.text_type=custom)**

**GOOGLE API IMPLEMENTATION STEPS:**
  * Pick Google Maps product **[More info](https://developers.google.com/maps/gmp-get-started#quickstart)**
  * Create a project.
  * Set up a billing account.
  * Enable APIs associated with the products you picked.
  * Create an API key-  documentation source - **[API Key](https://developers.google.com/maps/documentation/javascript/get-api-key)**
  * API keys for frontend-only applications cannot be hidden like is stated on the following link **[Hide API Keys](https://gist.github.com/derzorngottes/3b57edc1f996dddcab25)**, developers **[Comment](https://github.com/tsokac2/newirishlife/blob/main/static/wireframes/API_Secure.png)**

**SCRIPTS INTEGRATION:**
  * In `<head>` element place `<scripts>` in following order:

    ```
    <script src="assets/js/markerclusterer_compiled.js"></script>
    <script defer src="https://maps.googleapis.com/maps/api/js?key="YOUR API KEY"&callback=initMap"></script>
    <script src="assets/js/maps.js"></script>
    ```
  * Create `<div>` element with ID `<div id="map">` render map place
  * Marker Cluster CDN - **[SOURCE](https://cdnjs.com/libraries/js-marker-clusterer)**
  * Creating call-back function in `<script src="assets/js/maps.js"></script>` -  **[CODE EXAMPLE](https://github.com/tsokac2/newirishlife/blob/main/static/js/maps.js)** from lines **1 - 36** 

* `function initMap() {..}` maps location on a major scale in this case Dublin, Ireland
* `google.maps.event.addDomListener(window, "resize", function() {...}` adding Google Maps DOM listener
* `let busMarkerIcon = {...}` creating custom map marker with `scaledSize` property
* `const Bus747Stop = new google.maps.Marker({...});` pointing to Bus Stop for 747 Dublin Bus line for Dublin Airport

**FULL SOURCE CODE:** GOOGLE MAPS API **[maps.js](https://github.com/tsokac2/newirishlife/blob/main/static/js/maps.js)**

## # [HEROKU](https://www.heroku.com)
* Cloud platform service used for hosting a "live" version of the project

## # [JASMINE BEHAVIOR-DRIVEN JavaScript](https://jasmine.github.io)
* Full testing and implementation process described in **[TESTING.MD](https://github.com/tsokac2/newirishlife/blob/main/TESTING.md)** file 

## # [FONTAWESOME](https://fontawesome.com/) 
* Use mostly for menu items and across projects elements

## # [GIT](https://git-scm.com/)
* Distributed version control system

## # [GITHUB](https://github.com/)
* Project files hosting platform

## # [IDE Visual Studio Code](https://code.visualstudio.com/)
* Project code editor 

## # [ADOBE PHOTOSHOP](https://www.adobe.com/)
* Images preparation - Logo Design

## # [ADOBE ILLUSTRATOR](https://www.adobe.com/)
* Logo Design 

## # [BALSAMIQ WIREFRAMES](https://balsamiq.com/) 
* Wireframes Design

## # [AM I Responsive?](http://ami.responsivedesign.is/)
* Multi-Device Website Mockup Generator was used to create the project Mockup image

**[Back to content](#contents)**

****

# TESTING

### Strategy and planning
* Testing is required on all features and user stories documented in this README file.
* All clickable links must redirect to the correct pages and sections.
* HTML Code must pass through the **[W3C HTML Validator](https://validator.w3.org/#validate_by_uri)**.
* CSS Code must pass through the **[W3C CSS Validator](https://jigsaw.w3.org/css-validator/)**.
* JavaScript code must pass through the **[JSHint Validator](https://jshint.com/)**.
* Python Code must pass through **[PEP8 Validator](http://pep8online.com/)**.
* Testing through **[Django Unit Testing Framework](https://docs.djangoproject.com/en/dev/internals/contributing/writing-code/unit-tests/)**.


### Test Cases and Description

![Test Cases](https://github.com/tsokac2/newirishlife/blob/main/static/wireframes/Test_Cases.JPG)

### Access Requirements
The tester must be a Superuser to have access to the Django admin console to test the full functionality of the application.

### Regression Testing
All features previously tested during development in a local environment must be regression tested in production on the live website.

### Assumptions and Dependencies
Testing is dependent on the website being deployed live on Heroku.

### Out of Scope
Only test cases listed under High-Level Test Cases will be performed as part of this testing effort.

### Test Results
All processed tests and results are described in detail **[HERE](https://github.com/tsokac2/newirishlife/blob/main/TESTING.md)**

**[Back to content](#contents)**

****

# DEPLOYMENT

**[PROJECT LINK](https://newirishlife.herokuapp.com/)**

### LOCAL PROJECT SETUP:
* Create a new repository on **[GitHub](https://github.com)**
* Create a project folder on the local device
* Start **[CMD](https://en.wikipedia.org/wiki/Cmd.exe)** on the local device and navigate to the root folder of the project
* Initialize project root folder with the following CMD command: `git init`
* Create _README.MD_ file with CMD command: `echo #New Irish Life > README.md`
* Initiate `git add .` command in CMD project root folder
* Initiate commit `git commit -m "Test first commit"` command in CMD project root folder
* Create a connection with the local device and GitHub repository with the CMD command 
  ```
  git remote add origin https://github.com/username/project_repo_name.git
  ```
* Initiate push command `git push -u origin master`
* Make regular commits after every project change with proper commit message more info in **[Git Commit Message](https://chris.beams.io/posts/git-commit/#separate)**
* Use `git push` command in CMD for code commits 

**[Back to content](#contents)**

## DEPLOYMENT TO HEROKU
### Create application:
**1.** Navigate to **[HEROKU](https://id.heroku.com/login)** and log in

**2.** Click on the _New_ button

**3.** Select create a _New App_

**4.** Enter the app name

**5.** Select region

### Configure connection to Github Repository
**1.** Click the **_Deploy_** tab and select **_GitHub - Connect to GitHub_**

**2.** Select GitHub

**3.** Enter the repository name for the project and click search

**4.** When repo has been found, click the _connect_ button

### Set environment variables:
* Click the **_Settings_** tab and then click the **_Reveal Config Vars_** button and add the following:

    **1.** AWS_ACCESS_KEY_ID

    **2.** AWS_SECRET_ACCESS_KEY

    **3.** DATABASE_URL

    **4.** EMAIL_HOST_PASS

    **5.** EMAIL_HOST_USER

    **6.** SECRET_KEY - **[Random Key Generator](https://randomkeygen.com/)**

    **7.** STRIPE_PUBLIC_KEY

    **8.** STRIPE_PUBLIC_KEY

    **10.** STRIPE_WH_SECRET

    **11.** USE_AWS

### Enable automatic deployment:
**1.** Select _Deploy_ tab and click _Enable Automation Deploys_

**2.** Click the _Deploy_ button

**3.** When the app is created check the logs for deployment errors, if none, click the _"View"_ button

### LOCAL HOSTING
**Note:** The project will not run locally unless the user sets up a _SECRET-KEY_ with **[Random Key Generator](https://randomkeygen.com/)**

**_These details are private and not disclosed in this repository for security purposes._**

Once the project has been loaded into an IDE of choice, run the following command in the shell to install all the required packages: pip install -r requirements.txt.

To run a local Django server run the following command in CMD:
`python manage.py runserver`

**[Back to content](#contents)**

****

# CREDITS
* Intro pitch - **[*"The Hobbit: An Unexpected Journey"*](https://en.wikipedia.org/wiki/The_Hobbit_(film_series))**
* Website images source - **[CARROLLS IRISH GIFTS](https://www.carrollsirishgifts.com/)**
* Website images source - **[UNSPLASH](https://unsplash.com/s/photos/smartphone)**
* Website images source - **[PIXABAY](https://pixabay.com/photos)**
  * **[User: wiredsmartio](https://pixabay.com/users/wiredsmartio-14931632/)**
  * **[User: geralt](https://pixabay.com/users/geralt-9301/)**
  * **[User: ds_30](https://pixabay.com/users/ds_30-1795490/)**
  * **[User: pexels](https://pixabay.com/users/pexels-2286921/)**
  * **[User: firmbee](https://pixabay.com/users/firmbee-663163/)**
  * **[User: wokandapix](https://pixabay.com/users/wokandapix-614097/)**
  * **[User: publicco](https://pixabay.com/users/publicco-5009832/)**

* Home page icons - **[Flaticon](https://www.flaticon.com/)**

### CODE
* **[Bootstrap Carousel Fade Effect](https://silvawebdesigns.com/how-to-change-the-bootstrap-4-carousel-to-a-fade-transition-instead-of-slide/)**
* **[Resizing Google Maps markers](https://stackoverflow.com/questions/15096461/resize-google-maps-marker-icon-image)**
* **[Jasmine-jQuery: Set of jQuery helpers](https://bowercdn.net/c/jasmine-jquery-2.1.1/lib/jasmine-jquery.js)**
* Project was developed by following the Code Institute video course **'Boutique Ado'**.

### ACKNOWLEDGEMENTS
* **Anna Villanueva** for always fun and informative mentorship sessions.

**[Back to content](#contents)**

****