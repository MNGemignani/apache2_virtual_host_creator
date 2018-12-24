# Apache2 virtual host creator for Ubuntu

## Installation

    pip install apache2-vh

## Usage

You can see all the commands and basic usage typing:

    vh --help
    
    usage: vh server_name folder_name [-h] [-m2] [-a SERVER_ALIAS] [-d DIRECTORY_ROOT] [-p PORT] [-c CONF_NAME]
                                                      
The minimal usage is with 2 arguments:
                                                                                                                                                      
                                                       
    server_name           Your server name (ex.: blabla.com)                                    
   
    folder_name           The folder name where your project is in the document root (default is /var/www/html if you have in a different place set it with -dr)
                                                                             
But you have a few more optional arguments: 
                                                         
    -m2, --magento2       Virtual Host para magento 2 (if you are creating  virtual host for magento2)  
   
    -a SERVER_ALIAS, --server_alias SERVER_ALIAS Add a server alias (ex.: www.blabla.com)                                 
   
    -d DIRECTORY_ROOT, --directory_root DIRECTORY_ROOT  Full path of your apache document root that will be set in the virtual host (default is /var/www/html)
   
    -p PORT, --port PORT  Change the listening port (default is 80)             
   
    -c CONF_NAME, --conf_name CONF_NAME Add a diferent name to your conf file (without the .conf extension) default is the name of your folder_name (ex.: blabla -> file created blabla.conf)

## Notes

 Feel free to use, copy, extend or contribute to this project, if you want to reuse a mention to this project is appreciated, but I don't really care if you don't do it.
 This is a open source project without any warranty or something like that. 
