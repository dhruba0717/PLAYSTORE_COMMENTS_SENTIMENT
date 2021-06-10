# PLAYSTORE_COMMENTS_SENTIMENT
OBJECTIVE OF THE RESEARCH:

The main objective of the research is to obtain a feasible way to identify weather a review given by any random user is of good sense or bad sense using machine learning algorithms.
VARIOUS STEPS TO OBTAIN THE REQUIRED OBJECTIVE:-


1.	STUDY THE DATASET.
2.	VISUALIZE THE DATASET.
3.	FIND LINK BETWEEN DIFFERENT COLUMNS.
4.	IDENTIFY THE DEPENDENT AND INDEPENDENT VARIABLES.
5.	IDENTIFY IF THE DATA GIVEN IS CATEGORIZED OR UNCATEGORIZED.
6.	 APPLY REQUIRED ALGORITHMS TO FIND THE ACCURACY SCORE.
7.	OBSERVE THE DATASET FOR DIFFERENT CORRELATION AFTER APPLYING ALGORITHMS.
8.	PREDICT THE REQUIRED OUTPUT BY GIVING A RANDOM REVIEW.

PROCEDURE:
1.	IMPORTING THE NECESSARY LIBRARIES
 
2.	UPLOADING THE DATASET
 

3.	CONVERTING THE DATASET INTO A DATAFRAME.

4.	CHECKING THE NUMBER OF NaN VALUES IN EACH COLUMNS.( There are 26868 NAN values in each column)
         
5.	CHECKING THE COUNT/ MEAN OF COLUMNS TO BE REPLACED
 

6.	REPLACING THE DATA NaN USING FILLNA
 

7.	THE NUMBER OF NAN VALUES HENCE CAME DOWN TO 0.
 



8.	CHECKING THE NUMBER OF OUTLIERS USING BOXPLOT.
•	IN SENTIMENT POLARITY
 
•	IN SENTIMENT SUBJECTIVTY
 

9.	REPLACING QUARTILES(+ve AND –ve) WITH THIRD AND FIRST QUARTILE VALUE RESPECTIVEL.
 

 

10.	REPALCING THE SENTIMENT COLUMN INTO NUMERIC( 1 POSITIVE, 0 NEGATIVE)
 

 



11.	DATA PROCESSING BEGINS
(CONVERTING THE UPPER CASE REVIEW INTO LOWER CASE)
 

12.	EXTRACTING THE COLUMN INTO PROCESS DATA AND TARGET DATA AND THEN SPLITTING INTO TEST AND TRAIN.
 

13.	VECTORIZE TEXT REVIEWS INTO NUMBER AS MACHINE DOESN’T GET OBJECT DATA
 

14.	APPLYING LOGISTIC REGRESSION ALGORITHM TO FIT DATA AND IMPROVE ACCURACY
 



15.	PREDICTING THE TARGET VALUES
 

16.	CREATING A CONFUSION MATRIX
 

17.	CHECKING THE ACCURACY SCORE

 

The accuracy score(95.19%) is quite acceptable and hence the over fitting Is reduced and hence the output now can be predicted accurately up to certain limits.


18.	CHECKING THE OUTPUT

**BY ENTERING RANDOM USER REVIEWS

•	POSITIVE REVIEW

 
	The review shows array [1] depicting positive sentiment


•	NEGATIVE REVIEW

 

	This review shows array [0] depicting negative sentiment.


Hence SENTIMENT ANALYSIS OF USER REVIEW is perfectly predicted.
CONCLUSION


The sudden eruption of sentiment analysis and opinion mining has opened new possibilities to improve our information gathering interests. We are always keen to know what others say about the devices or applications we are going to use. It’s observed that sometimes the numeric rating has vast difference than the reviews given by the users. To remove this ambiguity a unified rating system has been proposed here. The starred rating and a generated numeric polarity of the reviews are combined to generate the final rating. The proposition is based on sentiment analysis and an optimized probabilistic approach described by a group of researchers. The approach is proved for its efficiency in a diverse corpus of writings where the targets are of different categories.
