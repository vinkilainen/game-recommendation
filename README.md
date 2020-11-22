
# Game Recommendation Algorithm

Final project for the Building AI course

## Summary

Similar to many online databases, BoardGameGeek.com has a huge amount of content, which is only as useful as users are able to find content they like in it. This project proposes an AI based recommendation tool for finding similar board games. 


## Background

Typical board game user might have a favourite game they like, and are willing to find similar games. Or as another use case, they might know some opinion leader and want to find other users they like to follow, with similar taste in board games.

Board games are a personal hobby of mine, and there are always new games waiting to be discovered. Providing an effective tool to find them will benefit a wide group of board game hobbyists.

As an AI problem this probably is not the most important, but trying to keep the focus small will make it easier to complete the project.


## How is it used?

The solution is for hobbyists that are interested in board games. Typical use would be to find a new game that is similar to some other games user is already familiar with. Another potential use would be to find similar users to gain insight from the games they like, but current user does not yet know.

I find this solution to be very similar to many recommendation systems in online shopping or for example movie recommendations such as [IMDb](https://www.imdb.com) provides to users. Since you like this board game, you might also be interested in these other games.

Technically, I would expect that a neural network would be good for finding these hidden connections between games and gamers. Also some clustering solutions could be useful for grouping similar games together. And for the users, a search tool where they can adjust their preferences, since the same user could be interested in some long game for Friday night with friends, and then some simple children's game for Saturday morning with kids. And it goes without saying that automatic recommendations are a key, since the search already requires some effort, and I believe this solution would benefit from being as effortless for the user as possible.


## Data sources and AI methods

The source for the data in this project is [BoardGameGeek](https://boardgamegeek.com) website. Its database can be accessed through two different APIs: [BGG XML API](https://boardgamegeek.com/wiki/page/BGG_XML_API) and [BGG XML API2](https://boardgamegeek.com/wiki/page/BGG_XML_API2), which is in beta phase. Important data to collect would be at least board games and user ratings for the games. Potentially beneficial are also board game details such as game designer, play time, number of players.


## Challenges

For the recommendation algorithm, the greatest challenge is to provide meaningful recommendations to the users. Not so that all users will get the same recommendations, but so that the user input actually has an effect for the outcome.


## What next?

There are a long list of various data items in the BoardGameGeek database that could be included as a source item for the algorithm. Further goal could be to have the algorithm so successful that it gets integrated into a part of the BGG website.


## Acknowledgments

* [BoardGameGeek](https://boardgamegeek.com) web site
* [IMDb](https://www.imdb.com) movie recommendations
