
##############
## Project One: SimApp
################
BuiltWith : CakePHP Framework Version 3
Features:
    Simple and Object Oriented
    Model View Controller Architecture
    Compatible with Php version 4 and 5
    Automatic CRUD scripting via Bake script
    Build in Validation
    Provide default helpers for HTML, CSS, JavaScript, XML, Form, Ajax, etc
    SEO friendly URL’s
    Convention over Configuration
    Router for mapping Urls and handling extensions
    In built components like- Security, Session, Cookies, Email and request Handling.
    Utility classes for working with Files, Folder, Array and more.
    Allow caching

Steps Followed to setUp CakePhp Instance:
## Installation
1. Create Database with name SimApp and Table called products.
2. Download [Composer](https://getcomposer.org/doc/00-intro.md) or update `composer self-update`.
3. Run `php composer.phar create-project --prefer-dist cakephp/app [app_name]`.
4. Run `bake/cake bake all products`.

Steps Followed to run the test suits (Never ijmplemented the testsuits before using cakePhp but tried to install phpunit):
5. Run `php composer.phar require --dev phpunit/phpunit:"^5.7|^6.0"`.
6. Run `phpunit tests`.
7. Tried to run custom function with no success, not creating database products using test script:
    Run `phpunit tests/TestCase/Controller/ProductsControllerTest.php`.
    Run `phpunit tests/TestCase/Model/Table/ProductsTableTest`.  


TimeTaken:
    1. Set up instance and create CRUD functionality for products : 1hour
    2. Test Suits - Previously, did not have experience in this area using CakePhp. Still tried but unable to create a product table and add data using test script. The script is deleting the table again and again. With help and self learning, can work on it, but need time to understand the whole testing concept in cakePhP.
    **However, I have used RFT an automatic testing tool for testing the website during my Studies.**


############
## Project Two: WiseLiving
############
BuiltWith : CodeIgniter
Details: Project implemented as assignment as part of my Master Studies in one of Unit called Web Development.
Project Requirement:
    1. Add, edit, delete functionality of products.
    2. Implement theme
    3. Wishlist functionality
    4. Admin add products and can assign that product to one or more stores with their different prices at different stores at different locations.
    5. Showing lowest price products and filter the products based on location and product name or description.
    6. Show and compare the lowest prices with respect to displayed product. The lowest price products are filtered with price, name and description.

Features: Basically used codeIgniter due to project requirement but have many features such as:
      •	It is fast and reliable framework which have the capability of extending PHP coding to get specific functions in your program.
      •	It is compatible with most web servers, numerous operating systems and platforms.
      •	MVC architecture helps to provide more secured and reliable development through CodeIgniter. Therefore, it is secure & user friendly.
      •	It is easy to learn, adopt and deploy and has a good collection of possessed libraries.
      •	CodeIgniter has an outstanding performance as well as presentation.
Basic Features:
        Model-View-Controller Based System
        Extremely Light Weight
        Full Featured database classes with support for several platforms.
        Query Builder Database Support
        Form and Data Validation
        Session Management
        Image Manipulation Library (cropping, resizing, rotating, etc.)
        File Uploading Class
        FTP Class
        Localization
        Pagination
        Data Encryption
        Full Page Caching
        Error Logging
        Search-engine Friendly URLs
        Flexible URI Routing
        Support for Hooks and Class Extensions
        Large library of “helper” functions

TimeTaken: Cannot specify, as completed in chunks.
**Moreover, it was a new framework for me and I worked from scratch.**


***Note: Database of both instance is in 'db' folder on root directory of project.
