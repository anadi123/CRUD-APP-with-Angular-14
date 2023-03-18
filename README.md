# MyCrudApp

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 15.0.0.
In this example we will create a post crud module with a list, view, insert, update and delete the post. we will use the web service API of jsonplaceholder. so we can easily use their created API. jsonplaceholder provides all APIs that we require like list, view, create, delete and update.



## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Steps

1.Step 1: Create New App

2.Step 2: Install Bootstrap

3.Step 3: Create Post Module--After creating successfully app, we need to create post module using angular cli command. angular provide command to create module with routing in angular application.

4.Step 4: Create Component For Module--add new component to our post module using bellow command, so let's create index, view, create and edit component for admin module.

5.Step 5: Create Route--In this step, we will simply create route for index, create, edit and view using generated new component. so we have to update our post-routing module file.

6.Step 6: Create Interface--in this step, we will create interface using angular command for post module. we will use post interface with Observable.

7.Step 7: Create Services--Here, we will create post service file and we will write and call all web services. we will create getAll(), create(), find(), update() and delete().We are using https://jsonplaceholder.typicode.com web site api for now. they provide to easily use.

8.Step 8: Update Component Logic and Template--Now in this step, we will work on our created component for crud application. we create four component for our crud application. now we will go one by one for creating list page, create page, edit page and view page.

1) List Page Template and Component

now, here we will work on post index component. we will call post service and display it with create, edit, delete and view button. so let's update it.

2) Create Page Template and Component

now here, we will use reactive form store data into server using web services. so let's update it.

3) Edit Page Template and Component

now here, we will use reactive form store data into server using web services for update post information. so let's update it.

4) Detail Page Template and Component

now here, we will display data into server using web services for update post information. so let's update it.

9.Step 9: Import to Module File--Now in last step, we will import our post module and HttpClientModule to main file and also other to post module.

Run Angular App:

All the required steps have been done, now you have to type the given below command and hit enter to run the Angular app:

ng serve

Now, Go to your web browser, type the given URL and view the app output:

http://localhost:4200/post

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.
