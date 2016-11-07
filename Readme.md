Ghost Busters
=============

A xgboost based solution to a fun problem to classify Ghosts, Ghouls and Ghosts based on features like `bone_length`, `has_soul` etc.

https://www.kaggle.com/c/ghouls-goblins-and-ghosts-boo

Validation Framework
====================

Since the data is well distributed, will be using stratified sampling and trying
out `xgb.cv` for cross validation
