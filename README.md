# shtml
tryout for apache shtml

# apache config
LoadModule include_module libexec/mod_include.so

In directory:
Options Includes Indexes FollowSymLinks

In IfModule mime_module:

AddType text/html .shtml

AddOutputFilter INCLUDES .shtml
