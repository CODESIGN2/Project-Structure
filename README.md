Project-Structure
==================

2014/2015 Project structure base for all in-house projects (excluding those using legacy or past systems)

vhost project folder structure 
=============================== 

 * vhosts (usually /usr/share/nginx/vhosts or /var/www/vhosts)
  * {projectname}
    * **public** 
    * **private** (***used to be CI for codeigniter***)
    * backup 
    * certs 
    * log 
    * tmp 

web-app folder structure  
=========================
N.b.: within vhost project folder structure

 * **public** 
  * {routerfile}.php 
  * font 
  * css 
  * img 
  * js 
  * themes 
     * {theme[x]} 
         * font 
         * css 
         * img 
         * js
         * licenses
  * media (symbolic links to uploads) 
  * licenses 
 * **private** 
  * uploads 
  * src (composer.json lives in here)
     * vendor 
         * autoload.php (composer autoloader)
         * cd2
             * base 
                 * **data** 
                 * models
                 * libaries
                 * helpers
                 * **assets** 
         * {vendor[x]} 
             * **data** 
             * models
             * libaries
             * helpers
             * **assets** 

Assets folder structure
========================
 * **assets** 
  * views 
  * scss 
  * less  
  * font  
  * css  
  * img  
  * js  
  * cs 

Data folder structure
======================
 * **data** 
	 * validations
	 * schemas 
	 * regex 

 
