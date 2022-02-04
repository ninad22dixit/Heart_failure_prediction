# Heart_failure_prediction
Capstone - 2

**Problem Statement:** How can healthcare providers predict heart failure with > 85% accuracy among individuals when their medical records are available?

**Context:** Cardiovascular diseases (CVDs) led to nearly 17.9 million deaths in 2019, which account for 32% of all global deaths. Nearly 85% of them were because of heart attack and stroke. Several health issues may serve as precursors to CVDs and heart failure/stroke. A model that can predict heart failure in patients can lead to early management of the problem and help in reducing the mortality rate. More information is available here: https://www.who.int/news-room/fact-sheets/detail/cardiovascular-diseases-(cvds)

**Criteria for success:** Given the medical record of an individual, predict heart failure with > 85% accuracy.

**Scope of solution space:** The data used in the project was collected over a few locations in the US and Europe. Thus, its analysis will likely be relevant to the patients from the US and Europe.

**Constraints:** The data and its predictive analysis are not time-sensitive, i.e., this project cannot predict “when” a CVD will likely cause heart failure. 

**Data Sources:** The following data set contains 11 features collected for > 900 individuals across the US, Hungary, and Switzerland:  https://www.kaggle.com/fedesoriano/heart-failure-prediction

**Project strategy:** Use regression analysis to predict heart failure in a patient. Compare Linear and Random Forest regressors. Employ other options if the models developed using the said regressors do not exceed the minimum accuracy requirement. Maximize accuracy by tuning hyperparameters.

**Deliverables:**
A Github repository containing work performed during each step of the project
A detailed project report
A presentation summarizing the work done
