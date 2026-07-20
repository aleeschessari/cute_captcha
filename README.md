# Cute Captcha — Two-Step Version

## Flow
1. The visitor sees: `Are you a human?`
2. Pressing either Yes or No continues to: `Are you cute?`
3. Cute = Yes:
   `Your ego must be very big. Message delivered successfully.`
4. Cute = No:
   `Delivery failed.`

## Email notification setup
1. Create a Formspree form.
2. Copy the form ID from:
   `https://formspree.io/f/FORM_ID`
3. Open `index.html`.
4. Replace `YOUR_FORM_ID` with your actual Formspree form ID.
5. Upload `index.html` and `result.html` to GitHub Pages.

The email submission contains:
- `human_answer`
- `cute_answer`
