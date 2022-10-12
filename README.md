#React Movie Search Application with "Add/Remove Favourite" section.
*****************************************************************************************
Visit URL: https://4o0slg-3000.preview.csb.app/
*****************************************************************************************

React Movie Application build using the bootstrap class to achieve the better UI experience for the user.
Also, the botstrap class and Icons has been added in the Search bar and favourite bar respectively.

*****************************************************************************************

App.js:-----
*********************************
useState, useEffect hooks are used to set the searchValue as per the user required. Inititally the page will not show any movie,
instead use the search bar for the functionality. Also the local storage has been created so the when the user comes again, he will
having the "Add to Favourites" movies that were added earlier.
************************************************************************************************************************************

This React movie app has been prepared by keeping the netflix UI in mind; movies appears to be reflected in the card view format.
*********************************
Different components such as AddFavoruite.js, MovieList.js, MovieListHeading etc. has been created so that data can be fetched and can be
received in the App.js keeping the files sepearted from one another.
*********************************
As per the user search, data has been fetched from the API and given the unique search value such that the local stoarge can be created
and when the user get visited again the same movies can be shown as that were added by the user into the favourite search bar.
*********************************

Also, when user reloads the page, favourite add movies will not be lost instead will be stored into the "localStorage" function, so when next time
visited the same data can be fetched again from the stored array.
****************
