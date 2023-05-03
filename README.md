# Project-3280 Personal-PC-selector
## start condition
1. In order to start this project, please start the mysql service before starting.
2. Use the composer install command to get the vendor folder.
3. Start database migration, when using migration, the three default users will automatically insert into the database.

## default user
|Name|Email|Permission|Password|
|--|--|--|--|
|Scott|1114897421@qq.com|Admin|12345678|
|Rohan|Rohan.kediyal@gmail.com|Admin|12345678|
|user|user@gmail.com|User|87654321|


## When start
1. When using it for the first time. You can log in with one of the three default users above, or use the Register button to register a new user.
2. When entering the page for building a new computer for the first time, the webpage will automatically send an API request to obtain hardware database information and save it to the database. Entering various hardware pages for the first time will take time to load. 

## Precautions
1. The administrator will display no data when entering the database before creating the computer for the first time, and the database can be loaded after the computer is built for the first time.
2. Ordinary users cannot normally register as administrators, but administrators can make ordinary users administrators by editing users.
3. If you want to use administrator privileges, please log in with the default inserted administrator account.
4. Pages that need to use API requests may encounter reading problems. This is because Amazon's free API can only send up to 100 requests per month. If you encounter this situation, please contact me to replace a new APIkey. There is my Discord server on the contact me page.

## MakeSure
# The following information is in. env file.

DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=Project3280
DB_USERNAME=root
DB_PASSWORD=
