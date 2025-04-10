# Kaggle_MultiClassification


# Dataset Description

The Estonian Mushroom Image Classification Dataset is a new collection of images representing the most popular mushroom species found in Estonia. It is structured into ten classes, each corresponding to a specific mushroom species. The dataset consists of 300 images per class, totalling 3000 images.

In this competition, you’ll gain access to two similar datasets that include images of mushrooms. One dataset is titled train.csv and the other is titled test.csv.

Train.csv will contain the details of a subset of the mushrooms and importantly, also have "ground truth" attached to them.

The test.csv dataset contains similar information but does not disclose the “ground truth” for each mushroom. It’s your job to predict these outcomes.

Using the patterns you find in the train.csv data, predict which class the other mushrooms on (found in test.csv) belong to.

# Submission File Format:
You shouldsubmit a csv file with 598 entries plus a header row. Your submission will show an error if you have extra columns (beyond Id and Predicted) or rows.

The file should have exactly 2 columns:

Id
Predicted (contains your predictions: 0-9)
Files
train.csv - the training set
test.csv - the test set

What label corresponds to what type of mushroom
amanita - 0
boletus - 1
chantelle - 2
deterrimus - 3
rufus - 4
torminosus - 5
aurantiacum - 6
procera - 7
involutus - 8
russula - 9
