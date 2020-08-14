

##### Rest API For Student CRUD

This Project is for Student CRUD using Rest API.


##### Project Working Procedure 

01. Create A New Project useing <b>composer create-project --prefer-dist laravel/laravel blog</b>

02. Create New Database and Add the database name into .env file (Database SQL file upload in the root directory)

03.  <b>php artisan migrate</b>  -> For initial migration

# To Create Model, Factory, Migration and Controller

04. <b>php artisan make:model Student -a</b>

    Model created successfully.
    Factory created successfully.
    Created Migration: 2020_08_14_130909_create_students_table
    Seeder created successfully.
    Controller created successfully.

05. <b> php artisan make:model Classes -a </b>

    Model created successfully.
    Factory created successfully.
    Created Migration: 2020_08_14_131304_create_classes_table
    Seeder created successfully.
    Controller created successfully.

06. Controller moven into Api folder and model moved info Model folder.

07. 




#####  Issues I Faced And Solution Is Given Below ----------------------------  ***********************************  -------------------------------------------------------------------------------------------------------------------

01. Class 'App\Http\Controllers\Admin\Controller' not found

<p>

If your controller is not within the same namespace as the base Controller (and it isn't), you need to add this to the top:

<code> use App\Http\Controllers\Controller; </code>

</p>

02. 


















