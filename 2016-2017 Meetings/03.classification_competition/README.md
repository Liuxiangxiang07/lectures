# Classification Competition

You have 50 minutes to build a classifier to detect email spam. The training data is pickled in `spam_train.p`. You can use `sklearn.externals.joblib` to load it. It is stored in the same kind of object as returned by `load_digits` - i.e., an object with attributes `data`, which contains the input data, and `target`, which contains the labels. There is a starter template in the form of a jupyter notebook at the aptly named `starter_template.ipynb`.

Once you are happy with your classifier, you can "dump" it into a pickled file using `joblib.dump`. Please name your pickled model `[team-name].p` and send it as an attachement to mwluw@uw.edu. You can pick your team name :smile:. Good luck! 