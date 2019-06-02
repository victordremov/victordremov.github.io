# Research on multi-armed bandit model efficiency for real-world emailing.
## Research goals
* How fast is feedback for email mailing?
  What is the difference between sending, opening and click through times
* How mailing variants should be distributed between recipients?
  We compare strategies:
  - Send defined number of emails with random variants.
    Choose best mailing variant and use it for rest recipients.
  - Send defined number of emails with random variants.
    Apply statistical n-sampled test.
    If there is significantly better mailing variant, use it for rest recipients.
    If there is not, continue to send randomly.
  - Use feedback to send better variants more ofter and worse variants less ofter. 
* Represent results as website where user can run tests and compare which is good for his business.
