<div align="center">

# ***E-Shop***

![Homepage Preview](docs/readme_images/frontpage-img.png)

***E-SHOP is a dynamic e-commerce platform offering a wide range of products — primarily clothing — with customizable options. Customers can browse items by category, size and color, or quickly locate specific products using the built-in search function in the navigation bar.***

***By registering, users can save their shipping details for faster future checkouts and gain access to a personal dashboard where all past orders, transactions, and receipts are stored in a clean, easy-to-read format.***

***With secure transaction processing, shoppers can make purchases with confidence and enjoy a smooth, user-friendly experience.***

[***See Live Project Here***](https://app-e-shop-c5039fdaf8fd.herokuapp.com/)

</div>

<div align="center">

## ***Project Goals***

</div>

***The goal of this project was to develop a fully functional and scalable e-commerce platform using Django, emphasizing modular design, secure deployment, and real-world integrations. The key objectives included:***

- *Building the backend using Python and the Django framework to handle business logic, data management via ORM, and secure user authentication with a custom Django user model.*

- *Creating a responsive and user-friendly frontend using HTML5, CSS3, JavaScript, and the Bootstrap framework for styling and layout.*

- *Utilizing Django Templates for server-side rendering and dynamic content delivery.*

- *Implementing payment processing through integration with the PayPal SDK, enabling real-world transaction functionality.*

- *Managing static and media files locally during development and in production via AWS S3 for cloud storage.*

- *Securing cloud resources by managing access permissions with AWS IAM, ensuring proper authorization controls.*

- *Preparing the application for production deployment using Gunicorn as a reliable WSGI server.*

- *Using SQLite as a lightweight development database.*

- *Designing RESTful APIs and patterns to facilitate dynamic frontend and backend interactions.*

- *Employing environment variables (os.environ) for secure and flexible configuration management.*


***These goals reflect a comprehensive approach to building a professional e-commerce system that balances frontend usability, backend robustness, and secure cloud deployment.***

<div align="center">

## ***User Goals:***

</div>

***The primary goal for users is to have a seamless and secure online shopping experience. E-SHOP is designed to provide:***

- *An intuitive interface for browsing and searching products by category, size, and color.*

- *A smooth and responsive shopping experience across devices.*

- *Secure user registration and login, with access to a personal account area.*

- *The ability to manage profile information and reset passwords if needed.*

- *A personalized dashboard displaying past orders and transaction history.*

- *A fast and reliable checkout process with secure PayPal payment integration.*

- *Saved shipping details to simplify future purchases.*

***Overall, E-SHOP aims to offer a clean, trustworthy, and convenient platform for purchasing customizable clothing and electronics online.***

<div align="center">

## ***1 - UX***

</div>

### ***1.1 - User Stories:***

### ***1.1.1 - First Time User Goals:***
- *a) As a First Time User, I want to quickly understand the purpose of the website.*
- *b) As a First Time User, I want to browse clothes.*
- *c) As a First Time User, I want to search for a specific clothing wear.*

### ***1.1.2 - Returning User Goals:***
- *a) As a Returning User, I want to make a purchase.*
- *b) As a Returning User, I want to register to the site.*
- *c) As a Returning User, I want to contact customer support.*

### ***1.1.3 - Frequent User Goals:***
- *a) As a Frequent User, I want my purchases to go faster.*
- *b) As a Frequent User, I want to see all my orders.*
- *c) As a Frequent User, I want change my account details.*



## 1.2 - Design

### 1.2.1 - Color Scheme:
![Color Scheme - image](https://github.com/user-attachments/assets/592674b0-c9e6-4724-931b-73bba8272bb0)

### 1.2.2 - Fonts:
<details>
    <summary>JuneGull, VarelaRound-Regular, Sans-serif</summary>
    <img src="https://raw.githubusercontent.com/GlennJohansson85/p5-shop/main/docs/images/1-ux/fonts.png" alt="JuneGull, VarelaRound-Regular, Sans-serif Font - image">
</details>
### 1.2.3 - Responsive Design

<details>
    <summary>Desktop, tablet and mobile view</summary>
    <img src="https://raw.githubusercontent.com/GlennJohansson85/p5-shop/main/docs/images/1-ux/responsive.png" alt="Desktop, tablet and mobile view - image">
</details>

# 2 - Wireframes

## 2.1 - Home:
<details>
    <summary>Desktop</summary>
    <img src="https://raw.githubusercontent.com/GlennJohansson85/p5-shop/main/docs/images/2-wireframes/home-large.png" alt="Home desktop wireframe - image">
</details>
<details>
  <summary>Tablet</summary>
  <img src="https://raw.githubusercontent.com/GlennJohansson85/p5-shop/main/docs/images/2-wireframes/home-medium.png" alt="Home tablet wireframe - image">
</details>
<details>
  <summary>Mobile</summary>
  <img src="https://raw.githubusercontent.com/GlennJohansson85/p5-shop/main/docs/images/2-wireframes/home-small.png" alt="Home mobile wireframe - image">
</details>

## 2.2 - All Products:
<details>
    <summary>Desktop</summary>
      <img src="https://raw.githubusercontent.com/GlennJohansson85/p5-shop/main/docs/images/2-wireframes/products-large.png" alt="products desktop wireframe - image">
</details>
<details>
  <summary>Tablet</summary>
  <img src="https://raw.githubusercontent.com/GlennJohansson85/p5-shop/main/docs/images/2-wireframes/products-medium.png" alt="products tablet wireframe - image">
</details>
<details>
  <summary>Mobile</summary>
  <img src="https://raw.githubusercontent.com/GlennJohansson85/p5-shop/main/docs/images/2-wireframes/products-small.png" alt="products mobile wireframe - image">
</details>

## 2.3 - Product Detail:
<details>
    <summary>Desktop</summary>
      <img src="https://raw.githubusercontent.com/GlennJohansson85/p5-shop/main/docs/images/2-wireframes/product_detail-large.png" alt="product_detail desktop wireframe - image">
</details>
<details>
  <summary>Tablet</summary>
  <img src="https://raw.githubusercontent.com/GlennJohansson85/p5-shop/main/docs/images/2-wireframes/product_detail-medium.png" alt="product_detail tablet wireframe - image">
</details>
<details>
  <summary>Mobile</summary>
  <img src="https://raw.githubusercontent.com/GlennJohansson85/p5-shop/main/docs/images/2-wireframes/product_detail-small.png" alt="product_detail mobile wireframe - image">
</details>

## 2.4 - Cart:
<details>
  <summary>Desktop</summary>
  <img src="https://raw.githubusercontent.com/GlennJohansson85/p5-shop/main/docs/images/2-wireframes/cart-large.png" alt="cart desktop wireframe - image">
</details>
<details>
  <summary>Tablet & Mobile</summary>
  <img src="https://raw.githubusercontent.com/GlennJohansson85/p5-shop/main/docs/images/2-wireframes/cart-medium-small.png" alt="cart tablet wireframe - image">
</details>

## 2.5 - Checkout:
<details>
  <summary>All devices</summary>
  <img src="https://raw.githubusercontent.com/GlennJohansson85/p5-shop/main/docs/images/2-wireframes/checkout.png" alt="checkout wireframe - image">
</details>

## 2.6 - Placing Order:
<details>
  <summary>Desktop</summary>
  <img src="https://raw.githubusercontent.com/GlennJohansson85/p5-shop/main/docs/images/2-wireframes/payments-l.png" alt="payments desktop wireframe - image">
</details>
<details>
  <summary>Tablet & Mobile</summary>
  <img src="https://raw.githubusercontent.com/GlennJohansson85/p5-shop/main/docs/images/2-wireframes/payments-m-s.png" alt="payments tablet & mobile wireframe - image">
</details>

## 2.7 - Dashboard:
<details>
  <summary>Desktop</summary>
  <img src="https://raw.githubusercontent.com/GlennJohansson85/p5-shop/main/docs/images/2-wireframes/dashboard-l.png" alt="dashboard desktop wireframe - image">
</details>
<details>
  <summary>Tablet & Mobile</summary>
  <img src="https://raw.githubusercontent.com/GlennJohansson85/p5-shop/main/docs/images/2-wireframes/dashboard-m-s.png" alt="dashboard tablet & mobile wireframe - image">
</details>

# 3 - Features

## 3.1 - Registration
<details>
  <summary>
    A user register to the website using this form. When the form has been successfully submitted the user recieves a message to activate her account through the activation email sent to her account.
  </summary>
  <img src="https://raw.githubusercontent.com/GlennJohansson85/p5-shop/main/docs/images/3-features/register.png" alt="Register Form - image">
</details>
<details>
  <summary>
    The activation email has the website name as the sender and 'Activation Email' as the subject, as a more user-friendly input.
  </summary>
  <img src="https://raw.githubusercontent.com/GlennJohansson85/p5-shop/main/docs/images/3-features/register-activation.png" alt="Account activation email - image">
</details>
<details>
  <summary>
    Clicking the link will redirect the user to the sign-in page, where they will be notified that their account has been successfully activated.
  </summary>
  <img src="https://raw.githubusercontent.com/GlennJohansson85/p5-shop/main/docs/images/3-features/register-activated.png" alt="Account activated success - image">
</details>

## 3.2 - Navbar
<details>
  <summary>
    The navbar contain the brand (I SHOP) which redirects to the homepage when clicked. A searchbar which searches for words in product name and categories based on input from user. Categories as a dropdown showing all clothing categories as links. A link "All products" which redirects the user to the products page. Accounts, a dropdown, with a link to the users´personal dashboard and a sign out button. Lastly, a cart which redirects the user to her cart and a "notify" showing the number of items in the cart.
  </summary>
  <img src="https://raw.githubusercontent.com/GlennJohansson85/p5-shop/main/docs/images/3-features/navbar-desktop.png" alt="Navbar with dropdowns in desktop view - image">
</details>
<details>
  <summary>
    The navbar in mobile view
  </summary>
  <img src="https://raw.githubusercontent.com/GlennJohansson85/p5-shop/main/docs/images/3-features/navbar-mobile.png" alt="Navbar mobile/tablet view - image">
</details>
<details>
  <summary>
    The navbar in mobile/tablet view with the toggler open.
  </summary>
  <img src="https://raw.githubusercontent.com/GlennJohansson85/p5-shop/main/docs/images/3-features/navbar-toggler-open.png" alt="Navbar with toggler open in mobile/tablet view - image">
</details>

## 3.3 - Homepage
<details>
  <summary>
    The main page, <strong>homepage</strong>, contains a intro text "LATEST TRENDS ARE HERE!" which dynamically rises and falls against a concrete-textured background, creating a subtle pulsating effect. Below the header, a grid showcases the most popular clothing items. Each card in the grid lifts slightly when hovered over, casting a shadow beneath it for added emphasis. Clicking on a card directs users to the detailed page of the selected clothing item. A prominent "See All" button is also available, guiding users to the product page where they can explore the full collection.
  </summary>
  <img src="https://raw.githubusercontent.com/GlennJohansson85/p5-shop/main/docs/images/3-features/homepage.png" alt="View of the homepage - image">
</details>

## 3.4 Products
<details>
  <summary>
    On the <strong>products page</strong>, where all clothing items are located, users can see six clothing items at a time. By using the paginator at the bottom users can move back and forth based on the number of items. On the left side of the grid is a list of all the differenct clothing wears to choose from. Clicking on category will show only that category.
  </summary>
  <img src="https://raw.githubusercontent.com/GlennJohansson85/p5-shop/main/docs/images/3-features/products.png" alt="View of the product page - image">
</details>
<details>
  <summary>
    Clicking on an item redirects the user to the <strong>product detail page</strong>, where they can view the item in a larger size. After selecting a color and size, the user can add the item to their cart. At the bottom of the page, users can also read reviews from other customers.
  </summary>
  <img src="https://raw.githubusercontent.com/GlennJohansson85/p5-shop/main/docs/images/3-features/product_detail.png" alt="View of the product_detail page - image">
</details>
<details>
  <summary>
    The <strong>cart page</strong> showcases all selected items, including individual item details/costs and the overall total. Users can easily adjust quantities by adding or removing items, with the total cost updating dynamically. They can revisit product details by clicking on the product name (link) or proceed with the purchase using the checkout button.
  </summary>
  <img src="https://raw.githubusercontent.com/GlennJohansson85/p5-shop/main/docs/images/3-features/cart.png" alt="View of the cart page - image">
</details>

## 3.5 - Transaction
<details>
  <summary>
    The <strong>checkout page</strong> features a form that users must complete to finalize their purchase. For returning customers, the form is pre-filled with their previous details, ensuring a seamless and user-friendly experience.
  </summary>
  <img src="https://raw.githubusercontent.com/GlennJohansson85/p5-shop/main/docs/images/3-features/checkout.png" alt="View of the checkout form - image">
</details>
<details>
  <summary>
    The <strong>payments/"Place order" page</strong> is where the user review their order making sure all the details are correct before going through with the purchase.
  </summary>
  <img src="https://raw.githubusercontent.com/GlennJohansson85/p5-shop/main/docs/images/3-features/checkout.png" alt="View of the payments page - image">
</details>

# 4 - Reponsiveness



# 5 Technologies Used:

## 5.1 Languages Used:
* **[HTML5](https://en.wikipedia.org/wiki/HTML5)** - Markup language used for structuring web pages.
* **[CSS](https://en.wikipedia.org/wiki/Cascading_Style_Sheets)** - Styling language used for the presentation of the HTML elements.
* **[Python](https://www.python.org/)** - Programming language used for the backend of the application.
* **[SQL](https://en.wikipedia.org/wiki/SQL)** - Used for database queries (e.g., in SQLite or PostgreSQL databases).

## 5.2 Frameworks, Libraries & Programs Used:

### 5.2.1 Frameworks:
* **[Django](https://www.djangoproject.com/)** - High-level Python web framework for rapid development.
* **[Django Cloudinary Storage](https://django-cloudinary-storage.readthedocs.io/en/latest/)** - Integration with Cloudinary for media file management.
* **[Django Storages](https://django-storages.readthedocs.io/)** - Integration with different cloud storage solutions like AWS S3.

### 5.2.2 Libraries:
* **[requests](https://requests.readthedocs.io/)** - Library for making HTTP requests.
* **[django-environ](https://django-environ.readthedocs.io/)** - Configuration management library for reading environment variables.
* **[dj-database-url](https://pypi.org/project/dj-database-url/)** - Simplifies database configuration using URL format.
* **[boto3](https://boto3.amazonaws.com/v1/documentation/api/latest/index.html)** - AWS SDK for Python to interact with AWS services.
* **[Pillow](https://python-pillow.org/)** - Python Imaging Library for image processing.
* **[pyyaml](https://pyyaml.org/)** - YAML parser and emitter for Python.

### 5.2.3 Development Tools:
* **[Visual Studio Code](https://code.visualstudio.com/)** - Code editor used for development.
* **[GitHub Desktop](https://desktop.github.com/)** - GitHub client for managing repository and version control.
* **[GitHub](https://github.com/)** - Platform for version control and collaboration.
* **[Heroku](https://www.heroku.com/)** - Platform for deploying and running the app.
* **[ElephantSQL](https://www.heroku.com/)** - Database - Save user actions.
* **[Amazon AWS](https://aws.amazon.com/)** - Cloud services used for storage (static and media).
* **[PayPal](https://paypal.com/)** - Transaction Service.
* **[Postman](https://www.postman.com/)** - API testing tool.
* **[Agile Development](https://www.opentext.com/what-is/agile-development#:~:text=Agile%20development%20is%20a%20project,twelve%20principles%20of%20Agile%20development.)** - Aimed to work in accordance to Agile Development.

### 5.2.4 Other Libraries & Tools Used:
* **[Google Gmail](https://mail.google.com/)** - Used for email services (account and password verification).
* **[Temp Mail](https://temp-mail.org/)** - For creating temporary email accounts used for testing purposes.
* **[Bootstrap 5.0.2](https://getbootstrap.com/docs/5.0/getting-started/introduction/)** - Framework for responsive web design and styling.
* **[jQuery 3.7.1](https://jquery.com/)** - Library for manipulating the HTML DOM.
* **[Font Awesome](https://fontawesome.com/)** - Icons used throughout the application.
* **[Fontspace](https://www.fontspace.com/)** & **[1001Fonts](https://www.1001fonts.com/)** - Sources for fonts used in the design.
* **[Freepik](https://www.freepik.com/)** - Used for sourcing background images and other assets.
* **[Balsamiq Wireframes](https://balsamiq.com/wireframes/)** - Wireframing tool used in the design phase of the project.

# 6 - Testing

## 6.1 - W3C Validator Test
<details>
  <summary>
    Base.css - Result
  </summary>
  <img src="https://raw.githubusercontent.com/GlennJohansson85/p5-shop/main/docs/images/6-testing/base.css-w3c.png" alt="W3C Validater result of base.css - image">
</details>
<details>
  <summary>
    Navbar.CSS - Result
  </summary>
  <img src="https://raw.githubusercontent.com/GlennJohansson85/p5-shop/main/docs/images/6-testing/navbar.css-w3c.png" alt="W3C Validater result of navbar.css - image">
</details>

## 6.2 - Testing of User Stories (From Chapter 1)

### 6.2.1 - Testing of First Time User Goals:
<details>
  <summary>
    As a First Time User, I want to quickly understand the purpose of the website.
  </summary>
  <img src="https://raw.githubusercontent.com/GlennJohansson85/p5-shop/main/docs/images/6-testing/us-purpose.png" alt="First Time User Story - Purpose - image">
</details>
<details>
  <summary>
    As a First Time User, I want to easily navigate through the website.
  </summary>
  <img src="https://raw.githubusercontent.com/GlennJohansson85/p5-shop/main/docs/images/6-testing/us-navigate.png" alt="First Time User Story - Navigate - image">
</details>
<details>
  <summary>
    As a First Time User, I want to browse clothes.
  </summary>
  <img src="https://raw.githubusercontent.com/GlennJohansson85/p5-shop/main/docs/images/6-testing/us-browse.png" alt="First Time User Story - Browse - image">
</details>

### 6.2.2 - Testing of Returning User Goals:
<details>
  <summary>
    As a Returning User, I want check the items in my cart.
  </summary>
  <img src="https://raw.githubusercontent.com/GlennJohansson85/p5-shop/main/docs/images/6-testing/us-cart.png" alt="Returning User Story - Cart - image">
</details>
<details>
  <summary>
    As a Returning User, I want to make a purchase.
  </summary>
  <img src="https://raw.githubusercontent.com/GlennJohansson85/p5-shop/main/docs/images/6-testing/us-purchase.png" alt="Returning User Story - Purchase - image">
</details>
<details>
  <summary>
    As a Returning User, I want to register to the site.
  </summary>
  <img src="https://raw.githubusercontent.com/GlennJohansson85/p5-shop/main/docs/images/6-testing/us-register.png" alt="Returning User Story - Register - image">
</details>

### 6.2.3 - Testing of Frequent User Goals:
<details>
  <summary>
    As a Frequent User, I want to make my purchases faster.
  </summary>
  <img src="https://raw.githubusercontent.com/GlennJohansson85/p5-shop/main/docs/images/6-testing/us-faster-purchase.png" alt="Returning User Story - Faster Purchase - image">
</details>
<details>
  <summary>
    As a Frequent User, I want to see all my orders.
  </summary>
  <img src="https://raw.githubusercontent.com/GlennJohansson85/p5-shop/main/docs/images/6-testing/us-order-history.png" alt="Returning User Story - Order History - image">
</details>
<details>
  <summary>
    As a Frequent User, I want to change my account details.
  </summary>
    <img src="https://raw.githubusercontent.com/GlennJohansson85/p5-shop/main/docs/images/6-testing/us-update.png" alt="Returning User Story - Change Accounts details - image">
</details>

# 7. Deployment

## 7.1 GitHub Pages
The project was deployed to GitHub Pages using the following steps...
1. Log in to GitHub and locate the [p5-shop](https://github.com/GlennJohansson85/p5-shop)
2. At the top of the Repository (not top of page), locate the "Settings" Button on the menu.
3. Scroll down the Settings page until you locate the "GitHub Pages" Section.
4. Under "Source", click the dropdown called "None" and select "Main Branch".
5. The page will automatically refresh.
6. Scroll back down through the page to locate the now published site [p5-shop](https://github.com/GlennJohansson85/p5-shop) in the "GitHub Pages" section.

### 7.2 Forking the GitHub Repository
By forking the GitHub Repository we make a copy of the original repository on our GitHub account to view and/or make changes without affecting the original repository by using the following steps...
1. Log in to GitHub and locate the [p5-shop](https://github.com/GlennJohansson85/p5-shop)
2. At the top of the Repository (not top of page) just above the "Settings" Button on the menu, locate the "Fork" Button.
3. You should now have a copy of the original repository in your GitHub account.

### 7.3 Making a Local Clone
1. Log in to GitHub and locate the [p5-shop](https://github.com/GlennJohansson85/p5-shop)[p5-shop](https://github.com/GlennJohansson85/p5-shop)
2. Under the repository name, click "Clone or download".
3. To clone the repository using HTTPS, under "Clone with HTTPS", copy the link.
4. Open Git Bash
5. Change the current working directory to the location where you want the cloned directory to be made.
6. Type `git clone`, and then paste the URL you copied in Step 3.
```
$ git clone https://github.com/GlennJohansson85/p5-shop
```
7. Press Enter. Your local clone will be created.
```
$ git clone  https://github.com/GlennJohansson85/p5-shop
> Cloning into `CI-Clone`...
> remote: Counting objects: 10, done.
> remote: Compressing objects: 100% (8/8), done.
> remove: Total 10 (delta 1), reused 10 (delta 1)
> Unpacking objects: 100% (10/10), done.
```
Click [Here](https://help.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository#cloning-a-repository-to-github-desktop) to retrieve pictures for some of the buttons and more detailed explanations of the above process.

## 8.Credits
- All technologies beeing used mentioned in chapter 4.
- The people whom created the media and font files.
- Code Insitute