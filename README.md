# Four-different-ways-to-predict-reviews-rating-through-text-analysis
topic: Data Mining; Rating Prediction; Sentiment Analysis

# ABSTRACT

Nowadays, organizations are accumulating vast and growing
amounts of data in different formats, storing them in huge
databases. This data can provide useful information through
patterns, associations or relationships. Therefore, data mining has
emerged to analyse a huge amount of data in automatic or semi-
automatic way, in order to discover as much information as
possible about them. Moreover, also the amount of online reviews
is growing rapidly and their role in e-commerce has become
increasingly important. Both academics and practitioners is
aiming at extracting meaningful information from these reviews
through text mining techniques. In this paper we describe our
implementation of an algorithm used to predict the rating of an
input text review, based on a list of positive and negative opinion
words.

# INTRODUCTION

In the last few years, progress in digital data acquisition and
storage technology has led in the growth of huge datasets [1]. For
this reason, data mining has recently emerged as an
interdisciplinary subfield of computer science. Data mining has
the goal of extracting as much information as possible from a
dataset and transform it into an understandable and useful
structure for further use [2]. The automatic or semi-automatic
analysis of huge quantities of data aims to discover interesting
patterns such as groups of data records, unusual records and
dependencies. These patterns may be used in further analysis or in
machine learning and predictive analytics.
Data mining can be used in a predictive way for a great variety of
different applications. Indeed, it is widely used in business,
science research and government security. Moreover, some of the
major database vendors have already taken steps to ensure that
their platform incorporate data mining techniques [3]. For
example, Oracle's Data Mining Suite [4] and Microsoft's SQL
Server [5] implement some algorithms and techniques of data
mining.
One important step toward building a efficient data mining
program is the gathering of data. This process of gathering data
for analysis is critical to the eventual success of any data mining
project and many companies already perform this task. Starting
with a dataset it need to be used an algorithm to extract the desired
information. The two most popular algorithms used in data mining
are regression and classification.
Regression is used to measure the relation between one dependent
variable and one or more other independent variables. Instead,
classification aims to discover to which set of categories a new
element belongs. They are both considered exponents of
supervised learning, a subfield of machine learning.
Another relevant technique related to data mining is text mining.
It has the purpose of extracting meaningful information from a
text. Nowadays, more and more users can freely express their
opinions about products or services on Internet. These reviews can
be very useful both to other users for making informed decisions
and to companies for upgrading their services [6]. Moreover, the
amount of reviews grows rapidly and understanding their role in
e-commerce has become an important topic both for academics
and practitioners [7].
In the following sections is described our idea and the
implementations of work that was done. We thought about an
algorithm which could be used to predict the rating of an input
text review, based on all others rating reviews in the dataset. We
compare the input review with each other review in the dataset to
determine which are the most similar to the input review. We
determine three different similarities using a set of positive and
negative opinion words. Finally, we use the computed similarities
and linear regression for predicting the ratings of the input review.
This paper is organized as follows: section 2 describes related
works which have been used as starting point for our
implementation of the project Section 3 presents the problem we
are trying to solve whereas section 4 provides our solution and
implementation. Section 5 describes all the experiments we
performed using different review datasets and input texts. Finally,
we conclude in section 6.
