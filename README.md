# Ruby on Rails Coding Challenge

- You will be designing a simplified version of an online marketplace for rental spaces.
- For the sake of simplicity, we will have only two types of users: Landlords and Renters.
- Landlord users will be able to upload their spaces for rent to the site.
- Renter users will be able to view the available spaces when they log in to the site.
- Renter will be able to search for spaces by location, date and category.
- Once the renter finds the right space for them (suitable based on location, date and price), they should be able
to request for a booking for that space.
- At that point, the landlord of the space will receive an email notification.
- The landlord can accept/decline the booking request.
- The renter will receive an email notification whenever their booking request is accepted/rejected.
- It's an open-ended design and coding problem where you have the flexibility to design the marketplace
system data models (attributes) and their relationships that make the most sense and are comprehensive.
- Please use Ruby version `2.6.5` or higher and Rails version `6.1` while developing the application.
- Feel free to use any open source gem that makes your life easier.
- Commit your code when you are done and send us the link to the github repo so that we can evaluate your code.

## Evaluation

Evaluation of your submission will be based on the following criteria:

- How well did you design the application data models, attributes, and associations?
- Did you document the method for setting up and running your application?
- Did you create a seed file to test the application locally?
- Did you you make atomic commits while developing the application?
- Did you write tests for your models and controllers?
- Did you consider performance bottlenecks while designing the system?
- Did you write code that is scalable and optimized for production users? 
- Did you consider what changes would need to be made for a true production-ready solution? You can include your thoughts in the README.

## Bonus Points:

The following points are nice-to-have but not necessary:

- Application UI looks nice!
- Use AWS S3 for uploading space images
- Use Sidekiq for sending emails to the users  
