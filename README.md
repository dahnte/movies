# Movie Matcher:

*WARNING* - Extract files before you run, otherwise application will not run properly!

An application that is meant to show which movies two people have agreed to watch, using two .txt files ("x_master" & "x_rating", x being the first letter of the movie cateogry).
Very simple automated way of giving an answer (yes, maybe, or no; answers will be based on "x_movielist"), which then produces a results file showing which movies were both agreed on, both given different answers on, and both said maybe on.

Latest version includes:
  - Overall stability
  + Added a results file that shows movies agreed on, indifferent about, and maybe's in neat .txt file (should appear in same file where .exe was ran)
  
  Now specifics:
  
    For comedy section
      - Comedy movie list (compiled from https://www.imdb.com/list/ls058726648/)
      + added "c_master" to compare results to
          - can modify "c_master" to your liking, so results are more personal 
          
    For drama section:
      - Drama movie list (compiled from https://www.imdb.com/list/ls009668711/)
      + added "d_master" to compare results to
          - can modify "d_master" to your own liking, so results are more personal
          
    For horror, romance, & action section:
      - Currently no movie list, or "x_master" - HOWEVER, you you're able to create your own movie list and master by simply creating a .txt file following the drama and comedy         section format
      - Program is now robust enough to include these sections when ran.
          - it will still say (Incomplete) in the movie category selection phase, but pay no mind as it will work... if done properly!
