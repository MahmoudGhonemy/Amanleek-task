# Amanleek-task
WordPress task

I downloded WordPress packaged by bitnami tool from this link : https://bitnami.com/redirect/to/2233477/bitnami-wordpress-6.1.1-0-windows-x64-installer.exe

After install and setup I started adding some dummy posts to the blog (so I can retrieve  data about them with the postman) from the leftside bar
posts - add new

After adding those posts , I opend the postman and (ctrl+n) I opend new HTTP request
I used the method GET
with Host : localhost
and the path : /wordpress/index.php/wp-json/wp/v2/posts HTTP/1.1

The respons was in JSON with all the data about the posts (Id , date , title , content ... ect)
