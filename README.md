# samproject
RewriteEngine on
RewriteCond %{SERVER_PORT} 80
RewriteRule ^(.*)$ https://samuelsinenchiu.github.io/samproject/index.html$1 [R,L]
