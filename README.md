
# Game Recommendation Algorithm

Final project for the Building AI course

## Summary

Similar to many online databases, BoardGameGeek.com has a huge amount of content, which is only as useful as users are able to find content they like in it. This project proposes an AI based recommendation tool for finding similar board games or like minded board gamers. 


## Background

Typical board game user might have a favourite game they like, and are willing to find similar games. Or as another use case, they might know some opinion leader and want to find other users they like to follow, with similar taste in board games.

Board games are a personal hobby of mine, and there are always new games waiting to be discovered. Providing an effective tool to find them will benefit a wide group of board game hobbyists.

As an AI problem this probably is not the most important, but trying to keep the focus small will make it easier to complete the project.


## How is it used?

Describe the process of using the solution. In what kind situations is the solution needed (environment, time, etc.)? Who are the users, what kinds of needs should be taken into account?

Images will make your README look nice!
Once you upload an image to your repository, you can link link to it like this (replace the URL with file path, if you've uploaded an image to Github.)
![Cat](https://upload.wikimedia.org/wikipedia/commons/5/5e/Sleeping_cat_on_her_back.jpg)

If you need to resize images, you have to use an HTML tag, like this:
<img src="https://upload.wikimedia.org/wikipedia/commons/5/5e/Sleeping_cat_on_her_back.jpg" width="300">

This is how you create code examples:
```
def main():
   countries = ['Denmark', 'Finland', 'Iceland', 'Norway', 'Sweden']
   pop = [5615000, 5439000, 324000, 5080000, 9609000]   # not actually needed in this exercise...
   fishers = [1891, 2652, 3800, 11611, 1757]

   totPop = sum(pop)
   totFish = sum(fishers)

   # write your solution here

   for i in range(len(countries)):
      print("%s %.2f%%" % (countries[i], 100.0))    # current just prints 100%

main()
```


## Data sources and AI methods

The source for the data in this project is [BoardGameGeek](https://boardgamegeek.com) website. Its database can be accessed through two different APIs: [BGG XML API](https://boardgamegeek.com/wiki/page/BGG_XML_API) and [BGG XML API2](https://boardgamegeek.com/wiki/page/BGG_XML_API2), which is in beta phase. Importat data to collect would be at least board games and user ratings for the games. Potentially beneficial are also board game details such as game designer, play time, number of players.


## Challenges

What does your project _not_ solve? Which limitations and ethical considerations should be taken into account when deploying a solution like this?

## What next?

How could your project grow and become something even more? What kind of skills, what kind of assistance would you  need to move on? 


## Acknowledgments

* list here the sources of inspiration 
* do not use code, images, data etc. from others without permission
* when you have permission to use other people's materials, always mention the original creator and the open source / Creative Commons licence they've used
  <br>For example: [Sleeping Cat on Her Back by Umberto Salvagnin](https://commons.wikimedia.org/wiki/File:Sleeping_cat_on_her_back.jpg#filelinks) / [CC BY 2.0](https://creativecommons.org/licenses/by/2.0)
* etc
