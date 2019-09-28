# Building a Recommender System for Lucid
We built an article recommendation system that computes similarity between posts based on its content and recommends posts that are similar. To test you pass in a post title that exists in the dataset to the function and you will get similar posts as the output. An example is shown below:

```
samplePost = 'What i have learnt so far on HTML'
recommendSimilarPosts = get_article_recommendations_for_user(samplePost)
```

## Architecture
We used Restricted Boltzmann Machines (RBMs), a Deep Learning algorithm to create our recommendation engine.


## Testing our model
You can test our model using colab at this link https://colab.research.google.com/drive/1FKGFQpPyw6dPxCaFSpnm00p1SnMqguy5#scrollTo=OeZi6U2spauu

Run the colab file.
