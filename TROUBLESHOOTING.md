# Troubleshooting & Common Issues

### 1. I clicked the repo link and received a GitHub "404 Page Not Found"
GitHub hides private repositories behind a standard `404` to avoid leaking repository existence. This happens for one of three reasons:
* **The Invite is Pending:** You must navigate to `https://github.com/CodifiedLabs/spec-to-code-rules-pro/invitations` and manually click **Accept**.
* **Account Mismatch:** You completed checkout using a personal or corporate email tied to a different GitHub handle than the one currently logged in on your browser. Log out of GitHub and log back in with the handle authorized during Dodo checkout.
* **Email Verification:** If your GitHub account has an unverified primary email, GitHub rejects collaborator grants automatically.

### 2. Dodo Payments says "Entitlement Delivered", but no email arrived

Check your spam/promotions tab for an email from support@dodopayments.com or notifications@github.com.

If you closed the checkout window before clicking the OAuth grant button, open your original Dodo payment receipt and click Manage Order / Access Product to re-trigger the OAuth screen.

### 3. The AI editor is ignoring the rules during generation

**Context Overload:** Do not paste every markdown rule file into a single prompt. Use modular references (e.g., Cursor's `.mdc` system or Windsurf rules) so the model only pulls relevant rules for specific file extensions.

**Model Overrides:** Older model checkpoints (e.g., GPT-3.5 or legacy Claude 3 Sonnet) struggle with strict negative constraints. Ensure you are using Claude 3.5 Sonnet, GPT-4o, or equivalent reasoning checkpoints.

### 4. Need to transfer access to a work GitHub handle?

If you purchased with a personal card and need your company handle (`@work-handle`) added to the repository:

1. Forward your Dodo purchase receipt to codifiedlabs@gmail.com.

2. Provide your old GitHub handle and the target GitHub handle.

3. We will rotate the seat manually within 12 hours.
