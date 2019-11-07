# Crawler

#### Create a simple crawler application with symfony and spatie's crawler package.
___

  Requirements / Objectives:
  
  - The application must be built with Symfony Framework as a console application.
  - [spatie/crawler](https://github.com/spatie/crawler) must be used instead of Symfony's own dom crawler.
  - The application should visit all the URL's of given website recursively. For example:
    * If www.batunet.com is given as parameter, crawler should visit the homepage to find all the links starting with www.batunet.com (`a` tag of HTML). External links can be ignored.
    * After finding all URL's in the homepage, the application should start visiting other pages, one by one.
    * At the end, we should have every single page of batunet.com as URLs.
  
  - After crawling all the pages, application should print out an array of URL's that website has. (or write into a file in JSON format)
  - A web interface is not necessary.

___
www.batunet.com