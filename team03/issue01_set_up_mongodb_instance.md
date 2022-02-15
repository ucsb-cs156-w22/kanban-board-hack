Set up MongoDB database

* Note that the person working on Heroku QA/Prod and localhost `.env` values will need to
  coordinate with you to obtain the value of `MONGODB_URI`.
* We suggest coordinating with the team member doing the Heroku QA/Prod and localhost setup.

# Acceptance Criteria:

- [ ] You have set up an account for yourself at <https://cloud.mongodb.com>; 

      (We suggest that you
      and all team members standardizing on using your `@ucsb.edu` email for this purpose just to avoid confusion, and that you sign in to  <https://cloud.mongodb.com> using Google OAuth; but that's entirely a personal/team decision.)

- [ ] All members of the team are added to the Heroku `prod` deployment.
- [ ] The course instructor (`phtcon@ucsb.edu`) and the mentor listed
      at <https://ucsb-cs156.github.io/w22/info/teams/> is added to
      the heroku `prod` deployment. (Ask for the email they use with
      Heroku via slack.)
- [ ] You have obtained values for `GOOGLE_CLIENT_ID` and `GOOGLE_CLIENT_SECRET` from the <https://console.developers.google.com/> following the instructions in the repo's `README.md` and the `/docs` directory for OAuth configuration and put these in the `.env` file. 
- [ ] You have gathered the UCSB email addresses of all team members and put them into the
      list of `ADMIN_EMAILS` in the `.env` file.      
- [ ] You have obtained the value of the `MONGODB_URI` from the team member responsible for the MongoDB setup.
- [ ] You have configured the values in your local `.env` file so that the application can run on `localhost`.
- [ ] You have 
      shared those values with other team members, and checked in to make sure they can run the app successfully on localhost also.
- [ ] You have configured the `.env` values as Config Variables on Heroku for both the prod and qa instances of the app,
      and have verified that the `main` branch of the starter code is up and running on both prod and qa.
