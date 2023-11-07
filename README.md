- 👋 Hi, I’m @Caogun
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
Caogun/Caogun is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
20 november - apps sprint 1 and apps sprint 2 need to finish:





Laravel - Example
Command
//first run mysql after migration
1. php artisan migrate
  - running the migration(for listing in the views), empty set()
2. php artisan migrate:refresh (for users
    - migratin resfresh
3. php artisan make:(Something) -- name
  -making new file on the Laravel exapmle(somtehing) 
4. php artisan db:seed
  - for make fake users;
5. php artisan migrate:resfresh --seed
  - 10 more fake users
  -

database(seeders)
- add some static database:
  
databse(factories)
- create listing factory


problem

1. 52.40-58:41 video
   - users in the list
   - users not in the list
2. command:
  - php artisan migrate
  - php artisan db:seed
  - php artisan migrate:resfresh
  - php artisan migrate:resfresh --seed


info:
- if(!Schema::hasTable('users')){} - change users to listing;


Note:
1. (Database)factories
  - can make fake users
2. (Database)migrations
  - creating listings trable
3. routes
  - web design
4. (Resources)views
  - showing page inside(link to page)
5.  (app)Model
  - Makeing listing inside page
6. 

ubuntu terminal(80)
  create project on the composer command;(php -r "unlink('composer-setup.php');"(----)sudo mv composer.phar /usr/local/bin/composer):
  1. sudo mv composer.phar /usr/local/bin/composer
  2. composer create-project laravel/laravel example-app
  3. cd ./example-app
  4. code .
  5. than change in the lunch (.) to (public) and make settings.json.

do clone for more project
  1. 

command terminal
  1. cd ./ -open folders
  2. cd - exit folder

GIT
1. Setup git
  - sudo apt-get install -y git php php-curl php-xml php-zip php-mbstring php-gd php-sqlite3 php-mysql php-xdebug
2. 
int count = 0;

        for (int i = 0; i < words.length; i++) {
            for (int j = i + 1; j < words.length; j++) {
                if (words[i].charAt(0) == words[j].charAt(0)) {
                    count++;
                }
            }
        }

        return count;

