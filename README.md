# Hacker News Upvote Prediction

## Project Overview
In this project, we will try to predict the upvote score of posts on the Hacker News website https://news.ycombinator.com/ using at least their titles.

#### 1.Prepare the dataset of Hacker News titles and upvote scores

- Obtain the data from the database by connecting to it with this connection string: postgres://sy91dhb:g5t49ao@178.156.142.230:5432/hd64m1ki.
- Use psql or some other tool to connect.
- Tokenise the titles (see the next chapter)
- Implement and train an architecture to obtain word embeddings in the style of the word2vec paper --> https://arxiv.org/pdf/1301.3781.pdf using either the continuous bag of words (CBOW) or Skip-gram model (or both).
- training these on the text8 dataset, which you can find in a convenient format below. https://huggingface.co/datasets/ardMLX/text8

#### 2.Implement a regression model to predict a Hacker News upvote score from the pooled average of the word embeddings in each title.


