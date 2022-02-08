## About Project

 - [Create a Social Login system with Google.]
 - [Create CRUD Operation for User Management using the following condition.]
    i. Fields
        Name - Text
        Email - Text
        Address - Textarea
        DOB - Date
        Status - Radio
        Education - Dropdown
        Pin Code - Text
        Profile Pic - Image / File Upload
        Country - Dropdown
        City - Dropdown (Based on Country Fields)

    ii. List Page with following fields
        Profile Pic (Thumnail)
        Name
        Email
        Age (Based on DOB)
        Status
        Action (Edit, View, Delete)

    iii. Need Filter option for following fields in List Table
        Name
        Email
        Age
    Status

## Installation & Setup

 - 


### Steps Followed
 - composer create-project --prefer-dist laravel/laravel DCKap
 - Create & configure database in env
 - Create migration
 - php artisan migrate
 - php artisan serve
 - composer require laravel/ui
 - php artisan ui bootstrap --auth
 - npm install
 - npm run dev
 - Create and get Google app creadentials
 - composer require laravel/socialite
 - php artisan make:migration add_google_id_column
 - php artisan make:controller GoogleController
 - 


