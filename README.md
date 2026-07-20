# Cute Captcha — Math Version

## Flow
1. Three math questions:
   - Addition
   - Subtraction
   - Multiplication
2. `Are you a human?`
   - Either answer continues.
3. `Are you cute?`
   - Yes: `Your ego must be very big. Message delivered successfully.`
   - No: `Delivery failed.`

## Formspree setup
1. Create or open your Formspree form.
2. Copy the ID from:
   `https://formspree.io/f/FORM_ID`
3. Open `index.html`.
4. Replace `YOUR_FORM_ID` with your actual Formspree form ID.
5. Upload `index.html` and `result.html` to the root of your GitHub repository.

The email submission contains:
- `math_score`
- `human_answer`
- `cute_answer`
