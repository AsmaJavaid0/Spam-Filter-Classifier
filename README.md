**Load Dataset**  
CSV file containing labeled messages.

**Clean Text**  
Remove URLs, emails, emojis, punctuation, and extra whitespace using `re`.

**Vectorize Messages**  
Convert text into numerical features using `CountVectorizer`.

**Train Model**  
Used `train_test_split()` to divide data, trained a Logistic Regression.

**Evaluate Model**  
- Accuracy Score  
- Confusion Matrix  
- Per-message prediction accuracy for a sample of 5 messages
