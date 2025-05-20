### 📦 Pull Request Template

**Summary**  
_A brief explanation of what this PR introduces or changes._

> Example:  
> Adds payment flow to the checkout page using Stripe, allowing users to complete purchases via credit card.

---

**Why is this change necessary?**  
_Explain the motivation, problem, or requirement driving this change._

> Example:  
> To enable paid subscriptions and support monetization efforts.

---

**What was done?**  
_List the key changes introduced in this PR._

- Integrated Stripe Elements on the frontend
- Added `/payment` API endpoint to handle transactions
- Implemented payment success and error handling
- Updated the UI with a card input form on `/checkout`

---

**How to test it?**  
_Provide clear, step-by-step testing or QA instructions._

1. Checkout this branch
2. Go to `/checkout`
3. Enter test card: `4242 4242 4242 4242`
4. Submit payment and verify success message
5. Confirm redirection to `/dashboard`

---

**Related issues / PRs**  
_Reference any associated tickets, PRs, or relevant history._

- Closes #42  
- Related to #39  
- Verified in `staging` (#46)  
- Hotfix synced from `main` (#51)

---

**Screenshots / Visuals**  
_Add screenshots, screen recordings, or diagrams if applicable (especially for UI changes)._

> _(Insert visuals here if any UI updates were made)_
