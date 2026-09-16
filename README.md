# Getting Started

Codified Labs is an AI native workspace for building, evaluating, and deploying product requirements using AI coding agents such as Cursor, Claude Code, Copilot, or any other tools.

Central onboarding hub and setup instructions for **Spec-to-Code Rules Pro** rules and engineering workflows.

### ⚡ Quick Access (Purchased Customers)
If you completed checkout through Dodo Payments, your access grant has been provisioned. Complete these two steps to enter the private vault:

#### 1. Accept Your GitHub Invitation
GitHub collaborator invites do not auto-accept. If you missed the notification email, click below while logged into your GitHub account:

👉 [Accept Invitation](https://github.com/CodifiedLabs/spec-to-code-rules-pro/invitations) to Spec-to-Code Rules Pro

#### 2. Enter the Private Repository
Once accepted, pull the repository or browse the rule manifests directly:

👉 CodifiedLabs/spec-to-code-rules-pro

Bash
git clone [https://github.com/CodifiedLabs/spec-to-code-rules-pro.git](https://github.com/CodifiedLabs/spec-to-code-rules-pro.git)

Seeing a 404 error? Read TROUBLESHOOTING.md. GitHub shows a 404 instead of a 403 if you are logged into the wrong account or have not clicked the invitation link yet.

### 🛠️ Supported Editors & Placement

Spec-to-Code rules are modular Markdown specifications structured to fit current AI IDE context windows without hallucination drift.

Tool / Environment | Recommended Rule Placement | Primary Use Case: Cursor.cursor/rules/*.mdc or root .cursorrules | Real-time code generation, refactoring, and agent indexing; Windsurf (Codeium).windsurfrules (root)Cascade agent execution and workflow constraints; GitHub Copilot.github/copilot-instructions.md | Workspace context and architectural guardrails; Claude Projects | Project Knowledge (attach .md files)Architectural specs, PR reviews, and vibe-to-spec drafting

### 🚀 60-Second Setup: Cursor Example

#### 1. Navigate to your target project root:

Bash
cd path/to/your-project
mkdir -p .cursor/rules

#### 2. Copy the foundational rules from your cloned spec-to-code-rules-pro directory:

Bash
cp path/to/spec-to-code-rules-pro/core/* .cursor/rules/

#### 3. Verify Cursor detects the rules by typing @ in the Cursor Chat; you should see your rule files indexed in the context picker.

For modular configs and sample setups, inspect templates/.cursorrules.example.

### 🔒 Enterprise & Team Licensing

License Scope: Each $199 license permits deployment across your immediate engineering squad and personal workstations.

Redistribution: Public mirroring, repackaging, or re-licensing of files within spec-to-code-rules-pro is strictly prohibited.

Updates: Your purchase grants perpetual access to updates, model adjustments, and framework extensions pushed directly to the main branch of spec-to-code-rules-pro.

### 🛟 Support & Access Resolution

If your invitation failed to dispatch, your company email does not match your GitHub handle, or you hit an entitlement error:

If you need to transfer the repository seat to a different technical lead, email us with your receipt number and the target GitHub handle:

Email: codifiedlabs@gmail.com

Subject: [Access Issue / Seat Transfer]

SLA: Responses within 12 business hours. Manual collaborator invites dispatched same-day.
