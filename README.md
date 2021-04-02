# movielens-recommendation-system

Here [MovieLens 20M Dataset](https://www.kaggle.com/grouplens/movielens-20m-dataset) by `GroupLens` is used to build `content based` and `collaborative filtering` recommendation systems.

`Content-Based` or `Item-Item recommendation systems`, this technique attempts to figure out what a user's favourite aspects of an item is and then recommends items that present those aspects.

`Collaborative Filtering`, which is also known as `User-User Filtering`. As hinted by its alternate name, this technique uses other users to recommend items to the input user. It attempts to find users that have similar preferences and opinions as the input and then recommends items that they have liked to the input. There are several methods of finding `similar users` (Even some making use of Machine Learning), and the one used here is based on the `Pearson Correlation Function`.

## Table of contents

- [Getting started](#getting-started)
- [License](#license)

## Getting started

The [notebook](https://www.kaggle.com/akashsdas/movielens-recommendation-system) is available on Kaggle to work in the same environment where this notebook was created i.e. use the same version packages used, etc...

## License

[APACHE LICENSE, VERSION 2.0](./LICENSE)
