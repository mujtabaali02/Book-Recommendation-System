# Book-Recommendation-System

## **Overview about Project**


* A book recommender system is a tool that suggests books to users based on their interests and reading history. These systems can be used by libraries, bookstores, or online retailers to help users discover new books that they might enjoy.

* There are several approaches to building a book recommender system, including collaborative filtering, content-based filtering, and hybrid systems that combine both approaches.

![image](https://user-images.githubusercontent.com/74107667/208481351-a5aee77c-cf57-4144-9c01-83025abcd0a4.png)

* <b>Collaborative filtering</b> is based on the idea that users who have similar reading histories are likely to have similar interests, so a book that one user likes is likely to be enjoyed by another user with a similar reading history. This approach is often used in recommendation systems for movies, music, and other products.

* <b>Content-based filtering</b>, on the other hand, focuses on the characteristics of the books themselves, such as their genre, theme, and author, to make recommendations. This approach is useful when there is not enough data available about users' preferences to use collaborative filtering.

* <b>Hybrid systems</b> combine both collaborative filtering and content-based filtering to make recommendations. They can take into account both the characteristics of the books and the preferences of the users to provide a more personalized recommendation.

* There are several challenges to building an effective book recommender system, including the need for large amounts of data to train the system, the complexity of natural language processing, and the need to balance the personalization of recommendations with the diversity of the books recommended.

### **Dataset Description**
---
The Book-Crossing dataset comprises 3 files.

* **Users:** Contains the users. Note that user IDs (User-ID) have been anonymized and map to integers. Demographic data is provided (Location, Age) if available. Otherwise, these fields contain NULL values.

* **Books:** Books are identified by their respective ISBN. Invalid ISBNs have already been removed from the dataset. Moreover, some content-based information is given (Book-Title, Book-Author, Year-Of-Publication, Publisher), obtained from Amazon Web Services. Note that in the case of several authors, only the first is provided. URLs linking to cover images are also given, appearing in three different flavors (Image-URL-S, Image-URL-M, Image-URL-L), i.e., small, medium, large. These URLs point to the Amazon website.

* **Ratings:** Contains the book rating information. Ratings (Book-Rating) are either explicit, expressed on a scale from 1-10 (higher values denoting higher appreciation), or implicit, expressed by 0.

**Datasets Link:-** https://drive.google.com/drive/folders/1Gi0wMWCTigA_rJSi9huyT51lKduBSv43?usp=share_link 
