# CSCI5709 Assignment 3

## EnviClean
Keeping the environment clean is our motive. Hence the project name EnviClean. It is a garbage collection management system developed by Advanced Web Services - Group 6. Link to the EnviClean website - https://enviclean.herokuapp.com/.

* *Date Created*: 21 07 2021
* *Last Modification Date*: 21 07 2021

## Author
* [Dhrumil Amish Shah](dh416386@dal.ca) - *(Creator)*

## EnviClean Stack
* [React](https://reactjs.org/) - Front-end framework
* [Node](https://nodejs.org/) - Backend JavaScript runtime built on [Chrome's V8 JavaScript engine](https://v8.dev/)
* [Express](https://expressjs.com/) - Web framework for [Node](https://nodejs.org/)
* [MySQL](https://www.mysql.com/) - Relational database used for data persistence

## EnviClean Front-end
Below are the links to the EnviClean front-end website deployed on Heroku, EnviClean front-end GitHub repository and, feature Social Clean Reporter Management - EnviClean Patron front-end code developed by me for Assignment 3:
* [EnviClean Front-end](https://enviclean.herokuapp.com/) - Heroku deployment link
* [EnviClean Github Repository](https://github.com/DhrumilShah98/Group6_S21_EnviClean) - Main GitHub repository link
* [Feature Branch: Social Clean Reporter Management - EnviClean Patron](https://github.com/DhrumilShah98/Group6_S21_EnviClean/tree/patron) - Branch patron Github repository link (Developed by me).

## EnviClean Back-end
Below are the links to the EnviClean back-end website deployed on Heroku, EnviClean back-end GitHub repository and, feature Social Clean Reporter Management - EnviClean Patron back-end code developed by me for Assignment 3:
* [EnviClean Back-end](https://envicleanapi.herokuapp.com) - Heroku deployment link
* [EnviClean Github Repository](https://github.com/vishaldipakparmar/Group6_S21_EnviCleanAPI/tree/main) - Main GitHub repository link
* [Feature Branch: Social Clean Reporter Management - EnviClean Patron](https://github.com/vishaldipakparmar/Group6_S21_EnviCleanAPI/tree/patron) - Branch patron Github repository link (Developed by me).

## EnviClean Database
To persist the data, EnviClean uses Relational Database Management Service - MySQL.
* [Google Cloud Platform](https://console.cloud.google.com/) - MySQL database is hosted on GCP.
* [MySQL Workbench](https://www.mysql.com/products/workbench/) - Desktop client used to connect to the MySQL database hosted on GCP.

## Feature Developed: Social Clean Reporter Management - EnviClean Patron
I have implemented the Social Clean Reporter Management – EnviClean Patron feature for the EnviClean web application. This feature provides an interface for the EnviClean patron members to seamlessly identify all the trash they find when they are outside and upload it on the EnviClean website. Garbage collectors are intimated to make sure that the reported garbage is taken care of properly. This feature covers the following tasks:

* Enroll as a social clean reporter and become an EnviClean Patron.
* Create a post regarding the garbage found.
* View posts created by other users.
* View posts created by users themselves.
* Search posts (By address - street address, city, province, zip code)
* Delete posts created by users themselves which are not fulfilled by garbage collectors.

All the necessary details regarding the feature Social Clean Reporter Management - EnviClean Patron (i.e., sitemap, wireframes, task flow diagrams, process workflows, use cases and, click streams) is covered in Assignment 1, Project Proposal and Assignment 2.

Note - Fulfil patron post is part of the collectors' job. Collectors will fulfil patron posts (i.e., Collect garbage and mark it as status - FULFILLED). It is one of the tasks of another feature and will be implemented later by another team member under the Collector navigation menu(i.e., For user type - Collector).

## Front-end files created by me
Below is the list of all the front-end files created by me for the feature Social Clean Reporter Management - EnviClean Patron:
* Folder - [/src/apis/](https://github.com/DhrumilShah98/Group6_S21_EnviClean/tree/patron/src/apis)
    * [patronPostAPIs.js](https://github.com/DhrumilShah98/Group6_S21_EnviClean/blob/patron/src/apis/patronPostAPIs.js) - This file contains the list of all the Patron APIs required to connect with the back-end EnviClean Patron feature.
* Folder - [/src/component/Patron/](https://github.com/DhrumilShah98/Group6_S21_EnviClean/tree/patron/src/component/Patron)
    * Folder - [PatronForm/](https://github.com/DhrumilShah98/Group6_S21_EnviClean/tree/patron/src/component/Patron/PatronForm)
        * [PatronForm.js](https://github.com/DhrumilShah98/Group6_S21_EnviClean/blob/patron/src/component/Patron/PatronForm/PatronForm.js) - This file contains code to populate the "Post Garbage" form for creating posts.
        * [styles.js](https://github.com/DhrumilShah98/Group6_S21_EnviClean/blob/patron/src/component/Patron/PatronForm/styles.js) - This file contains CSS styles for the file _PatronForm.js_.
    * Folder - [PatronHome/](https://github.com/DhrumilShah98/Group6_S21_EnviClean/tree/patron/src/component/Patron/PatronHome)
        * [PatronHome.js](https://github.com/DhrumilShah98/Group6_S21_EnviClean/blob/patron/src/component/Patron/PatronHome/PatronHome.js) - This file contains code and logic that decides what to show based on the preference selected (All posts, My posts, Searched Posts).
        * [styles.js](https://github.com/DhrumilShah98/Group6_S21_EnviClean/blob/patron/src/component/Patron/PatronHome/styles.js) - This file contains CSS styles for the file _PatronHome.js_.
    * Folder - [PatronMember/](https://github.com/DhrumilShah98/Group6_S21_EnviClean/tree/patron/src/component/Patron/PatronMember)
        * [PatronMember.js](https://github.com/DhrumilShah98/Group6_S21_EnviClean/blob/patron/src/component/Patron/PatronMember/PatronMember.js) - This file contains code to enrol the user (User type - Depositor) as an EnviClean Patron member.
        * [PatronTermsAndConditions.js](https://github.com/DhrumilShah98/Group6_S21_EnviClean/blob/patron/src/component/Patron/PatronMember/PatronTermsAndConditions.js) - This file contains code to display the terms and conditions dialogue.
        * [styles.js](https://github.com/DhrumilShah98/Group6_S21_EnviClean/blob/patron/src/component/Patron/PatronMember/styles.js)- This file contains CSS styles for the file _PatronMember.js_ and _PatronTermsAndConditions.js_.
    * Folder - [PatronPosts/](https://github.com/DhrumilShah98/Group6_S21_EnviClean/tree/patron/src/component/Patron/PatronPosts)
        * [PatronPosts.js](https://github.com/DhrumilShah98/Group6_S21_EnviClean/blob/patron/src/component/Patron/PatronPosts/PatronPosts.js) - This file contains code to populate all the posts.
        * [styles.js](https://github.com/DhrumilShah98/Group6_S21_EnviClean/blob/patron/src/component/Patron/PatronPosts/styles.js) - This file contains CSS styles for the file _PatronPosts.js_.
        * Folder - [PatronPost/](https://github.com/DhrumilShah98/Group6_S21_EnviClean/tree/patron/src/component/Patron/PatronPosts/PatronPost)
            * [PatronPost.js](https://github.com/DhrumilShah98/Group6_S21_EnviClean/blob/patron/src/component/Patron/PatronPosts/PatronPost/PatronPost.js) - This file contains code to populate a single post.
            * [styles.js](https://github.com/DhrumilShah98/Group6_S21_EnviClean/blob/patron/src/component/Patron/PatronPosts/PatronPost/styles.js)- This file contains CSS styles for the file _PatronPost.js_.
* Folder - [/src/utils/](https://github.com/DhrumilShah98/Group6_S21_EnviClean/tree/patron/src/utils)
    * [NavbarPatronUtils.js](https://github.com/DhrumilShah98/Group6_S21_EnviClean/blob/patron/src/utils/NavbarPatronUtils.js) - This file contains logic that decides when to display the Patron tab on the Navigation menu.

For the front-end implementation, I followed Material-UI guidelines, principles and structure.

## Back-end files created by me
* Folder - [/src/config/](https://github.com/vishaldipakparmar/Group6_S21_EnviCleanAPI/tree/patron/src/config)
    * [cloudinary.config.js](https://github.com/vishaldipakparmar/Group6_S21_EnviCleanAPI/blob/patron/src/config/cloudinary.config.js) - This file contains [Cloudinary](https://cloudinary.com/) connection and  configuration details. 
* Folder - [/src/models/](https://github.com/vishaldipakparmar/Group6_S21_EnviCleanAPI/tree/patron/src/models)
    * [patronPost.js](https://github.com/vishaldipakparmar/Group6_S21_EnviCleanAPI/blob/patron/src/models/patronPost.js) - This is a model file that maps the patron post parameters with the patron_post table.
* Folder - [/src/routes/](https://github.com/vishaldipakparmar/Group6_S21_EnviCleanAPI/tree/patron/src/routes)
    * [patronPostRoute.js](https://github.com/vishaldipakparmar/Group6_S21_EnviCleanAPI/blob/patron/src/routes/patronPostRoute.js) - This file contains the routes to EnviClean patron features that require authentication.
* Folder - [/src/controller/](https://github.com/vishaldipakparmar/Group6_S21_EnviCleanAPI/tree/patron/src/controller)
    * [patronPostController.js](https://github.com/vishaldipakparmar/Group6_S21_EnviCleanAPI/blob/patron/src/controller/patronPostController.js) - The _patronPostRoute.js_ route file calls the appropriate controller method in the _patronPostController.js_ file to serve user requests.
* Folder - [/src/services/](https://github.com/vishaldipakparmar/Group6_S21_EnviCleanAPI/tree/patron/src/services)
    * [patronPostService.js](https://github.com/vishaldipakparmar/Group6_S21_EnviCleanAPI/blob/patron/src/services/patronPostService.js) - The _patronPostController.js_ controller file calls the appropriate service method in the _patronPostService.js_ file to perform the business logic.
* Folder - [/src/database/](https://github.com/vishaldipakparmar/Group6_S21_EnviCleanAPI/tree/patron/src/database)
    * [patronPostDB.js](https://github.com/vishaldipakparmar/Group6_S21_EnviCleanAPI/blob/patron/src/database/patronPostDB.js) - The _patronPostService.js_ service file calls the appropriate method in the _patronPostDB.js_ file to perform CRUD operations on patron_post table.
* Folder - [/src/utils/](https://github.com/vishaldipakparmar/Group6_S21_EnviCleanAPI/tree/patron/src/utils)
    * [imageUploadUtil.js](https://github.com/vishaldipakparmar/Group6_S21_EnviCleanAPI/blob/patron/src/utils/imageUploadUtil.js) - This file contains logic to allow jpg, jpeg and png image files.

### Prerequisites
To have a local copy of this project up and running on your local machine, you will first need to install the following software/libraries/plug-ins:

* [Node](https://nodejs.org/en/) - Download and install Node, which also includes [NPM](https://www.npmjs.com/) (Node Package Manager).
* [Visual Studio Code](https://code.visualstudio.com/) - Download and install VS Code or any Editor/IDE(Integrated Development Environment) of your choice.

### Image References
* [Webpage Background Image](https://github.com/DhrumilShah98/Group6_S21_EnviClean/blob/patron/src/assets/dustbin_background.jpg)
    * Original source - [Misty Suburban Neighborhood](https://unsplash.com/photos/MwKhY91v2Dc)
    * Author - [Shane Rounce](https://unsplash.com/@shanerounce)
* [Patron Member Image](https://github.com/DhrumilShah98/Group6_S21_EnviClean/blob/patron/src/assets/patron_member.png)
    * Original source - [Bhavyata Foundation](http://new.bhavyata.com/wp-content/uploads/2021/04/icon-2@4x-e1618571684684-180x180.png)
    * Author - [Bhavyata Foundation](http://new.bhavyata.com/)
* [Green Lime Persian Image](https://in.pinterest.com/pin/828803137652290892/?d=t&mt=login) - Green color palette


### Built With
* [React](https://reactjs.org/) - Front-end framework
* [Node](https://nodejs.org/) - Backend JavaScript runtime built on [Chrome's V8 JavaScript engine](https://v8.dev/)
* [Express](https://expressjs.com/) - Web framework for [Node](https://nodejs.org/)
* [MySQL](https://www.mysql.com/) - Relational database used for data persistence
* [NPM](https://www.npmjs.com/) - The package manager for  [Node](https://nodejs.org/)
* [Cloudinary](https://cloudinary.com/) - Cloud-based image and video management service
* [Heroku](https://dashboard.heroku.com/) - The cloud platform used for application deployment
* [GitHub](https://github.com/) - The version control tool
* [Visual Studio Code](https://code.visualstudio.com/download) - The source code editor used
* [Google Chrome](https://www.google.com/intl/en_in/chrome/) - Browser used to visualize the changes
* [Postman](https://www.postman.com/) - The Platform for API development and testing
* [Google Cloud Platform](https://console.cloud.google.com/) - MySQL database is hosted on GCP.
* [MySQL Workbench](https://www.mysql.com/products/workbench/) - Desktop client used to connect to the MySQL database hosted on GCP.

## Instructor
* [@gmosqueraj](https://github.com/gmosqueraj)

## Teaching Assistants
* [@pishdude](https://github.com/pishdude)
* [@GoenkaNikunj97](https://github.com/GoenkaNikunj97)
* [@shehzeenhooda](https://github.com/shehzeenhooda)
* [@theyashjaiswal](https://github.com/theyashjaiswal)
* [@bala-sundeep-d](https://github.com/bala-sundeep-d)
* [@kshitijp12345](https://github.com/kshitijp12345)
* [@NeharikaSehgal](https://github.com/NeharikaSehgal)
* [@shahaadesh5](https://github.com/shahaadesh5)
* [@smnsingh444](https://github.com/smnsingh444)