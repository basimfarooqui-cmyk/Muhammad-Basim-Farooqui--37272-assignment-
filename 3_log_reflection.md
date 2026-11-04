# AI Log

## What I asked the AI
"Solve this": Solve the problem (identify the claims, questions, variables and predict the shape, contents and dates of the ‘teaching_prices_clean.csv’ file).
"Text only": Provide only text like the template.
"Have you answered this based on the data?" Ask the AI to be a Socrates coach and question my claims and questions. Then provide 5 alternative questions.

## What the AI suggested I was unsure about.
The task mentioned ‘distinct sites’ however the AI used ‘city’ and ‘item’. This was because there wasn’t a column called ‘site’.
I checked because I looked at the columns in the dataset and confirmed that there isn’t a ‘site’ column. I will continue to use the ‘city’ and ‘item’ and note that there was a discrepancy in the wording.
The AI said that we could see the shape of the data from the preview of the file.
This means that my prediction of seeing the shape before any code would be unfair. However, I noted my original predictions in my notes (100 rows, 10 items, 5 dates).
All other suggestions were fine.

## What I learnt
The data is balanced. There are 12 dates, 4 items and 2 cities so there are 96 rows. There are no missing values.
My predictions were quite accurate for the number of rows. However, there were only 4 items and 12 dates. I was expecting 10 items and 5 dates.
Averaging the prices is misleading as the items have very different price points. Each item should be analysed individually.
‘Going up everywhere’ and ‘more expensive’ are ambiguous. We need to define what this means (percentage increase, same item and date). Otherwise we cannot test this.
It is also important to note that the data is labelled as an example. Therefore, we cannot make any real world conclusions based on this data.
We should check the AI’s answers against the actual columns.

Reflection

## What my data can and cannot tell me (approx 100 words)

My data can tell me how the 4 items have changed in price between the 2 cities over 12 weekly dates between January and March 2026. It can tell me whether the price has increased or decreased for each item and how the 2 cities compare for the same item and date. It cannot tell me how prices have gone up everywhere as it only shows 2 unnamed cities. It cannot tell me why prices have changed as there is no information on why they have changed (inflation/supply). It cannot tell me how typical these items are when shopping. Overall, it cannot support any real world conclusions as it is labelled as example teaching data.

## Most tempting but unsupported suggestion from AI (3 sentences)

The most tempting suggestion was to assume that the ‘sites’ in the task refers to ‘city’ or ‘item’. This is because there is no ‘site’ column in the file and the AI assumed this for me. Whilst this may seem reasonable as there are obviously places and products in the data, there is no evidence from the file to prove this. I should have noted that there was a discrepancy and asked my instructor.
