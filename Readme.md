#Movies#

##ID attribute values##
```
*movies*- Applied to a DIV tag. The list of movies in this representation. This list may contain only one movie.
*actors*- Applied to a DIV tag. The list of actors in this representation. This list may contain only one actor.
```

##Class attribute values##
```
*all*- Applied to a UL tag. A list of representations. When this element is a descendant of DIV.id="movies" it may have one or more LI.class="movie" descendant elements. When this element is a descendant of DIV.id="actors" it may have one or more LI.class="actor" descendant elements. 
*movie*- Applied to a LI tag. This gives the outbound link to link a specific movie.
*actor*- Applied to a LI tag. This gives the outbound link to link a specific actor.
*movie-add*- Applied to a FORM tag. A non-idempotent link to create a new movie.
*movie-actors*- Applied to a LI tag. This gives the actors of a specific movie.
*movie-id*- Applied to a DT tag. This gives the id of a movie.
*movie-name*- Applied to a DT tag. This gives the name of a movie.
*movie-director*- Applied to a DT tag. This gives the director of a movie.
*movie-genre*- Applied to a DT tag. This gives the genres of a movie.
*movie-country*- Applied to a DT tag. This gives the country of a movie.
*movie-language*- Applied to a DT tag. This gives the language of a movie.
*movie-date*- Applied to a DT tag. This gives the release date of a movie.
*image*- Applied to a DT tag. This gives the image of a movie and an actor.
*actor-add*- Applied to a FORM tag. A non-idempotent link to create a new actor.
*actor-update*- Applied to a FORM tag. A non-idempotent link to update an existing actor.
*actor-name*- Applied to a DT tag. This gives the name of a actor.
*actor-birthday*- Applied to a DT tag. This gives the birthday of a actor.
*actor-update*- Applied to a FORM tag. A non-idempotent link to update an existing actor. 
*actor-search*- Applied to a FORM tag. A templat to search actor by name.
```

##Name attribute values##
```
*id*- Applied to an INPUT element. The id of the movie.
*name*- Applied to an INPUT element. The name of the movie.
*genre*- Applied to an INPUT element. The genres of the movie.
*director*- Applied to an INPUT element. The director of the movie.
*country*- Applied to an INPUT element. The country of the movie.
*language*- Applied to an INPUT element. The language of the movie.
*year*- Applied to an INPUT element. The year of the movie.
*image*- Applied to an INPUT element. The url of the movie`s poster image and actor image.
*actor*- Applied to an INPUT element. The name of the actor.
*birthday*- Applied to an INPUT element. The birthday of the actor.
```

##Rel attribute values##
```
*movie*- Applied to an A tag. A reference to the movie representation.
*actor*- Applied to an A tag. A reference to the actor representation.
*all-movies*- Applied to an A tag. A reference to the starting URI for the application.
*all-actors*- Applied to an A tag. A reference to the list of actors.
```

----------------------------------------------------------------------------------------------


##Microdata type
```
*itemtype="http://schema.org/Movie"*
*itemtype="http://schema.org/Person"*
```

##Microdata property
```
*itemprop="name"*- Used to identify names of movies, actors, directors. 
*itemprop="actor"*- Used to identify the actors of a movie.
*itemprop="director"*- Used to identify the director of a movie.
*itemprop="genre"*- Used to identify the genre of a movie.
*itemprop="contentLocation"*- Used to identify the country of a movie.
*itemprop="inLanguage"*- Used to identify the language of a movie.
*itemprop="datePublished"*- Used to identify the release date of a movie.
*itemprop="birthDate"*- Used to identify the birthday of an actor.
*itemprop="performerIn"*- Used to indentify the movies which an actor performed in. 
*itemprop="image"*- Used to identify image url of both movies and actors.
*itemprop="url"*- Used to identify every url.
```