# Jobs and Salaries

This is a data feature that helps users find possible jobs related to their career and the salaries they offer.

## **Features**
- Takes **keywords** related to the user's major or industry of interest and provides 5 suitable job titles for them.
- Takes the **job titles** and the **city** users live in, and provides the median salary for the job.
- Provides **sources** and **links** to the jobs found.

## **Prerequisites**
To run the notebook, you need to set up API keys for:
1. **Perplexity API** (model: llama-3.1-8b-instruct) – to get job title recommendations.
2. **Rapid Job Salary API** – to look up salary and other job-related data.

Make sure to save your API keys in the **Secret** tab in Google Colab under the following names:
- `perplexity_api`
- `rapid_salary_api_key`

## **Usage**
1. Run the notebook cells in order.
2. When prompted, enter your **major** or the **industry** you want to work in.
3. The notebook will show you 5 job titles.
4. Choose one of the titles and enter it into the box.
5. Enter your **city name**.
6. The notebook will display all the jobs in your city under that title and the salaries they offer.

## **Note**
This project was done for **educational purposes**. To use it in real life, more features and fact-checking will be necessary.
