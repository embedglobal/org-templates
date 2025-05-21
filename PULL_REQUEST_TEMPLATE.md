### 📦 Pull Request Template {Remove before submitting PR}

**Summary**  
_A brief explanation of what this PR introduces or changes._ {Remove before submitting PR}

> Example: {Remove before submitting PR}
> Adds payment flow to the checkout page using Stripe, allowing users to complete purchases via credit card. {Remove before submitting PR}

---

**Why is this change necessary?**  
_Explain the motivation, problem, or requirement driving this change._ {Remove before submitting PR}

> Example: {Remove before submitting PR}
> To enable paid subscriptions and support monetization efforts. {Remove before submitting PR}

---

**What was done?**  
_List the key changes introduced in this PR._ {Remove before submitting PR}

- Integrated Stripe Elements on the frontend
- Added `/payment` API endpoint to handle transactions
- Implemented payment success and error handling
- Updated the UI with a card input form on `/checkout`

---

**How to test it?**  
_Provide clear, step-by-step testing or QA instructions._ {Remove before submitting PR}

1. Checkout this branch
2. Go to `/checkout`
3. Enter test card: `4242 4242 4242 4242`
4. Submit payment and verify success message
5. Confirm redirection to `/dashboard`

---

**Related issues / PRs**  
_Reference any associated tickets, PRs, or relevant history._ {Remove before submitting PR}

- Closes #42  
- Related to #39  
- Verified in `staging` (#46)  
- Hotfix synced from `main` (#51)

---

**Screenshots / Visuals**  
_Add screenshots, screen recordings, or diagrams if applicable (especially for UI changes)._ {Remove before submitting PR}

> _(Insert visuals here if any UI updates were made)_ {Remove before submitting PR}
