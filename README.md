# Machine-Learning

## Description
"Lokis: Lokasi Seru" aims to create an application that provides tourist attraction recommendations in the Jabodetabek area. The app considers users' preferences and offers packages of various tourist attractions based on parameters such as city, price, category, and time.

## Shortest Route Optimization
The Traveling Salesman Problem (TSP) is a classic conundrum that seeks the most efficient route for salesmen visiting multiple cities without revisiting the same city.

Reinforcement learning, a subset of machine learning, focuses on how intelligent agents can make decisions in an environment to maximize cumulative rewards. RL, along with supervised and unsupervised learning, represents one of the three fundamental machine learning paradigms.

## Recommendation System:
Collaborative filtering is a technique that filters items a user might like based on reactions from similar users. It involves searching a large user group to identify a small subgroup with similar tastes to a particular user.

Content-based recommenders treat recommendations as user-specific classification problems. They learn classifiers for user preferences based on item features. In this system, keywords describe items, and user profiles indicate the types of items users prefer.

### Dataset

To build the TSP we were inspired to use this dataset to check if our optimization route works especially for testing Reinforcement Learning in [here](http://elib.zib.de/pub/mp-testdata/tsp/tsplib/tsp/index.html)

and we were inspired by this data set to build our recommendation system in [here](https://www.kaggle.com/azharianisah/infotempatwisata) and in [here](https://data.world/cityofaustin/m964-vp2q)

But we decided to build our own dataset because we didn't find the right dataset for our project. We crawl data from many sources and make it into a single dataset which you can view in [here](https://docs.google.com/spreadsheets/d/1lq6qeYAhBJBJbuyC9DpwKehQ6mWswMkd-NMfbDlkwnw/edit?pli=1#gid=990183666)

## 📚 Libraries Used

This project utilizes several Python libraries for data handling, machine learning, and visualization:

| Library                | Purpose                                                   |
| ---------------------- | --------------------------------------------------------- |
| `pandas`               | Facilitates data manipulation and analysis with data frames. |
| `numpy`                | Enables efficient numerical computations and array operations. |
| `tensorflow`           | An open-source machine learning framework for building and training models. |
| `keras`                | High-level neural networks API, integrated with TensorFlow for easy model construction. |
| `matplotlib.pyplot`    | Used for creating visualizations, plots, and charts in Python. |
| `IPython.display`      | Provides tools for interactive computing, useful for dynamic displays. |
| `jiwer`                | Calculates Word Error Rate (WER) for evaluating speech recognition performance. |

### Reference
* Solved TSP for optimasion route with RL in [here](https://medium.com/unit8-machine-learning-publication/routing-traveling-salesmen-on-random-graphs-using-reinforcement-learning-in-pytorch-7378e4814980)
* Build Content-based recomendation system in [here](https://www.kdnuggets.com/2020/07/building-content-based-book-recommendation-engine.html)
* Collaborative Filtering in [here](https://gilberttanner.com/blog/building-a-book-recommendation-system-usingkeras)
