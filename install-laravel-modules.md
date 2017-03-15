# Install Laravel Modules

## 1. Install Laravel 
  #### Via Laravel Installer
   run
   
     `composer global require "laravel/installer"`
   
   then
   
     `laravel new blog`
            
  #### Via Composer Create-Project
  
      composer create-project --prefer-dist laravel/laravel blog
      
## 2. `cd blog`

   Enter into project folder
   
## 3. Install Laravel Modules
   #### Via Laravel Modules Installer
   
   run
   
     `composer global require "laravelmodules/installer"`
   
   then
   
     `laravelmodules new`
   #### Via Composer Create-Project
   
   run
   
     `composer create-project laravelmodules/core`
   
   then
   
     `module:core:install`

