# music_tag_recommender
A Recommender System for Tagging Music.

# 1. Aim of the Project
When we think of AI and music, it's typically music classification or generation that come to mind first. In a podcast I listened to recently, Alex Jacobi from "With Love and Data" blew my mind with a completely different approach. With his team, he developed a ML model that let's media producers find the right music for their ads, movies, etc. much more efficiently. When they search for a few keywords, the model will also recommend them music that is not tagged with any of the keywords, but with keywords somehow related to those searched for. This is genius! <br>  <br>
Imagine how many opportunities you have missed, looking up the wrong keywords searching for books, academic literature, programming tutorials, or cat videos. I find it stunning. There's only two ways to improve searching for content with tags. 
1. Find ways to work around bad tagging
1. Find ways to use better tags
<br>
Alex Jacobi's work is a massive step towards the first. I want to take a small step towards the latter. I plan to to create a recommender system, that is trained with the tags people actually use for music. More specifically, I want to help creators and media producers find together through better tags. There are a lot of models that are trained on the relationship between words. These models would be able to recommend tags that go along well with the previous one. But music is a very special thing, and it's questionable whether you can draw conclusions for good music tagging from datasets trained on blogposts or chats. It would be much more helpful for creators to be recommended tags that media managers are going to search for and for media managers to be recommended tags that musicians actually use. That is the aim of this project!
