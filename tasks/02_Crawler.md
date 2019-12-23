# Crawler

#### Create a simple crawler application with symfony and spatie's crawler package.
___

  Requirements / Objectives:
  
  - Build a console application with the Symfony framework.
  - Instead of the Symfony DOM, the spatie crawler must be used [spatie/crawler](https://github.com/spatie/crawler).
  - A domain should be specified as a parameter (e.g. in-die-tuerkei.de)
  - The application should find all internal URL's (`a` tag of HTML) of the specified domain recursively and output the following values as an array:
    * URL-Id
    * URL path
    * URL Length
  - A web interface is not necessary.
  - External URL's should be ignored.
