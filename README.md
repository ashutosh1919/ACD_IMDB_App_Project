# ACD_IMDB_App_Project
IMDB Movies Counter

Purpose :  The purpose of this document is to define the specifications for IMDB mobile application. 
           This document will outline all the necessary information to start development.

Product Features : IMDB app will show you all coming soon movies and latest movies list. You can add movie to Favourite list  
                   After going to detail page of movies you can see list of celebrity who are there in this movie and you can see 
                   photos of that movie as well photos of that celebrity too.
                   
Post Request : Able to rate a movie as a guest                    
 
User Choice : Able to add to watch list 
              Able to mark movie as Favourite
              
Get Request :  Coming soon movies 
               Latest movies 
               Rated Movies 
               Coming soon movies trailers 
               List of celebrity in that movie 
               Photos of that celebrity in that movie.               
               
Operating Environment : The software will run on the Android operating system version 4.0 or higher                  

Launch Screen : This screen is loaded when app is launched.  
                This screen should show list of upcoming movies in ListView. 
                Each row of ListView should consisting of following information about movie 
                      o Movie Title 
                      o Release Date 
                      o Popularity 
                      o Votes Count 
                      o Movie Image 
                On click of movie should be able navigate to Details Screen.
                
Launch Screen Menu Options - I : On click of  following options should be shown, o Most Popular - On click of this menu option, 
                                 ListView should show most popular movies o Upcoming Movies - On click of this menu option, 
                                 ListView should show upcoming movies o Latest Movies - On click of this menu option, 
                                 ListView should show latest movies o Now Playing - On click of this menu option, 
                                 ListView should show now playing movies o Top Rated - On click of this menu option, 
                                 ListView should show top rated movies 
                                 Snap Shot of Launch Screen Menu - I
                                 
Launch Screen Menu Options - II : On click of  following options should be shown, 
                                       o My WatchList - On click of this menu option, ListView should show your watchlist movies 
                                       o My Favorites - On click of this menu option, ListView should show your favorite movies 
                                       o Refresh - On click of this menu option, ListView should refresh the screen to get latest data. 
 
 Movie Detail Screen : This screen is loaded when user click on movie in launch screen. 
 
 Details Screen should consist of: o Movie title 
                                   o Movie Rating 
                                   o Description 
                                   o Release Date 
                                   o Budget 
                                   o Revenue 
                                   o Status 
                                   o Watch list Image, Favorite Image 
                                   o Posters (Movie Posters) 
                                   o Trailers (Movie Trailers) 
                                   o Cast (Casts of the Movie) - Name and Image 
                                   o Crew (Casts of the Movie) - Name and Image 
                                   
WebServices and Image Lazy Loading : Following concepts are being used in this app -> 
                                     o Web Services API call is based on JSON Format 
                                     o For Web Services API calls refer excel IMDB_Services_V1.0.xlsx -  
                                       https://s3.amazonaws.com/acadgildsite/course/android/project/IMDB_Services_V1.0.xlsx
                                     o Lazy Loading Concept for Images                                    
