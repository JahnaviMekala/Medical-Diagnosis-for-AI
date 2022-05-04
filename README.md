# Medical-Diagnosis-for-AI

Project for Artifical Intelligence - 1st Semester.

PROJECT MEMBERS:
-Sri Sowmya Korpu
-Jahnavi Mekala

Brief :
Health Care Chat-Bot is a Healthcare Domain Chatbot that simulates a General Physician's prognosis.

Bellow Information we used in the Project:
Dataset:

*Training dataset :
113 features , 4920 samples Testing dataset: 113 features, 41 samples “prognosis” features is used as label. Label Encoder is used to encode labels to numbers.

*Training, Testing and Cross Validation

clf1 = DecisionTreeClassifier() clf2 = clf1.fit(x_train,y_train) print(clf2.score(testx,testy)) Cross-validation: scores = cross_val_score(clf, x_test, y_test, cv=3) Print(scores.mean())

*Results

Training Accuracy: 0.97 Testing Accuracy: 0.94

*Imp Functions (code)

Main Function: 
Decision_tree_bot() is the main function that will be called when the program is run.
Sub Functions:
Binary_search_in_tree(): A subfunction of Decision_tree_bot() that does binary search using the user's responses to the bot's inquiries.
Print disease to user(): This function converts the decision tree's output into one of the diseases that the user is afflicted with.

**FutureImplementation

As Decision Trees overfit noisy data, ensemble techniques such as Random Forest can be used. However, ensemble approaches necessitate large datasets.

**Video : https://www.youtube.com/watch?v=hzjQEr9IcqY
