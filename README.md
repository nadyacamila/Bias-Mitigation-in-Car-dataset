# Bias-Mitigation-in-Car-dataset

This project is created suring The IT Girls Bootcamp with topic Data Science, Storytelling, and Ethics. The bootcamp conducted within 2 days. We practicing how to mitigate biases in a dummy car company dataset which tasked with conducting car crash tests to see whether their newest model is safe enough to enter the market. They have a cutoff of 4 out of 10 for the car model's injury risk rating, which is calculated from 0 to 10. Anything above a 4 will require further testing to ensure the safety of future users. The initial average of injury risk rating was 2.63%.
# Actions
<img width="1828" height="743" alt="image" src="https://github.com/user-attachments/assets/1eaad6da-dd98-4c49-9ab4-52f4e7e7fb2b" />
Through bar chart we can see the biases shows in sub-group distribution of gender. Through box plots we can see the existance of oultiers. Therefore, before handling the biases, these are the actions conducted:
- 2.0% of missing values considered as small amount was removed
- Outliers with value of less than 0 was removed which doesn't indicate injury risk rating measurement

# Bias Mitigation
<img width="1207" height="353" alt="image" src="https://github.com/user-attachments/assets/e25ad879-d55c-4646-9f6f-8d73393dfa01" />
<img width="1226" height="851" alt="image" src="https://github.com/user-attachments/assets/7757020c-8bbf-48d1-b02f-5e63a71c6327" />
Based on minimum amount both in female and male group, 85 was chosen to overcome the gender bias. The new result was 4.81%.

# Recommendation
Based on the latest results, which provide a more accurate injury risk rating, it is advisable to re-assess the car to ensure its safety.

Link to full demonstration available in sorce code file.

