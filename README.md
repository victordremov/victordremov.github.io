<body>
  <header>
    <h1>
      Research on multi-armed bandit model efficiency for real-world emailing.
    </h1>
  </header>
  <h2>
    Research goals:
  </h2>
  <ul>
    <li><emph>How fast is feedback for email mailing?</emph> What is the difference between sending, opening and click through times</li>
    <li>
      How mailing variants should be distributed between recipients? We compare strategies:
      <ul>
        <li>Send defined number of emails with random variants.
        Choose best mailing variant and use it for rest recipients.</li>
        <li>Send defined number of emails with random variants.
        Apply statistical n-sampled test.
        If there is significantly better mailing variant, use it for rest recipients.
        If there is not, continue to send randomly.</li>
        <li>Use feedback to send better variants more ofter and worse variants less ofter.</li>
        </ul>
      </li>
   <li>Represent results as website where user can run tests and compare which is good for his business.</li>
 </ul>
</body>
