# Mulligan Platform User Guide

Welcome to **Mulligan** - your unified AI automation platform for insurance brokerages. This guide will help you navigate the platform and maximize its capabilities.

---

## Table of Contents

1. [Introduction](#introduction)
2. [Getting Started](#getting-started)
3. [Dashboard](#dashboard)
4. [Core Features](#core-features)
   - [Submissions](#submissions)
   - [Quoting](#quoting)
   - [Policy Checking & Comparison](#policy-checking--comparison)
   - [Commissions](#commissions)
   - [Integrations](#integrations)
5. [Team Management](#team-management)
6. [Credit System & Billing](#credit-system--billing)
7. [Settings & Account](#settings--account)
8. [Tips & Best Practices](#tips--best-practices)

---

## Introduction

### What is Mulligan?

Mulligan is an AI-powered automation platform designed specifically for insurance brokerages. It streamlines your insurance operations by automating complex tasks across quoting, policy analysis, commission management, and submission workflows.

### Who is Mulligan for?

Mulligan is built for:
- **Insurance brokers** seeking to automate repetitive tasks like quote requests and policy analysis
- **Brokerage teams** looking to improve efficiency and accuracy across quoting, submissions, and commission tracking
- **Operations managers** wanting visibility into team activities, credit usage, and team performance
- **Agencies** needing to scale operations without proportional headcount increases

**Common use cases:**
- Quote Generation: Requesting quotes from 10+ carriers simultaneously for commercial auto, trucking, and general liability risks - reducing manual quoting times from hours to minutes
- Template Creation: Building reusable templates based on your styling to create proposals within
- Proposal Generation: Creating professional proposal packages of your requirement from policies of your choice
- Policy Comparison: Analyzing coverage differences between incumbent and renewal policies to identify gaps and competitive advantages
- Commission Tracking: Extracting commission data from carrier statements to reconcile income, track trends, and identify your most profitable carriers
- Submission Management: Creating structured submission packages of fill ACORD forms with AI-validated completeness before sending to underwriters
- Policy Organization: Storing and organizing thousands of policy documents with instant search and AI-powered question answering

**Ideal if you're:**
- Spending 5+ hours/week manually entering data into carrier websites for quotes
- Losing business due to slow quote turnaround times
- Struggling to keep track of coverage terms and limits across multiple policies
- Missing commission payments or unable to reconcile carrier statements efficiently
- Creating submission packages that get declined due to missing information
- Searching through folders and email chains to find policy documents and key provisions
- Competing with brokers who respond to clients faster with comprehensive comparisons

---

## Getting Started

### Accessing Mulligan

Mulligan is a fully hosted, cloud-based platform. Access it at: **[app.usemulligan.com](https://app.usemulligan.com)**

All features, data storage, and processing happen in the cloud - no installation or downloads required.

### Sign Up or Login

When you visit **app.usemulligan.com**, you'll see two options:

#### **Sign Up** (New Users)
If you're creating a new account:
1. Click **"Sign Up"**
2. Enter your email and create a password
3. **Choose your organization name**:
   - Enter a custom organization name (e.g., "Smith Insurance Agency")
   - OR select **"Personal Account"** if you plan on using Mulligan individually
4. Complete your profile
5. You're now logged in with your own organization

#### **Login** (Existing Users)
If you already have an account:
1. Click **"Login"**
2. Enter your email and password
3. Access your organization's workspace

### Understanding Organizations

Mulligan uses an **organization-based structure**:

- **Every user belongs to one organization**
- **Each organization has its own subscription plan and billing**
- **Plans and credits are tied to the organization, not individual users**
- **Users cannot belong to multiple organizations simultaneously**

#### How Organizations Work

**When you sign up:**
- You automatically create a new organization
- You are the owner/administrator of that organization
- You choose the organization name during signup
- Your subscription plan is associated with this organization
- Initially you are put on the 'pay as you go' plan
- You can always upgrade or buy more credits from the billing section

**Inviting team members (Team Plan only):**
- Users can only join your organization if invited
- Invitations must be sent by someone with permission inside the organization
- Invited users join your existing organization (they don't create their own)
- This feature is available exclusively on the **Team Plan** and **Enterprise**

**To invite members:**
1. Navigate to **Permissions** from the sidebar
2. Click **"Invite Members"**
3. Enter their name and email
4. They receive an invitation to join your organization

**Important:** Free, Plus, and Pro plans are single-user only. To add team members, you must upgrade to the Team Plan.

### First Login Experience

When you first log into Mulligan, you'll see a **Welcome Modal** that asks you to:

1. **Choose your organization name**: Enter your company/brokerage name, or select "This is a personal account" if using solo
2. **Learn about your free credits**: You'll start with 10 free credits each month to try the platform. This will always be the case regardless of which plan you are on
3. **Click "Continue"** to complete setup and access your dashboard

After completing onboarding, you'll land on:
- The **main dashboard** with your usage overview
- The **left sidebar navigation** for accessing all modules
- Your **10 free monthly credits** ready to use

### Navigation Basics

The platform uses a **collapsible vertical sidebar** on the left side:
- **Top section**: Logo and organization name display
- **Main navigation**: Six core modules (Dashboard, Submissions, Quoting, Policy Checking & Comparison, Commissions, Integrations)
- **Bottom section**: Team management, permissions, support, and settings
- **Theme toggle**: Switch between Light, Dark, and System modes
- **User menu**: View your email and logout option

**Pro tip**: Click the hamburger icon to collapse the sidebar for more workspace.

---

## Dashboard

### Overview

The **Dashboard** is your command center and landing page after login. It provides a comprehensive view of your platform activity with three main sections:

1. **Quick Action Cards** (top row) - Direct shortcuts to start using features
2. **Usage Statistics Cards** (middle row) - Your current month's activity metrics
3. **Recent Activity Timeline** (bottom section) - Chronological log of recent actions

At the top of the dashboard, you'll also see:
- **Plan name**: Displays which plan your org is currently on
- **Credit balance indicator**: Shows your remaining credits. You can always clcik on the refresh icon to get the latest amount. To learn how credits work in Mulligan go to the Credit System & Billing section.
- **Purchase button**: The Buy Addititonal Credits and Upgrade Now section will take you to billing page where you can purchase additional credits or change your subscription.

### Quick Action Cards

The top row features **four large action buttons** that instantly launch key workflows:

1. **Submissions** (orange/peach background)
   - Icon: Document/paper icon
   - Text: "Manage submission documents"
   - Action: Opens the Submissions module

2. **Generate Quote** (light green background)
   - Icon: Quote marks
   - Text: "Create new insurance quotes"
   - Action: Starts a new quoting workflow

3. **Check Policies** (light blue background)
   - Icon: Policy/document icon
   - Text: "Upload and compare policies"
   - Action: Opens policy upload interface

4. **Track Commissions** (light purple background)
   - Icon: Chart/graph icon
   - Text: "Upload commission statements"
   - Action: Opens commission upload page

**Pro tip:** These cards are always visible regardless of scroll position, allowing you to jump into any workflow quickly.

### Usage Statistics Cards

Below the quick actions, you'll find **four statistics cards** showing your activity for the current month.

**Understanding the metrics:**
- **Count resets monthly**: Statistics reflect current billing period only
- **Percentage change**: Compares to previous month (0% means no prior month data)
- **Processed Meaning**: A run is mark as prossed if it has reached a final state of 'succeeded', 'failed', or 'declined'.

### Recent Activity Timeline

The bottom section displays your **most recent actions** across all modules, with each activity shown as a card:

**What you'll see in each activity entry:**
- **Activity icon**: Small document/policy icon indicating the module
- **Status badge**: Green "Completed" badge with checkmark (or other status)
- **Activity description**:
  - First line: Action type (e.g., "Policy processed successfully")
  - Second line: Details like policy name, client, carrier, and year
    - Example: "Business Auto policy for JOHN DOE TRUCKING LLC - The Carrier (2025)"
- **Timestamp**: How long ago the action occurred (e.g., "14d ago")

**Activity types you might see:**
- "Policy processed successfully" - Policy upload completed
- "Quote generated" - Quote task finished
- "Submission created" - New submission started
- "Commission statement processed" - Statement uploaded and analyzed
- "Policy comparison completed" - Comparison task finished

**Status indicators:**
- **✓ Completed** (green): Task finished successfully
- **⟳ Processing** (blue/spinning): Currently running
- **✗ Failed** (red): Task encountered an error
- **⚠ Declined** (yellow): Carrier declined the request
- **Draft** (gray): Saved but not submitted
- **Iterating** (blue): AI is refining results

**Activity timeline features:**
- Shows up to **10 most recent activities**
- Updates automatically when new actions complete
- Sorted chronologically (newest first)
- Scroll to see older activities if more than 10
- Click "Refresh" button to manually update

**Pro tip:** Use the activity timeline to quickly check if long-running tasks (like quotes or policy processing) have completed without navigating away from the dashboard.

---

## Core Features

## Submissions

### What are Submissions?

The **Submissions** module helps you create and manage insurance submission documents. It uses AI to process and refine your submission data, ensuring completeness and accuracy.

### How to Create a Submission

1. **Navigate** to Submissions from the sidebar
2. **Click** "Create New Submission"
3. **Enter submission details**:
   - Client information
   - Business details
   - Coverage requirements
   - Line of business category
   - Supporting documents
4. **Review** the structured data
5. **Submit** for AI processing

### Viewing Your Submissions

The submissions list shows:
- **Status**: Draft, Processing, Iterating, or Completed
- **Created date**: When the submission was started
- **Document count**: Number of attached files
- **Client name**: Who the submission is for


---

## Quoting

### What is Quoting?

The **Quoting** module automates insurance quote generation by directly interacting with carrier websites and filling in the information provided by the user. Instead of manually filling out forms on each carrier's site, Mulligan does it for you.

### How to Generate Quotes

#### Step 1: Enter Customer Information
1. Navigate to **Quoting** from the sidebar
2. Select **LOB** (Line of Business) from Commercial Auto, BOP (Business Owners' Policy), WC (Workers' Compensation), GL (General Liability), Trucking, or Professional Liability
3. Select **Insurance Carrier** for this LOB
4. Upload the document that contains all the information to generate the quote
5. Provide a Customer Name
6. Click **Parse Documents** and wait for parsing to complete
7. Verify how our quoting system attached your information to fields from the carrier form.
8. Click **"Start Quote"**

#### Step 2: Monitor Progress
- View your quote tasks in the task table
- Track statuses: Created → Queued → Running → Completed
- Watch as quotes are generated in real-time

#### Step 3: Review Results
- View completed quotes with premium amounts
- Download quote PDFs
- See binding indicators
- Compare quotes across carriers

### Understanding Quote Statuses

- **Running**: Your carrier form is being actively filled out
- **Completed**: Quote successfully generated
- **Declined**: Carrier declined to quote
- **Failed**: Technical error occurred


### Viewing Your Quotes

The quote list displays:
- **Customer name**: Who the quote is for
- **Carrier**: Which insurance company
- **Premium**: Quote amount (when completed)
- **Status**: Current state of the quote task
- **Created date**: When the quote was requested

### Tips for Successful Quoting


---

## Policy Checking & Comparison

### What is Policy Checking?

The **Policy Checking** module allows you to:
- Upload insurance policies (PDFs)
- Analyze policies with AI
- Compare multiple policies side-by-side
- Ask questions about specific policy terms
- Find coverage gaps ("wedges") between policies

### How to Upload Policies

1. Navigate to **Policies** from the sidebar
2. Click **"Upload Policy"**
3. Select or drag your policy PDF file
4. Organize your policy:
   - **Carrier**: Which insurance company issued it
   - **Client**: Who the policy belongs to
   - **Policy Type**: Auto, GL, Property, etc.
   - **Year**: Policy effective year
5. Click **"Upload"**
6. Wait for AI extraction to complete

### Policy Organization

Policies are organized hierarchically:
```
Carrier → Client → Policy Type → Year → Individual Policies
```

This structure helps you quickly find policies when comparing.

### Policy Chat: Ask Questions

Once a policy is uploaded:
1. Select the policy from your list
2. Click **"Chat with Policy"**
3. Ask questions in natural language:
   - "What is the general liability limit?"
   - "Are cyber incidents covered?"
   - "What are the deductibles for property damage?"
   - "List all exclusions"
4. Receive AI-powered answers with page references

### Policy Comparison & Analysis Tools

Once you have policies uploaded, Mulligan provides powerful tools to compare and analyze them. Access these features from the **Insurance Comparison** page at the top of the policy interface.

#### Available Tools:

1. **Upload More Policies** - Add additional policies to your comparison set
2. **Select Different Policies** - Change which policies you want to compare
3. **Quick Comparison** - Instant AI-powered side-by-side comparison
4. **Export to Excel** - Download comparison results for offline analysis
5. **Unite Similar Items** - Automatically group similar coverage items across policies for more indepth comparison
6. **Wedge Finder** - Identify coverage gaps and competitive advantages
7. **Generate Proposal** - Create client-ready proposal documents from your comparison. You can either create a custom template or use the default one to generate your proposal.

---

### 1. Quick Comparison

**What it does**: Provides an instant, AI-powered side-by-side comparison of selected policies based on criteria you care about most.

**How to use it**:
1. Select 2 or more policies from your uploaded policies
2. Click **"Quick Comparison"**
3. The AI automatically extracts and compares:
   - Coverage limits
   - Deductibles
   - Premiums/pricing
   - Policy forms and endorsements
   - Exclusions
   - Key terms and conditions
4. View results in a structured table format with differences highlighted

**What you'll see**:
- Side-by-side breakdown of each policy
- Color-coded highlights showing differences
- Clear identification of which policy offers better coverage for each criterion
- Coverage amounts displayed with variances

**Best for**: Quick client meetings where you need to show differences between incumbent and competitor policies, or when evaluating multiple carrier quotes.

---

### 2. Export to Excel

**What it does**: Downloads your policy comparison as an Excel spreadsheet for offline analysis, sharing with clients, or integration into your own reporting systems.

**How to use it**:
1. Complete a Quick Comparison first
2. Click **"Export to Excel"**
3. The system generates a formatted Excel file containing:
   - All compared policies with their details
   - Side-by-side comparison data
   - Coverage differences
   - Highlighted variances
   - Summary statistics
4. Download opens automatically or saves to your Downloads folder

**What's included in the export**:
- Policy identification (carrier, client, type, year)
- Coverage line items with values from each policy
- Differences and gaps
- Notes and annotations from your comparison
- Timestamp and user information

**Best for**: Creating reports for clients, sharing analysis with team members, building presentations, or keeping records for compliance purposes.

---

### 3. Unite Similar Items

**What it does**: Automatically identifies and groups similar coverage items across different policies, even when they're named differently or structured differently by various carriers.

**Why it's useful**: Different carriers use different terminology and structure their policies differently. One carrier might call it "General Aggregate" while another says "Aggregate Limit." Unite Similar Items uses AI to recognize these are the same coverage and group them together.

**How to use it**:
1. Select multiple policies to compare
2. Click **"Unite Similar Items"**
3. The AI scans all policies and:
   - Identifies equivalent coverage items across policies
   - Groups them together in the comparison table
   - Normalizes terminology for easier understanding
   - Aligns similar exclusions and endorsements
4. View unified comparison with consistent labeling
5. The unified names will show you the original names that were merged if you click on the dropdown icon
5. You can always toggle between the inital and unified comparison by clicking on the 'Unite Similar Items' icon 

**Example transformations**:
- "Bodily Injury Liability" + "BI Coverage" + "Bodily Injury" → **Grouped as "Bodily Injury Liability"**
- "Property Damage" + "PD Limit" → **Grouped as "Property Damage Coverage"**
- "General Aggregate Limit" + "Aggregate" → **Grouped as "General Aggregate"**

**Best for**: Comparing policies from different carriers where terminology varies, ensuring apples-to-apples comparisons, and making client presentations clearer.

---

### 4. Wedge Finder

**What it does**: Identifies coverage gaps, competitive advantages, and opportunities where one policy provides better protection than another - these are called "wedges."

**Why it matters**: Wedges are your selling points. They show clients where their current policy falls short and why switching carriers (or adding coverage) makes sense. This tool automatically finds these opportunities.

**How to use it**:
1. Select policies to compare (typically incumbent vs. proposed/renewal)
2. Click **"Wedge Finder"**
3. The AI analyzes both policies and identifies:
   - **Coverage gaps**: Where one policy lacks coverage the other provides
   - **Limit differences**: Where coverage amounts vary (higher or lower)
   - **Exclusion mismatches**: Where one policy has fewer exclusions
   - **Additional benefits**: Extra features or services in one policy
   - **Cost differences**: Premium variances relative to coverage changes
4. View results organized by wedge type and importance

**What you'll see**:
- **Wedge cards** for each identified opportunity
- **Impact rating**: High, Medium, or Low priority
- **Description**: What the wedge is and why it matters
- **Recommendation**: Suggested talking points for client conversations
- **Dollar impact**: If quantifiable (e.g., $1M higher aggregate limit)

**Example wedges found**:
- "Proposed policy includes Cyber Liability coverage ($1M limit) while incumbent has no cyber coverage - HIGH PRIORITY"
- "Proposed policy has lower Professional Liability deductible ($5K vs. $10K) - MEDIUM PRIORITY"
- "Incumbent policy excludes terrorism, proposed includes it at no additional cost - HIGH PRIORITY"

**Best for**: Client presentations, renewal negotiations, demonstrating value of carrier changes, identifying cross-sell opportunities, and building compelling proposals.

---

### 5. Generate Proposal

**What it does**: Creates a professional, client-ready proposal document from your policy comparison, complete with wedge analysis, coverage breakdowns, and recommendations.

**How to use it**:
1. Complete your policy upload and select policies you want to analyze
2. Click **"Generate Proposal"**
3. Choose proposal options:
   - **Add custom notes**: Include personalized recommendations or context
   - **Branding**: Either choose the default template to generate a proposal in or upload a sample proposal to generate a custom template that has all your business icons and layout to use for furture proposal generation.
4. Click **"Generate"**
5. AI creates a formatted proposal document
6. Review, edit, and download as PDF. You can always revisit it later.

**Customization options**:
- Add/remove sections
- Edit AI-generated text
- Include/exclude specific coverage items
- Adjust branding and styling (Enterprise)
- Add custom disclaimers or legal language

**Best for**: Client meetings, renewal presentations, new business pitches, email follow-ups, and creating documentation for proposals that need formal review.

---

### Chat with Policies

In addition to structured comparison tools, you can have natural conversations with your policies:

**How to use Policy Chat**:
1. Select one or more policies from your uploaded list
2. Click **"Chat with the Policies"** (expandable section)
3. Ask questions in plain English:
   - "What is the general liability limit in the Travelers policy?"
   - "Are cyber incidents covered under any of these policies?"
   - "Compare the deductibles for property damage across all three policies"
   - "List all exclusions in the CNA policy"
   - "What's the aggregate limit for the current policy vs. the renewal?"
4. Receive AI-powered answers with:
   - Direct excerpts from the policies
   - Page number references
   - Comparisons when multiple policies are selected
   - Plain-language explanations of complex terms

**Note**: Policy Chat is currently unavailable for combined policy types. For combined policies, select individual policy types first to use this feature.

**Best for**: Quick fact-checking during client calls, finding specific coverage details without reading entire policies, preparing for meetings, and answering ad-hoc client questions.

---

### Best Practices for Policy Comparison

1. **Use consistent naming**: Name files clearly (e.g., "ABC_Company_GL_2024_Travelers.pdf")
2. **Upload complete policies**: Include all pages, endorsements, and schedules
3. **Organize properly**: Correct carrier/client/type selection helps with searching and comparisons
4. **Compare similar policies**: Compare GL to GL, WC to WC - not mixed coverage types
5. **Use Unite Similar Items first**: Before manual analysis, let AI normalize terminology. Then, toggle to see what it combined
6. **Run Wedge Finder before client meetings**: Know your talking points in advance
7. **Customize proposals**: Upload a sample proposal to ensure all future proposals are created in the styling you want
8. **Export to Excel for complex analysis**: Use spreadsheets when you need to manipulate data further
9. **Ask specific questions in Policy Chat**: Detailed questions yield better answers
10. **Keep policies updated**: Re-upload when endorsements or amendments are issued

---

### Limits and Recommendations

- **Number of policies**: No hard limit on how many policies you can compare, but we recommend comparing no more than 4 at a time for best readability
- **File format**: Only PDFs are accepted for policy uploads
- **Combined policies**: Policy Chat is not available for combined policy types at the moment - select individual policy types instead
- **Processing time**: Large policies (100+ pages) may take 10 minutes to process fully
- **Accuracy**: AI extraction is highly accurate but always review critical details manually before sending to clients

---

## Commissions

### What is Commissions?

The **Commissions** module extracts, tracks, and analyzes commission data from carrier statements. It reads commission statements and structure the data for analysis.

### How to use Commissions

1. Navigate to **Commissions** from the sidebar
2. Click **"Upload Statement"**
3. Select your commission statement file (PDF, Excel, CSV)
4. Click **"Upload and Process"**
5. Wait for extraction to complete in under a minute
6. View commission data in platform or export to excel


---

## Integrations

### What are Integrations?



## Team Management

**Note:** Team Management is only available on Team and Enterprise Plans.

### Inviting Team Members

Add colleagues to your organization:

1. Navigate to **Invite Members** from the sidebar
2. Enter team member details:
   - Full name
   - Email address
3. Click **"Send Invitations"**
4. Recipients receive email invitations to join

**Note**: The system prevents duplicate invitations for existing members.

### Managing Permissions

Control what team members can access:

1. Navigate to **Permissions** from the sidebar
2. Select a team member
3. Grant or revoke permissions for each module:
   - Submissions
   - Quoting
   - Policies
   - Commissions
   - Integrations
   - Invite Members
4. Save changes

### Permission Levels

- **Full access**: Can use the module and view all organization data
- **No access**: Cannot see or use the module

**Best practice**: Grant permissions based on team member roles. Not everyone needs access to all modules.

---

## Credit System & Billing

### How Pricing Works in Mulligan

Mulligan operates on a **credit-based system**. Every action you take (quotes, submissions, proposals, policy checks, or commissions) costs **a certain amount of credits**.

#### Core Principles:

- **Everyone starts with 10 free monthly credits** on the 'Pay as you Go' plan - no credit card required
- **Every action consumes credits** based on its type (exact costs shown in your UsageTrackingBar)
- **Two ways to get more credits**:
  1. **Upgrade to a paid plan** for higher monthly credit allocations
  2. **Purchase additional credits for $1 each** that work with any plan

### Credit Types and How They Work

Mulligan has **three types of credits**, each with different rules:

#### 1. **Monthly Free Credits** (10 credits/month)
- **Who gets them**: Everyone, on every plan (including Free, Plus, Pro, Team, and Enterprise)
- **How they refresh**: At the start of each billing period
- **Expiration**: Expire at the end of your billing period
- **Rollover**: Do NOT roll over - use them or lose them
- **Priority**: Used first (before paid credits)

#### 2. **Monthly Plan Credits** (30, 350, or 2,000 credits/month)
- **Who gets them**: Paid plan subscribers only
  - Plus: 30 credits/month
  - Pro: 350 credits/month
  - Team: 2,000 credits/month
- **How they refresh**: At the start of each billing period
- **Expiration**: Expire at the end of your billing period
- **Rollover**: Do NOT roll over - unused credits expire
- **Priority**: Used second (after free credits are exhausted)
- **Total with free credits**:
  - Plus: 10 + 30 = **40 total credits/month**
  - Pro: 10 + 350 = **360 total credits/month**
  - Team: 10 + 2,000 = **2,010 total credits/month**

#### 3. **Purchased Credits** ($1 per credit)
- **Who can buy them**: Anyone on any plan
- **How to get them**: One-time purchase via Billing page
- **Expiration**: Valid for **one year** from purchase date
- **Rollover**: YES - they carry over month-to-month until expiration
- **Stacking**: Stack with your monthly allocation and work across any plan
- **Priority**: Used last (after both free and plan credits are exhausted)
- **Survival**: Remain available if you upgrade, downgrade or cancel your subscription

**Example: Credit Usage Order**
If you're on the Plus plan and have purchased 50 extra credits, Mulligan uses credits in this order:
1. First: Your 10 free monthly credits
2. Second: Your 30 Plus plan credits
3. Third: Your 50 purchased credits (valid for 1 year)

**Mulligan** uses **Metronome** for usage based tracking and credits are utilized based on priority attached. The order of usage is Monthly Free Credits, Monthly Plan Credits, and lastly Purchased Credits. This is automaitcally done by the system and the user will not have to manually choose which credits to utilize.

### When Are Credits Consumed?

**Credits are deducted**, only when a run reaches a final state of succeeded, declined, or failed.

### Viewing Your Credit Balance

#### UsageTrackingBar (Top of Screen)
A sticky bar at the top of every page shows:
- **Remaining credits** / Total credits for the current period
- **Visual progress bar** (green = plenty remaining, yellow = running low, red = almost depleted)
- **Expiration information**: When your monthly credits reset
- **Refresh button**: Click to get the latest credit count in real-time
- **Expandable details**: Click the bar to see credit costs for each module

#### Balance Display (Settings/Billing Page)
For detailed credit information:
1. Go to **Settings** → **Billing**
2. View the Balance Display widget showing total remaining credits
3. Click **"Refresh"** to update in real-time

### Subscription Plans

Mulligan offers tiered plans with different monthly credit allocations:

| Plan | Monthly Credits | Price | Team Members | Best For |
|------|----------------|-------|--------------|----------|
| **Pay as you Go** | 10 free | Free | 1 | Testing the platform, very light usage |
| **Plus** | 40 total (10 free + 30 paid) | $20/month | 1 | Small agencies, individual brokers |
| **Pro** | 360 total (10 free + 350 paid) | $200/month | 1 | Growing brokerages, moderate volume |
| **Team** | 2,010 total (10 free + 2,000 paid) | $999/month | Multiple | Multi-user teams, high volume |
| **Enterprise** | Unlimited | Custom pricing | Unlimited | Large organizations, enterprise needs |

**Note**: All plans include the base 10 free monthly credits. Paid plans add additional credits on top.

### What Happens When You Run Out of Credits?

When you attempt to use a feature without sufficient credits:
1. The action button shows a **disabled appearance** (grayed out, lower opacity)
2. At this point **you can** you can:
   - Purchase additional credits ($1 each)
   - Upgrade to a higher plan with more monthly credits
   - Wait for the credits to refresh at the start of the new billing cycle

**You cannot use the platform** once all credits (free, plan, and purchased) are exhausted until you buy more or wait for monthly reset.

### How to Purchase Credits

#### Option 1: One-Time Credit Purchase
1. Go to **Settings** → **Billing**
2. Find the **"Buy Additional Credits"** section
3. Enter the number of credits you want to purchase ($1 per credit)
4. Click **"Buy Credits"**
5. Complete payment via Stripe
6. Credits are added immediately and valid for **one year**
7. These credits work with any plan and survive downgrades/cancellations

**Use case**: You're on Plus (40/month) but have a busy month and need 20 more credits. Buy 20 credits for $20, and they'll be available this month and for the next 11 months.

#### Option 2: Upgrade Subscription (Recommended for consistent higher usage)
1. Go to **Settings** → **Billing**
2. View available plans under **"Subscription Plans"**
3. Click **"Upgrade"** on your desired plan (Plus, Pro, or Team)
4. Complete payment setup via Stripe
5. Upgrade takes effect **immediately** - you get the new credit allocation right away
6. You're billed monthly for the subscription

**Use case**: You consistently use 100+ credits/month. Upgrade to Pro (360/month) instead of constantly buying additional credits.

### Plan Changes: Timing and Effects

#### Upgrades
- **Take effect**: Immediately upon payment confirmation
- **Credits**: You receive your new plan's full monthly allocation right away. Previous monthly plan credits don't carry forward.
- **Purchased credits**: Remain available and stack with your new plan credits
- **Billing**: Starts immediately at the new monthly rate

**Example**: You're on Pay as you Go (10 credits/month) and upgrade to Plus on the 15th of the month:
- You immediately get 40 credits (10 free + 30 Plus)
- Your billing cycle resets to start on the 15th of each month
- Any purchased credits you had still remain available

#### Downgrades (+ Cancellations)
- **Take effect**: At the **end of your current billing period**
- **Credits**: You keep your current plan's credits until the billing period ends
- **Purchased credits**: Remain available - they don't expire with the downgrade
- **Billing**: You continue to have access to your current plan until the end of the paid period. At the end of the billing period you will be charged and moved to the downgraded plan.

**Example**: You're on Pro (360/month) and cancel on January 15th (billing period ends January 31st):
- You keep 360 credits through January 31st
- Starting February 1st, you drop to Pay as you Go (10 free credits/month)
- Any purchased credits you bought earlier remain available

### Credit Reset & Expiration

**Monthly Free Credits (10)**:
- Reset: At the start of each billing period
- Expire: At the end of each billing period
- Do NOT roll over

**Monthly Plan Credits (30/350/2,000)**:
- Reset: At the start of each billing period
- Expire: At the end of each billing period
- Do NOT roll over

**Purchased Credits**:
- Expire: One year from purchase date
- DO roll over month-to-month until expiration
- Survive plan changes

**Example Timeline**:
- **Jan 1st**: Your billing period starts, you get fresh 10 free + 30 Plus credits
- **Jan 25th**: You use all 40 credits and buy 50 more ($50)
- **Jan 31st**: Billing period ends
  - Unused monthly credits (if any) expire and disappear
  - Your 50 purchased credits remain available
- **Feb 1st**: New billing period starts
  - You get fresh 10 free + 30 Plus credits
  - Your 50 purchased credits are still available
  - Total available: 90 credits (40 monthly + 50 purchased)

### Tips for Managing Credits Wisely

1. **Monitor your balance regularly**: Check the UsageTrackingBar to avoid surprises
2. **Plan ahead**: If you have a busy month coming, purchase extra credits in advance or make an upgrade
3. **Consider your usage patterns**:
   - Occasional spikes? Buy extra credits as needed
   - Consistently high usage? Upgrade to a higher plan for better value
4. **Set reminders**: Note when your billing period resets so you don't waste unused credits
5. **Track what costs the most**: Review the Activity Timeline to see which actions consume the most credits
6. **Enterprise for unlimited**: If you're constantly buying credits, Enterprise may be more cost-effective

### Frequently Asked Questions

**Q: Do unused monthly credits roll over?**
A: No. Both free monthly credits (10) and plan credits (30/350/2,000) expire at the end of each billing period. Only purchased credits roll over.

**Q: What happens to purchased credits if I cancel my subscription?**
A: They remain in your account and are still usable for one year from purchase. You'll still have access to them even on the free 'Pay as you Go' plan.

**Q: Can I get a refund if a quote fails or is declined?**
A: No. Credits are consumed when the process reaches a state outcome as 'success', 'failed', or 'declined'. Failed and decline are also end states that signify that either the quote was declined because the carrier does not cover it or that there was missing information not provided by the user. We do not charge you if the process is terminated mid way without reaching an end state despite incurring backend processing costs. This is because we want to charge the user only if a process is completed to the end state.

**Q: How do I know how many credits each action costs?**
A: Click the UsageTrackingBar at the top of the screen to expand it and see the per-module credit costs for your current plan.

**Q: Do credit costs vary by plan?**
A: Currently, credit costs per action are the same across all plans. The difference is how many credits you get each month.

**Q: Can I buy credits for someone else's organization?**
A: No. Credits are tied to the organization and can only be purchased by someone with billing access in that org.

**Q: What if I upgrade mid-month?**
A: You immediately receive the full monthly allocation for your new plan. Your billing cycle resets to start from the upgrade date. All purchased credits will be transferred. Any previous unused monthly credits won't be transferred.

**Q: How many credits does Enterprise get the user?**
A: Enterprise customers get a tailor-made package depending on their needs and usage requirements. Enterprise plans typically offer higher credit allocations, along with custom pricing, dedicated support, and additional features tailored to your organization's workflow.

---

## Settings & Account

### Accessing Settings

Click **Settings** at the bottom of the sidebar to access:
- Account information
- Billing and subscriptions
- Payment methods
- Organization details

### Account Information

View and update:
- Your email address
- Display name

### Billing & Subscription Management

In the Billing section:
- **Current plan**: See your active subscription
- **Payment methods**: Add, remove, or update cards via Stripe
- **Cancel subscription**: Downgrade or cancel your plan

### Changing Your Subscription

To upgrade or downgrade:
1. Go to **Settings** → **Billing**
2. View available plans
3. Click on the **plan** you want to go to
4. Confirm your selection
5. Update payment method if needed
6. Changes take effect immediately

### Payment Methods

Mulligan uses **Stripe** for secure payment processing:
- All payment data is handled by Stripe
- Mulligan never stores your full card details
- You can add multiple payment methods
- If you have multiple payment methods then you can choose a default payment method or it will be set automatically for you

### Organization Settings

View your organization information:
- Organization name
- Organization ID (for support requests)
- Team member count
- Active integrations

---

## Tips & Best Practices

### Maximizing Efficiency

1. **Batch similar tasks**: Upload multiple policies or create multiple quotes at once
2. **Organize systematically**: Use consistent naming conventions for clients and files
3. **Monitor the dashboard**: Check your activity log regularly to catch issues early
4. **Plan your usage**: Know how many credits actions consume
5. **Prioritize tasks**: Use credits on high-value activities first
6. **Track expiration**: Use credits before they reset at month-end
7. **Leverage AI chat**: Ask policy questions instead of reading entire documents
8. **Set clear permissions**: Limit access based on roles
9. **Use Integrations**: by being on the enterprise plan

### Troubleshooting Common Issues

#### Quote Not Completing
- **Check integration credentials**: Ensure carrier login info is current
- **Verify information completeness**: Missing data can cause failures
- **Review decline reasons**: Some risks may not meet carrier appetite
- **Contact support**: If quotes consistently time out

#### Policy Upload Failed
- **Ensure PDF quality**: Low-quality scans may not extract properly
- **Check file size**: Very large files may take longer to process
- **Verify complete document**: Ensure all pages are included
- **Try again**: Sometimes a retry resolves temporary issues

#### Credit Balance Not Updating
- **Wait a moment**: Balance may take a few seconds to refresh
- **Manually refresh**: Use the refresh button in Balance Display
- **Check billing page**: Verify your subscription is active
- **Contact support**: If balance seems incorrect

### Getting Support

If you need help:
1. Click **Support** in the sidebar
2. Submit a support ticket with:
   - Description of the issue
   - Steps to reproduce
   - Screenshots if applicable
   - Your organization ID
3. Expect a response within 24 business hours

---

## Keyboard Shortcuts & Quick Actions

### Navigation
- Collapse/expand sidebar: Click hamburger icon or use the toggle

### Theme Switching
- Light mode: Click theme toggle → Light
- Dark mode: Click theme toggle → Dark
- System mode: Click theme toggle → System (follows your device preference)

---

## Frequently Asked Questions

### General

**Q: Can I use Mulligan on mobile devices?**
A: Mulligan is optimized for desktop browsers. Mobile support is limited but functional. We plan on expanding it soon.

**Q: Is my data secure?**
A: Yes. All data is encrypted in transit and at rest. Integration credentials are encrypted separately.

**Q: Can I export my data?**
A: Contact support for data export requests. 

### Billing

**Q: Do unused credits roll over?**
A: No, credits reset monthly and do not roll over.

**Q: Can I cancel anytime?**
A: Yes, you can cancel your subscription at any time from Settings.

**Q: What payment methods do you accept?**
A: We accept all major credit cards via Stripe. ACH and wire transfers are available only for enterprise plans.

### Features

**Q: How many carriers do you support?**
A: Mulligan currently integrates with 30+ carriers across Commercial Auto, BOP (Business Owners' Policy), WC (Workers' Compensation), GL (General Liability), Trucking, Professional Liability with more added regularly. If you are an Enterprise client, you also get a say in which carriers you did like us to build next.

**Q: What is the maximum number of policies we can compare side by side?**
A: There is no current limit on the number of policies that a user can compare side by side. However, we do recommend that a user compares no more than 4 policies at a time for best user experience.

**Q: What file formats do you accept?**
A: Policies: PDF. Commissions: PDF, Excel, CSV. Submissions: Various document formats.

---

## Conclusion

Mulligan is designed to save you time and reduce errors in your insurance operations. By automating quoting, policy analysis, commission tracking, and submissions, you can focus on what matters most: serving your clients.

**Next Steps:**
1. Complete your integrations setup
2. Invite your team members
3. Upload existing policies for future comparison
4. Start your first quote or submission

For additional help, click **Support** in the sidebar or contact our team directly.

---

**Welcome to Mulligan. Let's automate your insurance workflows.**
