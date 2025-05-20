# Example PR Description
Update the template and include sections where applicable.

### Summary
<!-- Explain what this PR does in a few sentences -->
This PR adds the payment flow to the checkout page using Stripe. Users can now enter card details and complete a purchase.

### Why is this change necessary?
<!-- State the purpose or problem this PR addresses -->
We need a working payment flow to support subscriptions and monetization.

### What was done?
<!-- Bullet point list of major changes made -->
- Integrated Stripe Elements
- Created `/payment` API endpoint
- Handled payment success/failure flows
- Updated frontend UI with payment form

### How to test?
<!-- Step-by-step instructions for QA or self-test -->
1. Checkout this branch
2. Navigate to `/checkout`
3. Enter test card: `4242 4242 4242 4242`
4. Confirm success message and redirect to `/dashboard`

### Related issues
<!-- Link any related issues or PRs -->
Closes #42  
Related to #39
Verified in `staging` #46
Hotfix sync with `main` #51

### Screenshots
<!-- Include UI screenshots, diagrams, or GIFs if applicable -->
Include before/after UI screenshots or GIFs if the PR changes the frontend.
