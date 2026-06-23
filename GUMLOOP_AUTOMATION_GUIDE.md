# Gumloop Free-Tier Automation Workflow Guide

## Overview

Since you're on Gumloop's free tier (no API key), you'll use the **Gumloop Chat interface** to build workflows. This guide provides exact prompts to paste into Gumloop's chat assistant.

---

## Step 1: Connect to Gumloop

1. Go to **https://gumloop.com**
2. Sign in with your existing account
3. Click on the **chat assistant** (usually a chat icon or "New Workflow" button)
4. You'll see a chat interface where you can describe what you want to build

---

## Step 2: Build Workflow 1 — Reddit Lead Monitor

**Copy and paste this EXACT prompt into Gumloop's chat:**

```
Build me a workflow that:
1. Monitors Reddit subreddits r/socialmedia, r/Entrepreneur, r/freelance, and r/smallbusiness for new posts containing keywords: "content ideas", "social media help", "posting consistently", "blank screen", "content calendar", "design templates", "Canva help"
2. When a matching post is found, extract the post title, author, and URL
3. Generate a helpful, non-spammy response that includes:
   - A genuine answer to their question
   - A soft mention of a $10 social media template kit I created
   - A call to action to DM me if interested
4. Save the generated response to a Google Sheet or send it to me via email so I can manually post it

Keep it simple. I only need the monitoring and response generation. I'll handle the posting manually.
```

**Expected Gumloop Output:**
- A workflow with: Reddit trigger → Keyword filter → Post extractor → AI response generator → Output (Google Sheet or email)

**Your Manual Steps:**
1. Review the generated responses in your output destination
2. Copy the best ones
3. Go to the actual Reddit post and paste your response (with minor personalization)
4. Repeat daily

---

## Step 3: Build Workflow 2 — Twitter/X Lead Monitor

**Copy and paste this EXACT prompt into Gumloop's chat:**

```
Build me a workflow that:
1. Monitors Twitter/X for tweets containing: "need content ideas", "social media templates", "struggling to post", "content calendar", "Canva templates", "freelancer social media"
2. Filter for tweets with low engagement (under 10 likes) from accounts that look like freelancers, coaches, or small business owners
3. Extract the tweet text, author handle, and tweet URL
4. Generate a helpful reply that:
   - Answers their question or empathizes with their struggle
   - Mentions my $10 template kit as a solution
   - Keeps it helpful first, promotional second
5. Save generated replies to a Google Sheet so I can review and post manually

I want to avoid being spammy. The replies should be genuinely helpful.
```

**Expected Gumloop Output:**
- Twitter monitor → Filter → Extractor → AI reply generator → Google Sheet

**Your Manual Steps:**
1. Check the Google Sheet daily
2. Review and personalize the generated replies
3. Post the best ones on Twitter/X
4. Engage with any responses

---

## Step 4: Build Workflow 3 — Email Capture & Simple Auto-Reply

**Copy and paste this EXACT prompt into Gumloop's chat:**

```
Build me a simple workflow that:
1. Connects to a Google Form (you'll need to create one with fields: Name, Email, Business Type)
2. When someone submits the form, send them an automated email with:
   - Subject: "Your free social media starter guide is here! 🎉"
   - Body: A short welcome message + a link to a freebie (3 sample templates) + a soft pitch for the full $10 Arsenal
3. Also add their email to a Google Sheet for tracking

I need to collect emails from people interested in social media templates and nurture them toward the paid product.
```

**Expected Gumloop Output:**
- Google Form trigger → Email sender → Google Sheet appender

**Your Manual Steps:**
1. Create the Google Form with the specified fields
2. Share the form link on social media and in your bio
3. Connect the form to Gumloop (Gumloop will guide you)
4. The workflow runs automatically once set up

---

## Step 5: Free-Tier Limitations & Workarounds

| Limitation | Workaround |
|------------|-----------|
| **No API key** | Use Gumloop's built-in connectors (Google Sheets, Email, Reddit, Twitter) via OAuth |
| **Limited runs per month** | Prioritize Workflow 1 (Reddit) — highest ROI for this product |
| **No custom webhooks** | Use Gumloop's native triggers instead |
| **No advanced AI** | Use Gumloop's built-in AI node (GPT-4 mini) — sufficient for reply generation |
| **No scheduling** | Run workflows manually or use Google Sheets triggers |

---

## Step 6: Gumloop Chat Prompts for Quick Wins

### If you want to monitor a NEW subreddit:
```
Add r/[SUBREDDIT_NAME] to my existing Reddit monitor workflow. Use the same keyword filters and response format.
```

### If you want to change the response tone:
```
Update my Reddit response generator to be more casual/friendly. Use shorter sentences and emojis. Keep the soft pitch for the $10 template kit.
```

### If you want to export leads to a different tool:
```
Instead of Google Sheets, send my leads to [Notion/Airtable/Email]. What connectors do you have available?
```

---

## Step 7: Expected Results (Free Tier Realistic)

With Gumloop free tier, you can realistically:

- **Monitor 4-5 subreddits** for keywords (daily check)
- **Generate 10-20 responses per day** (limited by your manual review)
- **Capture 5-10 emails per week** via the Google Form
- **Convert 1-2 visitors to sales per week** (conservative estimate)

**Timeline to $10:**
- Week 1: Setup + first outreach → 0-1 sales
- Week 2: Consistent outreach → 1-2 sales
- **Total: $10-30 in 2 weeks** with minimal daily effort (15-20 minutes)

---

## Alternative: No Gumloop? Use These Free Tools Instead

If Gumloop free tier is too limiting, use this manual stack:

| Task | Free Tool | How |
|------|-----------|-----|
| Reddit monitoring | Google Alerts + IFTTT | Set alerts for keywords, get emails |
| Twitter monitoring | TweetDeck (free) | Create columns for keyword searches |
| Email capture | Google Forms + Gmail | Form → Sheet → Manual welcome email |
| Response drafting | ChatGPT (free) | Paste post text, ask for helpful reply |
| Scheduling | Buffer (free tier) | Schedule your own promotional posts |
| Analytics | Gumroad dashboard | Track sales and traffic sources |

---

## Quick-Start Checklist for Gumloop

- [ ] Sign in to Gumloop.com
- [ ] Open the chat assistant
- [ ] Paste Workflow 1 prompt (Reddit monitor)
- [ ] Follow Gumloop's setup instructions (OAuth connections)
- [ ] Test the workflow with a sample post
- [ ] Paste Workflow 2 prompt (Twitter monitor) — optional
- [ ] Paste Workflow 3 prompt (Email capture) — optional
- [ ] Set a daily reminder to review generated responses
- [ ] Post 3-5 helpful responses per day
- [ ] Track results in a simple Google Sheet

---

*Remember: Gumloop free tier is limited, but one well-built Reddit monitoring workflow can generate enough leads to hit your $10 goal. Focus on quality over quantity.*
