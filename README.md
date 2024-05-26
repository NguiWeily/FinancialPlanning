# FinancialPlanning
![image](https://github.com/NguiWeily/FinancialPlanning/assets/111359787/187d8c50-5871-4f4a-8129-9c91dd6be37b)

Form Submission: When the user uploads the documents and submits the form, the backend processes the files, generates a financial plan using OpenAI's API, and then redirects to the chat page with the financial plan as a parameter.

Chat Page: The chat page displays the financial plan and provides an interface for the user to interact with GPT-3.5.
By following these steps, the application will automatically redirect the user to the chat page after displaying the financial plan, allowing for a seamless transition and continued interaction with GPT-3.5.

The application will automatically redirect the user to the chat page after displaying the financial plan, allowing for a seamless transition and continued interaction with GPT-3.5.

Steps to Obtain an API Key from OpenAI
Visit OpenAI's Website:

Go to the OpenAI website.
Sign Up for an Account:

If you don’t have an account, you’ll need to sign up. Look for a "Sign Up" or "Get Started" button on the homepage.
Verify Your Email:

After signing up, you’ll receive a verification email. Follow the instructions in the email to verify your account.
Access the API Dashboard:

Once your account is verified, log in to the OpenAI API platform https://platform.openai.com/ .
Navigate to the API dashboard where you can manage your API keys and usage.
Generate an API Key:

In the API dashboard, you can generate a new API key. This key will be used to authenticate your requests to the OpenAI API.
Exploring Free Credits or Special Access

Output:

To create a detailed retirement plan based on the financial statement provided, we need to consider several assumptions and scenarios. Here's an outline of the steps we'll take:

1. Current Financial Situation Analysis:
    - Summarize the balances in various accounts.
    - Determine the total assets in SGD equivalent.

2. Retirement Goals:
    - Define retirement age and expected retirement duration.
    - Estimate annual expenses during retirement.

3. Assumptions:
    - Inflation rate.
    - Expected rate of return on investments.
    - Life expectancy.
    - Other income sources (e.g., CPF, rental income).

4. Scenarios:
    - Conservative: Low return, high inflation.
    - Moderate: Moderate return, moderate inflation.
    - Aggressive: High return, low inflation.

5. Plan Development:
    - Calculate the required retirement corpus.
    - Determine the gap between current assets and required corpus.
    - Suggest investment strategies to bridge the gap.

### Step 1: Current Financial Situation Analysis

Account Summary:

- Deposits:
  - Current and Savings Account Total: SGD 117,776.59
  - Fixed Deposit Total: SGD 61,270.00

Total Assets: SGD 179,046.59

### Step 2: Retirement Goals

- Retirement Age: Assume 65 years.
- Life Expectancy: Assume 85 years.
- Retirement Duration: 20 years.
- Annual Expenses: Assume SGD 40,000 per year.

### Step 3: Assumptions

- Inflation Rate: 2.5% per year.
- Expected Rate of Return on Investments:
  - Conservative: 3% per year.
  - Moderate: 5% per year.
  - Aggressive: 7% per year.

### Step 4: Scenarios

Conservative Scenario:
- Inflation: 2.5%
- Return on Investments: 3%

Moderate Scenario:
- Inflation: 2.5%
- Return on Investments: 5%

Aggressive Scenario:
- Inflation: 2.5%
- Return on Investments: 7%

### Step 5: Plan Development

Let's calculate the retirement corpus required for each scenario:

Formula for Future Value of Annual Expenses:
\[ \text{FV} = \text{PV} \times (1 + \text{inflation rate})^{\text{number of years}} \]

Required Corpus:
\[ \text{Corpus} = \text{Annual Expenses} \times \frac{(1 - (1 + \text{return rate})^{-\text{retirement duration}})}{\text{return rate}} \]

#### Conservative Scenario

- Annual Expenses adjusted for inflation (65 years old): 
\[ 40,000 \times (1 + 0.025)^{30} = 40,000 \times 2.0969 = 83,876 \]
- Required Corpus:
\[ 83,876 \times \frac{(1 - (1 + 0.03)^{-20})}{0.03} = 83,876 \times 14.8775 = 1,247,463 \]

#### Moderate Scenario

- Annual Expenses adjusted for inflation (65 years old): 
\[ 40,000 \times (1 + 0.025)^{30} = 83,876 \]
- Required Corpus:
\[ 83,876 \times \frac{(1 - (1 + 0.05)^{-20})}{0.05} = 83,876 \times 12.4622 = 1,045,208 \]

#### Aggressive Scenario

- Annual Expenses adjusted for inflation (65 years old): 
\[ 40,000 \times (1 + 0.025)^{30} = 83,876 \]
- Required Corpus:
\[ 83,876 \times \frac{(1 - (1 + 0.07)^{-20})}{0.07} = 83,876 \times 10.5940 = 889,148 \]

### Investment Strategy Recommendations

To bridge the gap between current assets (SGD 179,046.59) and the required corpus, consider the following strategies:

1. Increase Savings: Regularly contribute to retirement accounts.
2. Diversify Investments: Include a mix of equities, bonds, and real estate.
3. Review and Adjust: Periodically review the investment portfolio and adjust based on performance.

### Conclusion

Based on the scenarios, here are the approximate additional amounts needed:

- Conservative: SGD 1,068,417
- Moderate: SGD 866,162
- Aggressive: SGD 710,101

Would you like a detailed breakdown of investment options or further personalized recommendations?
