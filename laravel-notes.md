   DB connections and CRUD operations steps

   1. Setup database: create DB in phpmyadmin then add configurations in .env folder
   2. Create migrations: Define or create the table columns
   3. Create Model: this talks to the DB
   4. Create Controller: this will handle all the logics
   5. Define Routes: web.php, URL to controller mapping
   6. Create views: index, edit, create balde files 
   7. Write CRUD logics: index, create, store, edit, update, destroy
   8. Test and PUSH to GITHUB: run app, vrify and then gitpush




      Controller: its the brain of the app, if someone visits a URL like students, laravel sends that request to controller, its fetches the data,processes it and send sit to view in order to display.
      fillable: security protection, tells laravel whihc columns should be filled from a form.
      
