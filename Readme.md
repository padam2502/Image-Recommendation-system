# Image Recommendation System

Image Recommendation system for different users using Collaborative Filtering.

## Description

- Collaborative Filtering is a way to predict items to the user based on the the user’s history and the history of similar users. The similarity between users can be quantified by the number of images that both the users appreciated.
- The images appreciated by a similar user would be the most suitable images to show a user. Since we can find the similarity between any two users, we would be able to find the “nearest” neighbours of any user, allowing us to use a KNN-based algorithm to recommend new images to a user.
- Since people do not like seeing pictures that they have seen already. So the system does not recommend pictures that a user has appreciated already.


## About the Dataset
Behance is a community art website where users showcase and discover creative work. Each user is able to “appreciate” (equivalent to a “like” on Instagram or a “react” on Facebook) an image, indicating that they like the image. It is in the website’s best interests to show users pictures that they would like, to keep them engaged for longer. For this question, given a set of pictures that a user has already appreciated, you have to show them a new picture that they would like based on what similar users appreciated.
<br><br>
**The dataset has information of 1 million appreciates of 63,497 users on 178,788 items. The file Behance appreciate 1M has a triplet in each line in the form of (user id, item id, unix timestamp).**



### Libraries Used

* NumPy,Pandas,SciPy,Sklearn

### Major Concept Involved

* Collaborative Filtering
* SVD
* KNN
* Sparse Matrix
* Cosine Distance


### Executing program

* Run the Cells

### Output

- Final output response will be saved in the file named ```config['output_file']```.

