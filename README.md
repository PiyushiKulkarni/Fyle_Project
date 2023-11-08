# Fyle Frontend Challenge
### Who is this for?
This challenge is meant for candidates who wish to intern at Fyle and work with our engineering team. The candidate should be able to commit to at least 6 months of dedicated time for internship.

### Why work at Fyle?
Fyle is a fast-growing Expense Management SaaS product. We are ~40 strong engineering team at the moment.

We are an extremely transparent organization. Check out our [careers page](https://careers.fylehq.com/) that will give you a glimpse of what it is like to work at Fyle. Also, check out our Glassdoor reviews [here](https://www.glassdoor.co.in/Reviews/Fyle-Reviews-E1723235.htm). You can read stories from our teammates here.

### Challenge outline
This challenge involves implementing application using github api.

The services that you need to use are already implemented - check out ApiService.

You can see details of this challenge here

Note - This challenge is in angular. We work on angular frameworks & after you join we expect the same from you. Hence it is required to complete this assignement in angular itself.

### What happens next?
You will hear back within 48 hours from us via email.

### Installation
1. Fork this repository to your github account.
2. Clone the forked repository and proceed with steps mentioned below.
### Install requirements
- Install angular cli [Ref](https://angular.io/cli)
* npm install in this repository
### Development server
Run ng serve for a dev server. Navigate to [http://localhost:4200/.](http://localhost:4200/.) The app will automatically reload if you change any of the source files.

### Further help
Visit the [Angular Documentation](https://angular.io/guide/styleguide) to learn more. Styling is to be strictly done with [Tailwind.](https://tailwindcss.com/docs/installation)

## How to use this app
Start by forking or downloading this repository. Once you have the project files on your local machine, you'll need to follow these steps to set up the development environment: 
### Step 1: Install Node Modules

To begin, make sure you have Angular and the required Node modules installed. Open your terminal and run the following commands:

npm install -g @angular/cli
npm install

### Step 2: Start the Development Server

Once you have the necessary packages and dependencies installed, you can start the development server to run your Angular application. Open your terminal and enter the following command:

Development server
Run ### ng serve -o for a dev server.

This command will launch the development server, and your web browser will open to http://localhost:4200/ automatically.

Now, you can access and interact with your Angular application. Follow the user interface to search for GitHub usernames, view user profiles, and explore repositories. Enjoy exploring and using your app!
### In the home page
- enter the github user name and click on view profile.
* the app will route to profile
### In the profile page
- pagination is added
* user can view repo list based on custom per page number.
### Unit Testing
    run  ng test
 - In api.service.spec.ts test is performed for api services
 * In github-profile.spec.ts UT is performed for github-profile component.
