# Laravel progress
 Here is my home page
![image](https://github.com/user-attachments/assets/9880c338-f33d-464d-bb51-85c2be238e3b)

Blog page
![image](https://github.com/user-attachments/assets/473b79ed-b7a6-4519-8d8b-52468360e776)

Contact page

![image](https://github.com/user-attachments/assets/ee755173-c9f5-4514-9a1c-0fd1e597ef82)

lastly this is the about page
![image](https://github.com/user-attachments/assets/aea4c6d5-e376-4b1e-8894-09a7395474b3)

New update on 12/9/2024

Blog Page 

![image](https://github.com/user-attachments/assets/9b10a27f-358b-401c-9371-941b17f1eb37)


Model Factories

Create random fake data in database just by command

for users
![image](https://github.com/user-attachments/assets/c54bc558-13cb-45e7-99ab-07b18e9b1105)

to change the language setting or to set name according to desire country for the fake data ^^

![image](https://github.com/user-attachments/assets/17db301e-8a14-4410-866c-b6ae6b733ba1)

: choose any language in this website at the 'LOCALES' section ^^

![image](https://github.com/user-attachments/assets/506ae2a3-e133-4491-87f6-74cb6a18ef1d)

: change in the .env folder at the 'APP_FAKER_LOCALE' ^^

#use( php artisan migrate:fresh ) to delete all the data that have been insert in the database

ELOQUENT RELATIONSHIP

 Making the user as foriegn key for the post

![image](https://github.com/user-attachments/assets/2745e3b9-9f63-4d9b-a957-2d50d77b3c25)

The documentation for the foreign key 

![image](https://github.com/user-attachments/assets/5f862ef5-670f-4448-9e4b-3dff8358f2a9)
![image](https://github.com/user-attachments/assets/726bff61-db3c-4870-a890-9bc9778864c0)


:set the author as foriegn key in the post table as constrained ^^

![image](https://github.com/user-attachments/assets/b45df178-7d42-4adb-9ed1-3635c4ac2a0e)

Documentation to use existing models data for relationship/ to use existing factories^^
for 1 id to many 

![image](https://github.com/user-attachments/assets/5a124c17-eba8-434e-8b0c-6caa0282c658)


to create 100 data of the post ^^

![image](https://github.com/user-attachments/assets/b5507786-156b-476f-b3eb-5c4a77ca83cb)


to recycle the user data for repeating in the post data for the (author) ^^

![image](https://github.com/user-attachments/assets/9b4aa063-d10d-4701-a25f-1790e5a192d1)


the first 'create' is for the recycle user data and the last 'create' function is for the post data ^^

![image](https://github.com/user-attachments/assets/8318f776-fc0f-4798-9dd4-6b9a1390b905)

command to check the details of the specific post ^^

![image](https://github.com/user-attachments/assets/cd351d8d-7763-462d-b859-941783443797)

to declare the author data connected to the post ^^

![image](https://github.com/user-attachments/assets/364acbfb-109f-4ffb-af12-f5bd7c28b8fe)

this for user to post as one to many, also set the foriegn key  ^^

![image](https://github.com/user-attachments/assets/63a5f1fb-ba44-4f06-a285-85b02cb84824)

change the path to get the name at the post (view) folder ^^

Step to click the author name and show all the post that have been write by the same author 

![image](https://github.com/user-attachments/assets/f9863aab-be5d-4c02-a5e1-471bdb86a744)

change the href to get the path ^^

![image](https://github.com/user-attachments/assets/fd8cf2b8-0a6a-46c8-b7d1-159c77533492)

Update POST CATEGORY ^^^

DATABASE SEEDER
(plant the database )

![image](https://github.com/user-attachments/assets/9b4aa063-d10d-4701-a25f-1790e5a192d1)

instead of doing this ^^^

![image](https://github.com/user-attachments/assets/63282620-c1a5-46b3-a9d4-c688e0e67d6c)

just do this ^^^

![image](https://github.com/user-attachments/assets/0c9936e7-0e4f-4a30-a03c-96006858871c)
set the command in the database seeder.php at the seeder folder^^

![image](https://github.com/user-attachments/assets/065eb633-6741-4e80-8166-716f3730a29c)

command to migrate fresh and seed the database at the same time^^

![image](https://github.com/user-attachments/assets/ea323153-9a70-4031-9d55-026795d7e7b4)

manually insert the data that we wanted^^

![image](https://github.com/user-attachments/assets/c3d9eca8-2394-4d93-ba7a-63b593f8c515)

fucntion to call the data from other seeders^^

N+1 PROBLEM

N = total data that we have 
1 = table post

![image](https://github.com/user-attachments/assets/f8badc58-df23-4d37-861e-a075c7da8b5e)

![image](https://github.com/user-attachments/assets/bfe1b03c-58e1-4c11-afb8-ade0c5636743)
 to sort the post from the latest data

![image](https://github.com/user-attachments/assets/2a51d95b-c35a-46f0-9db0-6de43bcf9557)

set the part that need to lazy eager loading

REDESIGN THE UI

install flowbite
![image](https://github.com/user-attachments/assets/0f5834e9-62d5-4ac6-933d-3018f5832056)

![image](https://github.com/user-attachments/assets/07e82c1f-1793-422b-bb36-72eaa2e82fb0)

![image](https://github.com/user-attachments/assets/f4baf1ab-811c-46f2-9889-ba085af6e033)
![image](https://github.com/user-attachments/assets/f7705e90-d10f-4f1c-a176-8056b92a7ea7)

add the highlight part in the tailwind file.^^

![image](https://github.com/user-attachments/assets/c4542cc7-5142-4add-9e08-98a236723b84)

only take what is different.

![image](https://github.com/user-attachments/assets/a2d3fd05-b133-45ba-be3f-9545b34b681d)
to add the colum^^

PAGINATION

![image](https://github.com/user-attachments/assets/1bbbd566-9df9-4c3a-ba5c-dd0d21bfbe32)
Add in the web.php

![image](https://github.com/user-attachments/assets/c3121803-c34e-4667-8b25-e0801d5a9510)

insert in the page
