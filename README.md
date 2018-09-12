# Web Developer assessment - create a small app that pulls and displays data from a RESTful API.

GitHub pages - https://jamiekt1983.github.io/CityRESTAPI/ (with pagination: https://jamiekt1983.github.io/demo/index.html)

-Create GitHub repository and clone to desktop - jamiekt1983/CityRESTAPI

-Create index page and css file to style later.

-Make first commit to ensure connection is working

-Fetch data from RESTful API - http://jsonplaceholder.typicode.com/photos

-Check for any errors in browser console

-Display a list of photos data. Improve loading time by applying the _limit parameter to only display 10 results.

-Display photo thumbnail and link to url

-Add flexbox styling to the lisitngs

-Add media query for mobile responsive design

-Sort results by id and in ascending order

-Apply some error trapping

-Add svg image on hover to indicate photo can be enlarged

-created paginationtest to test out angular pagination, using bootstrap (https://jamiekt1983.github.io/demo/index.html)


# Future changes:

-implement scss variables

-lazy loading to speed up loading times - load only when user selects next page

-develop app with JSON Server (eg:http://www.betterpixels.co.uk/projects/2015/05/09/mock-up-your-rest-api-with-json-server/)

-create dropdown to select album

-improve pagination - Github uses the Link response header

-use albumId to get album title from albums resource (first fetch the albums and then while rendering the photo list, pick the album information)
