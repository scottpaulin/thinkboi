---
name: Draft Post
description: Transform clarified musings into well-structured posts for LinkedIn or Twitter using proven formats and hooks
---

# Draft Post

This skill transforms clarified musings into posts formatted for LinkedIn or Twitter.

## Musing Status Lifecycle

Musings have these statuses:

1. **Raw**: Unprocessed, as captured from voice notes
2. **Clarified**: Worked through with follow-up questions, ready for drafting

Posts (not musings) have these statuses:

1. **Ready to Post**: Draft complete, waiting to publish
2. **Posted (date)**: Published to the platform

A clarified musing can be used in multiple posts. Track usage with the "Used In Posts" field on the musing entry.

Only draft musings with status "Clarified". Skip "Raw" musings (needs clarification first).

---

## Finding Content to Draft

Search for musings ready to become posts:

1. Look for musings with status "Clarified" in theme sub-pages
2. Review the clarification notes for core message, audience, and examples
3. Note any existing posts in the "Used In Posts" field - musings can be reused, but check for overlap
4. Consider combining related clarified musings if they strengthen each other
5. Let the user choose which musing(s) to work with
6. Ask the user which platform they want to draft for: LinkedIn or Twitter

---

## LinkedIn Posts

### Structure

1. **Hook (First 1-3 lines)**: The first 150 characters appear before "See more." Create curiosity, tension, or recognition.
2. **Context (2-4 lines)**: Explain why this matters or what prompted the thought.
3. **Body (5-10 lines)**: Deliver the insight, story, or framework. Use short paragraphs and line breaks.
4. **Call-to-Conversation (1-2 lines)**: End with a question that invites discussion.

### Formatting

- Short paragraphs (1-2 sentences)
- Line breaks for whitespace
- Bullets or numbers for lists
- Aim for 1,000-1,500 characters
- Under 300 characters for quick insights
- No hashtags
- No dashes or em-dashes. Use periods and shorter sentences instead.

---

## Twitter Posts

Prefer single tweets over threads. Single tweets are easier to consume and share.

### Single Tweet (Preferred)

Best for punchy insights, observations, or questions. Most musings should become single tweets.

- Maximum 280 characters
- Ideal length: 100-250 characters
- One clear idea per tweet
- 1-2 hashtags maximum, or none

### Thread (Optional)

Only use threads when the idea truly requires multiple tweets to convey. Most ideas should be distilled into a single tweet.

**Thread Structure:**
1. **Hook Tweet**: The first tweet must grab attention and promise value. This determines if people read the rest.
2. **Body Tweets**: 5-10 tweets is the sweet spot (7 is ideal). One idea per tweet. Each tweet should stand alone but flow to the next.
3. **Closing Tweet**: Summarize the takeaway or ask a question. Place 2-3 hashtags here, not throughout the thread.

**Thread Formatting:**
- Short, punchy sentences
- Clear line breaks within tweets
- Add a visual (image) every 3-4 tweets to increase completion rates
- Number your tweets (1/, 2/, etc.) or use a consistent marker

### Twitter Hook Types

- **Bold claim**: Start with a strong opinion or counterintuitive statement
- **Promise of value**: "Here's how I..." or "X things that will help you..."
- **Story opener**: "Last week something happened that changed how I think about..."
- **Pattern/observation**: "I've noticed that the best [X] all do this one thing..."

---

## Tone Guidelines

Keep posts constructive and professional. Share perspectives without tearing others down.

- Never criticize specific companies or individuals by name
- Focus on ideas, patterns, and insights rather than calling out bad actors
- Frame contrarian views as alternative perspectives, not attacks on opposing views
- If referencing an industry problem, focus on the solution or lesson rather than blame
- Match the platform vibe: LinkedIn is collegial and professional; Twitter can be direct but still respectful

Objectivity is fine. Critique of ideas is fine. Personal attacks are not.

---

## Writing Level

Write all posts in fifth-grade English. This ensures content is accessible and easy to read.

- Use simple, everyday words instead of jargon or complex vocabulary
- Keep sentences short and direct
- Prefer active voice over passive voice
- Explain concepts in plain language
- If a simpler word works, use it
- Aim for a Flesch-Kincaid grade level of 5 or below

---

## Post Styles (Both Platforms)

### Personal Story
Share a journey, lesson from failure, or moment of insight.
- Start with a surprising or relatable first line
- Structure: What happened, what you learned, what changed

### List Format
Organize information into a numbered list.
- Put the number in the hook
- Keep each point concise

### Insight/Analysis
Share your perspective on a trend or pattern.
- Interpret, do not just report
- Add your unique angle

### Contrarian Take
Challenge a widely accepted belief.
- Lead with the counterintuitive claim
- Back it up with logic or experience

---

## Hook Types (Both Platforms)

- **Provocative statement**: Something surprising that makes people want to read more
- **Cliffhanger**: Tease an answer or insight
- **Personal revelation**: A turning point or challenge from your experience
- **Pattern observation**: "I noticed X happening repeatedly. Here is what it means."
- **Counterintuitive claim**: "Everyone thinks X. They are wrong."
- **Direct value**: "Here is how to do X"

---

## Combining Multiple Musings

When related clarified musings can strengthen each other:

1. Identify the common thread or theme
2. Determine which musing provides the core insight
3. Use others as supporting examples or extensions
4. Maintain a single clear message

---

## Instructions

1. Use Notion MCP to find clarified musings
2. Present options and let user select one or more related musings
3. Ask which platform: LinkedIn or Twitter (default to single tweet for Twitter)
4. Review clarification notes for core message and audience
5. Suggest a post style and hook approach
6. Draft the post following the platform-specific structure
7. Present the draft for feedback
8. Refine until the user is satisfied
9. Store the final draft in the musing entry
10. Update status to "Ready to Post"

---

## Storage

Posts are stored as sub-pages under `Musings/Posts/`. Each post page represents one core insight and can have drafts for multiple platforms.

### Post Page Structure

```
## [Post Title]

**Source Musings:** 
- [Link to musing 1]
- [Link to musing 2 if combined]

**Core Message:** [One sentence summary of the insight]

---

### LinkedIn
**Status:** Not Drafted / Ready to Post / Posted (date)
**Draft:**
[Full LinkedIn post]

**Engagement Notes:** (add after posting)

---

### Twitter
**Status:** Not Drafted / Ready to Post / Posted (date)
**Draft:**
[Single tweet or thread]

**Engagement Notes:** (add after posting)
```

### Creating a New Post

1. Create a sub-page under `Musings/Posts/` with the post title
2. Link to source musing(s)
3. Add the core message
4. Add the platform section with the draft
5. Set status to "Ready to Post"
6. Update the source musing entry: add the post link to "Used In Posts" field (do not change musing status - it stays "Clarified" so it can be reused)

### After Posting

Update the platform section:
- Change status to "Posted (date)"
- Add engagement notes (reactions, comments, insights)

This history becomes reference material for future posts.
