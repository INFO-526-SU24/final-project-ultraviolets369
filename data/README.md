# Data

-   **The Great American Coffee Taste Test** was conducted in 2023 by James Hoffman and Cometeer, a coffee company. This data set was pulled from github here: <https://github.com/rfordatascience/tidytuesday/blob/master/data/2024/2024-05-14/readme.md>. They sent out 4 frozen capsules of coffee which included a light, medium, and dark roast Kenyan coffee along with a Columbian coffee. Participants were asked to prepare each sample and answer a 48 question survey about their coffee preference along with demographic questions such as race, political party, age, and income. The data for this project included 4,042 response from this survey.

# Codebook for The Great American Coffee Taste Test Dataset

## Variable Names, Data Types, and Descriptions:

| Variable                     | Data Type | Description                                                                                 |
|:-----------------------------|:----------|:--------------------------------------------------------------------------------------------|
| submission_id                | character | Submission ID                                                                               |
| age                          | character | What is your age?                                                                           |
| cups                         | character | How many cups of coffee do you typically drink per day?                                     |
| where_drink                  | character | Where do you typically drink coffee?                                                        |
| brew                         | character | How do you brew coffee at home?                                                             |
| brew_other                   | character | How else do you brew coffee at home?                                                        |
| purchase                     | character | On the go, where do you typically purchase coffee?                                          |
| purchase_other               | character | Where else do you purchase coffee?                                                          |
| favorite                     | character | What is your favorite coffee drink?                                                         |
| favorite_specify             | character | Please specify what your favorite coffee drink is                                           |
| additions                    | character | Do you usually add anything to your coffee?                                                 |
| additions_other              | character | What else do you add to your coffee?                                                        |
| dairy                        | character | What kind of dairy do you add?                                                              |
| sweetener                    | character | What kind of sugar or sweetener do you add?                                                 |
| style                        | character | Before today's tasting, which of the following best described what kind of coffee you like? |
| strength                     | character | How strong do you like your coffee?                                                         |
| roast_level                  | character | What roast level of coffee do you prefer?                                                   |
| caffeine                     | character | How much caffeine do you like in your coffee?                                               |
| expertise                    | numeric   | Lastly, how would you rate your own coffee expertise?                                       |
| coffee_a_bitterness          | numeric   | Coffee A - Bitterness                                                                       |
| coffee_a_acidity             | numeric   | Coffee A - Acidity                                                                          |
| coffee_a_personal_preference | numeric   | Coffee A - Personal Preference                                                              |
| coffee_a_notes               | character | Coffee A - Notes                                                                            |
| coffee_b_bitterness          | numeric   | Coffee B - Bitterness                                                                       |
| coffee_b_acidity             | numeric   | Coffee B - Acidity                                                                          |
| coffee_b_personal_preference | numeric   | Coffee B - Personal Preference                                                              |
| coffee_b_notes               | character | Coffee B - Notes                                                                            |
| coffee_c_bitterness          | numeric   | Coffee C - Bitterness                                                                       |
| coffee_c_acidity             | numeric   | Coffee C - Acidity                                                                          |
| coffee_c_personal_preference | numeric   | Coffee C - Personal Preference                                                              |
| coffee_c_notes               | character | Coffee C - Notes                                                                            |
| coffee_d_bitterness          | numeric   | Coffee D - Bitterness                                                                       |
| coffee_d_acidity             | numeric   | Coffee D - Acidity                                                                          |
| coffee_d_personal_preference | numeric   | Coffee D - Personal Preference                                                              |
| coffee_d_notes               | character | Coffee D - Notes                                                                            |
| prefer_abc                   | character | Between Coffee A, Coffee B, and Coffee C which did you prefer?                              |
| prefer_ad                    | character | Between Coffee A and Coffee D, which did you prefer?                                        |
| prefer_overall               | character | Lastly, what was your favorite overall coffee?                                              |
| wfh                          | character | Do you work from home or in person?                                                         |
| total_spend                  | character | In total, much money do you typically spend on coffee in a month?                           |
| why_drink                    | character | Why do you drink coffee?                                                                    |
| why_drink_other              | character | Other reason for drinking coffee                                                            |
| taste                        | character | Do you like the taste of coffee?                                                            |
| know_source                  | character | Do you know where your coffee comes from?                                                   |
| most_paid                    | character | What is the most you've ever paid for a cup of coffee?                                      |
| most_willing                 | character | What is the most you'd ever be willing to pay for a cup of coffee?                          |
| value_cafe                   | character | Do you feel like you’re getting good value for your money when you buy coffee at a cafe?    |
| spent_equipment              | character | Approximately how much have you spent on coffee equipment in the past 5 years?              |
| value_equipment              | character | Do you feel like you’re getting good value for your money when you buy coffee at a cafe?    |
| gender                       | character | Gender                                                                                      |
| gender_specify               | character | Gender (please specify)                                                                     |
| education_level              | character | Education Level                                                                             |
| ethnicity_race               | character | Ethnicity/Race                                                                              |
| ethnicity_race_specify       | character | Ethnicity/Race (please specify)                                                             |
| employment_status            | character | Employment Status                                                                           |
| number_children              | character | Number of Children                                                                          |
| political_affiliation        | character | Political Affiliation                                                                       |
