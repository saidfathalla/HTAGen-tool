# HTAGen - an Htaccess Generator

A tool for htaccess files generation using a user-friendly graphical user interface.

## Background

Generally, Apache [Htaccess files](http://httpd.apache.org/docs/current/howto/htaccess.html) control a number of ways that a website can be accessed, blocked, and redirected. It does this using a series of one or more `rewrite` rules. These rewrites are made possible by Apache's `mod_rewrite` module.
`mod_rewrite` provides a way to modify incoming URL requests, dynamically, based on regular expression rules. This allows you to map arbitrary URLs onto your internal URL structure in a certain way you specify.

Apache [Htaccess files](http://httpd.apache.org/docs/current/howto/htaccess.html) contain one or more configuration directives, is placed in a particular directory, and the directives apply to that directory, and all subdirectories thereof.

Working with Htaccess files has both good and bad sides: on one hand, site owners can easily add new rewrites, configure headers, and more. On the other hand, one mistake can mean the whole site goes down.

## Aim

 HTAGen tool is developed, mainly, to help people who want to generate htaccess files to be used in [PURL services](https://en.wikipedia.org/wiki/Persistent_uniform_resource_locator), such as [PIDs for HMC](https://github.com/saidfathalla/PID-Service) and [w3id.org/](https://w3id.org/) which provides permanent URL re-direction service for Web applications.
Web applications that deal with Linked Data often need permanent URLs to such data to avoid potential service down. 
 
 
