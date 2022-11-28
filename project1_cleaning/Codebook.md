{\rtf1\ansi\ansicpg1252\cocoartf2639
\cocoatextscaling0\cocoaplatform0{\fonttbl\f0\fnil\fcharset0 .SFNS-Regular_wdth_opsz180000_GRAD_wght2580000;\f1\fnil\fcharset0 HelveticaNeue;\f2\fnil\fcharset0 .SFNS-Regular_wdth_opsz140000_GRAD_wght2580000;
}
{\colortbl;\red255\green255\blue255;\red189\green198\blue208;\red12\green14\blue18;\red72\green146\blue255;
}
{\*\expandedcolortbl;;\cssrgb\c78824\c81961\c85098;\cssrgb\c5098\c6667\c9020;\cssrgb\c34510\c65098\c100000;
}
{\*\listtable{\list\listtemplateid1\listhybrid{\listlevel\levelnfc23\levelnfcn23\leveljc0\leveljcn0\levelfollow0\levelstartat1\levelspace360\levelindent0{\*\levelmarker \{disc\}}{\leveltext\leveltemplateid1\'01\uc0\u8226 ;}{\levelnumbers;}\fi-360\li720\lin720 }{\listname ;}\listid1}}
{\*\listoverridetable{\listoverride\listid1\listoverridecount0\ls1}}
\paperw11900\paperh16840\margl1440\margr1440\vieww11520\viewh8400\viewkind0
\deftab720
\pard\pardeftab720\sa320\partightenfactor0

\f0\b\fs48 \cf2 \cb3 \expnd0\expndtw0\kerning0
Getting and Cleaning Data Project\cb1 \
\pard\pardeftab720\sa320\partightenfactor0

\f1\b0\fs32 \cf2 \cb3 Author: Sanyam Singhal\cb1 \
\pard\pardeftab720\partightenfactor0

\f2\b\fs40 \cf4 \
\pard\pardeftab720\sa320\partightenfactor0
\cf2 \cb3 Description\cb1 \
\pard\pardeftab720\sa320\partightenfactor0

\f1\b0\fs32 \cf2 \cb3 Additional information about the variables, data and transformations used in the course project for the Johns Hopkins Getting and Cleaning Data course.\cb1 \
\pard\pardeftab720\partightenfactor0

\f2\b\fs40 \cf4 \
\pard\pardeftab720\sa320\partightenfactor0
\cf2 \cb3 Source Data\cb1 \
\pard\pardeftab720\sa320\partightenfactor0

\f1\b0\fs32 \cf2 \cb3 Data + Description can be found here {\field{\*\fldinst{HYPERLINK "http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones"}}{\fldrslt \cf4 UCI Machine Learning Repository}}\cb1 \
\pard\pardeftab720\partightenfactor0

\f2\b\fs40 \cf4 \
\pard\pardeftab720\sa320\partightenfactor0
\cf2 \cb3 Data Set Information\cb1 \
\pard\pardeftab720\sa320\partightenfactor0

\f1\b0\fs32 \cf2 \cb3 The experiments have been carried out with a group of 30 volunteers within an age bracket of 19-48 years. Each person performed six activities (WALKING, WALKING_UPSTAIRS, WALKING_DOWNSTAIRS, SITTING, STANDING, LAYING) wearing a smartphone (Samsung Galaxy S II) on the waist. Using its embedded accelerometer and gyroscope, we captured 3-axial linear acceleration and 3-axial angular velocity at a constant rate of 50Hz. The experiments have been video-recorded to label the data manually. The obtained dataset has been randomly partitioned into two sets, where 70% of the volunteers was selected for generating the training data and 30% the test data.\cb1 \
\cb3 The sensor signals (accelerometer and gyroscope) were pre-processed by applying noise filters and then sampled in fixed-width sliding windows of 2.56 sec and 50% overlap (128 readings/window). The sensor acceleration signal, which has gravitational and body motion components, was separated using a Butterworth low-pass filter into body acceleration and gravity. The gravitational force is assumed to have only low frequency components, therefore a filter with 0.3 Hz cutoff frequency was used. From each window, a vector of features was obtained by calculating variables from the time and frequency domain.\cb1 \
\pard\pardeftab720\partightenfactor0

\f2\b\fs40 \cf4 \
\pard\pardeftab720\sa320\partightenfactor0
\cf2 \cb3 Attribute Information\cb1 \
\pard\pardeftab720\sa320\partightenfactor0

\f1\b0\fs32 \cf2 \cb3 For each record in the dataset it is provided:\cb1 \
\pard\tx220\tx720\pardeftab720\li720\fi-720\partightenfactor0
\ls1\ilvl0\cf2 \cb3 \kerning1\expnd0\expndtw0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
Triaxial acceleration from the accelerometer (total acceleration) and the estimated body acceleration.\cb1 \
\ls1\ilvl0\cb3 \kerning1\expnd0\expndtw0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
Triaxial Angular velocity from the gyroscope.\cb1 \
\ls1\ilvl0\cb3 \kerning1\expnd0\expndtw0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
A 561-feature vector with time and frequency domain variables.\cb1 \
\ls1\ilvl0\cb3 \kerning1\expnd0\expndtw0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
Its activity label.\cb1 \
\ls1\ilvl0\cb3 \kerning1\expnd0\expndtw0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
An identifier of the subject who carried out the experiment.\cb1 \
\pard\pardeftab720\partightenfactor0

\f0\b\fs48 \cf4 \
\pard\pardeftab720\sa320\partightenfactor0
\cf2 \cb3 Please see the README.md for how the following instructions are implemented {\field{\*\fldinst{HYPERLINK "https://github.com/mGalarnyk/datasciencecoursera/blob/master/3_Getting_and_Cleaning_Data/README.md"}}{\fldrslt \cf4 README.md}}\cb1 \
\pard\pardeftab720\partightenfactor0

\f2\fs40 \cf4 \
\pard\pardeftab720\sa320\partightenfactor0
\cf2 \cb3 1. Merge the training and the test sets to create one data set.\cb1 \
\pard\pardeftab720\partightenfactor0
\cf4 \
\pard\pardeftab720\sa320\partightenfactor0
\cf2 \cb3 2. Extracts only the measurements on the mean and standard deviation for each measurement.\cb1 \
\pard\pardeftab720\partightenfactor0
\cf4 \
\pard\pardeftab720\sa320\partightenfactor0
\cf2 \cb3 3. Uses descriptive activity names to name the activities in the data set\cb1 \
\pard\pardeftab720\partightenfactor0
\cf4 \
\pard\pardeftab720\sa320\partightenfactor0
\cf2 \cb3 4. Appropriately labels the data set with descriptive variable names.\cb1 \
\pard\pardeftab720\partightenfactor0
\cf4 \
\pard\pardeftab720\partightenfactor0
\cf2 \cb3 5. From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.}