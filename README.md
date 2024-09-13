# ML-Portfolio-Random-Forest-Regressor-Salaries-Predictor

The salaries are from ai-jobs. Ai-jobs collects salary information anonymously from professionals all over the world in the AI/ML and Big Data space and makes it publicly available for anyone to use, share and play around with. The data is being updated regularly with new data coming in, usually on a weekly basis.
The primary goal is to have data that can provide better guidance in regards to what's being paid globally. So newbies, experienced pros, hiring managers, recruiters and also startup founders or people wanting to make a career switch can make better informed decisions.

The dataset contains one table structured as follow:

work_year: The year the salary was paid.

experience_level: The experience level in the job during the year with the following possible values:

EN: Entry-level / Junior

MI: Mid-level / Intermediate

SE: Senior-level / Expert

EX: Executive-level / Director

employment_type: The type of employement for the role:

PT: Part-time

FT: Full-time

CT: Contract

FL: Freelance

job_title: The role worked in during the year.

salary: The total gross salary amount paid.

salary_currency: The currency of the salary paid as an ISO 4217 currency code.

salary_in_usd: The salary in USD (FX rate divided by avg. USD rate for the respective year via fxdata.foorilla.com).

employee_residence: Employee's primary country of residence in during the work year as an ISO 3166 country code.

remote_ratio: The overall amount of work done remotely, possible values are as follows:

0: No remote work (less than 20%)

50: Partially remote

100: Fully remote (more than 80%)

company_location: The country of the employer's main office or contracting branch as an ISO 3166 country code.

company_size: The average number of people that worked for the company during the year:

S: less than 50 employees (small)

M: 50 to 250 employees (medium)

L: more than 250 employees (large)

I applied the Random forest regressor and linear regression but the best accuracy is achieved through random forest regressor.

Model: Random Forest Regressor

R2 Score: 0.9671

Mean Absolute Error (MAE): 1190.1960

Root Mean Squared Error (RMSE): 14070.1127

----------------------------------------
Model: Linear Regression

R2 Score: 0.0222

Mean Absolute Error (MAE): 55312.7144

Root Mean Squared Error (RMSE): 76717.5722

----------------------------------------

The ML Portfolio Project AI/ML Salaries contains the EDA and Ml part of AI,ML salaries data. 

The ML Portfolio Project Fast API file contains the FastApi application.

The ML Portfolio Project hugging face Create a Gradio application that interacts with the FastAPI endpoint.

Here's is the URL for Hugging face application =
