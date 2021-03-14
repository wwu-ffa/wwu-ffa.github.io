# Food For All

*   Kieran Devany - devanyk2@wwu.edu
*   Marri - jamal@marri.dev
*   de Vera - deveraj@wwu.edu
*   Ayisha Olanrewaju - olanrea@wwu.edu

## CS 412, Winter 2021, Dr. Shameem Ahmed

## Purpose

The purpose of this app is to reduce food waste by connecting those with excess food to those in need.

## Features

Our app uses the following features to provide an excellent experience to our nonexistent customers. We use multiple screens, a menu, a firebase firestore, camera, GPS, google maps, and fragments.

## Market Analysis

*   [YourLocal](https://yourlocal.org/) 
*   [FoodRescue](https://foodrescue.us/)
*   [Food Banks USA](https://play.google.com/store/apps/details?id=com.free.food)
*   [Food Finder](https://play.google.com/store/apps/details?id=org.foodfinderga.foodfinder)
*   [ShareTheMeal](https://sharethemeal.org/en)
*   [FoodConnect](https://www.foodconnectgroup.com/)
*   [Got Food](https://play.google.com/store/apps/details?id=com.us.gotfood&hl=en_US&gl=US)
*   [Waste No Food](https://play.google.com/store/apps/details?id=org.wastenofood.app&hl=en_US&gl=US)

Through our research of these apps we discovered that there is not only a market for reducing waste but also for charities and other organizations to coordinate food rescues.

## App Evolution

*   Checkpoint 1

    Our primary focus for checkpoint 1 was to set up our development environment, mainly our database solution, and to develop our method of contribution. The end result is a basic login and registration activity that connects to firebase for authentication.
    ![*Checkpoint 1*](images/image1.png=30%)

*   Checkpoint 2

    The next stage was to add functionality to the application in the form of a listing creation page and an organization registration page. This stage also dealt with asking for camera permissions and taking photos.
    ![*Checkpoint 2*](images/image2.png=30%)
*   Checkpoint 3

    In checkpoint 3 we integrated location services as well as google maps using fragments, now we have our main activity. The only thing missing is our database connection.
    ![*Checkpoint 3*](images/image3.png =30%)

*   Checkpoint 4

    Success! We now have a map that displays the location of items in relation to the user. Our page also allows a user to filter and examine listings. Organizations can now edit and modify listings that they created.
    ![*Checkpoint 4*](images/image4.png=30%)

*   Checkpoint 5

    Checkpoint 5 is all about polishing existing features, this involved a custom icon and theme aswell as giving organizations more control over their content.
    ![*Checkpoint 5*](images/image5.png=30%)

## Final Project

*   Model

    Our model consists of multiple Firebase services including: Firestore, Storage, and Authentication. Our model also includes the Java classes which manage Firestore and Storage access, as well as a Listing class to serve as a representation of a single Listing.

*   Controller

    Our controller consists of our activity Java classes which control each activity’s view, as well as a class managing Toasts and an interface for callback methods.

*   View

    Our view consists of our activity XML files, as well as the Java classes which we extend for most of our activities, each representing a common feature among them.

*   Final Version

    Our app allows for email/password registration/login. Upon logging into the app, the user is presented with a feed of listings posted by organizations that have registered to become food donators. Users may sort the feed by date posted or by distance to them. They may also filter by distance to narrow down their results. Users may click on a listing to see more details about it. When looking at a particular listing, users can see the details of the organization that posted it by clicking on their name. In the profile page, a user may log out of the app or register as an organization themselves. Upon registering as an organization, the user’s profile page will change to include options where they can modify their organization’s details and manage their existing listings. Additionally, the create button will be accessible from the feed page, which users can use to create new listings.

*   check us out [here](https://github.com/wwu-ffa/food-for-all)