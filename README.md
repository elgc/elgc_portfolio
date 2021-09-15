# Portfolio

01100001 01101101 01100100 01100111

### Ernesto L. Garcia C., PhD.

*"Continuous improver, able to choose the right technology, understand the business context and solve a wide set of problems individually or as a team."*

### 1. [Market Segmentation using RFM and Cluster Analysis](https://github.com/elgc/Market_Segmentation/blob/main/MarketSegmentation1.ipynb)
**(Data Science)**

These real data (reduced, scaled and transformed) consists of 594,783 purchasing entries with three columns: *Date*, *Client*, and *Sale* value. 

- **Customer segmentation** is the process of dividing a market into sub-groups of clients based on some type of shared characteristics.
- **RFM** stands for Recency, Frequency, and Monetary value (Sales in this example).
- **Task objective:** segment clients based on when their last purchase was (Recency), how often they’ve purchased in the past (Frequency), and how much they’ve spent overall (Sales). All three of these measures are effective predictors of a customer's willingness to engage in marketing messages and offers.
- **Cluster analysis**: ML tech used to group similar objects into respective categories. It is also known as segmentation analysis, taxonomy analysis, or clustering. 
- **Output:** Once these groups were clearly defined, a marketing team could target clients with specific strategies and increase profits.

![](/Images/NoClusters.png)
![](/Images/Clust2.png)
---
### 2. [A3 and TBP for Process Improvement](https://github.com/elgc/Portfolio/blob/main/A3TBP_Appaloosa.pdf)
**(Lean-Six Sigma)** <br/>

-Short paper on the use of the **A3/TBP methodology** for sustainable and dramatic process improvement. 
-**Objective:** Comunicate that any transformational project needs to be explored and observed in the *"place where the action is."* The term for exploring and observing a process is called **Genchi Genbutsu**.
-**Caveat:** Through each step of the A3 methodology I have used baseball quotes. When I sent the first draft for feedback some of my colleages from overseas replied that they were not able to understand the quotes due to their lack of familiarity with baseball. A future case, with soccer references :), is on the way.

![](/Images/Before.png)
---
### 3. [Classifiers improving human appraisers evaluation]()
**(KNN, SVM, Logistic Regression)**

[KNN](https://github.com/elgc/Other-Classifiers/blob/main/KNN-Sonar%20Data.ipynb)

[SVM with linear kernel](https://github.com/elgc/Other-Classifiers/blob/main/Sonar%20Data%20with%20Support%20Vector%20Machine%20Linear%20kernel.ipynb)

[SVM with radial kernel](https://github.com/elgc/Other-Classifiers/blob/main/Sonar%20Data%20Support%20Vector%20Machine%20Radial%20Kernel.ipynb)

[Binary logistic regression](https://github.com/elgc/Other-Classifiers/blob/main/Logistic%20Regression-Sonar%20Data.ipynb)


Four simple classifiers are used to provide better performance than human inspectors in the detection of submarine mines. The data is as follows:

File with 1) Bouncing sonar signals off a metal cylinder at various angles and under various conditions, and 2) from bouncing sonar signals off rocks under similar conditions. The transmitted sonar signal is a frequency-modulated chirp, rising in frequency. The data set contains signals obtained from a variety of different aspect angles, spanning 90 degrees for the cylinder and 180 degrees for the rock.

Each pattern is a set of 60 features in the range 0.0 to 1.0. Each feature representing the energy within a particular frequency band, integrated over a certain period of time.

The label associated with each record contains "Rock" or "Mine".

Three trained human subjects were each tested on 100 signals, chosen at random from the set of 208 returns used to create this data set. Their responses ranged between **88% and 97% correct**. However, they may have been using information from the raw sonar signal that is not preserved in the processed data sets presented here.

One of the models obtained accuracy of **98.1%**

![](/Images/Table.png)
