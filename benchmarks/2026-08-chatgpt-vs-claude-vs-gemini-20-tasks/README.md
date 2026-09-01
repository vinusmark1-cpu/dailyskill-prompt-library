# ChatGPT vs Claude vs Gemini — 20 Everyday Tasks (Aug 2026)

Full raw data behind [this DailySkill post](https://dailyskill.ai/chatgpt-vs-claude-vs-gemini-20-everyday-tasks-tested/?utm_source=github&utm_medium=prompt_library) — every prompt, every full response from all three AIs, every individual score. Nothing trimmed, nothing cherry-picked.

## Method

The exact same prompt was sent to ChatGPT, Claude, and Gemini for each of 20 everyday tasks (write an email, plan a trip, decode a lease, build a workout plan, etc). A separate AI judge then scored the three anonymized responses — it didn't know which AI wrote which one — on 5 criteria out of 5 each (25 total): task completion, accuracy, beginner clarity, ready-to-use usability, and whether it followed the format instructions given in the prompt.

`data.json` in this folder has, for each task: the exact prompt used, all three full responses, the per-criterion score breakdown, the winner, and the judge's full reasoning (with the AI names de-anonymized after scoring).

## Results

| Task | Winner | Claude /25 | ChatGPT /25 | Gemini /25 |
|---|---|---|---|---|
| Turn Any Meeting Recording into 5-Line Minutes | **Claude** | 25 | 24 | 19 |
| Write a Polished Business Email | **Tie** | 24 | 21 | 24 |
| Pull Dates & Plans From a Group Chat | **ChatGPT** | 18 | 25 | 20 |
| Extract Every Deadline From Your Email Chain | **Tie** | 17 | 25 | 25 |
| Decode Any Contract in Plain English | **Gemini** | 23 | 24 | 25 |
| Extract Key Dates From a Long Event Invite | **ChatGPT** | 23 | 25 | 22 |
| Plan a Full Trip Itinerary | **ChatGPT** | 23 | 24 | 22 |
| Plan a 3-Day Road Trip | **Claude** | 25 | 22 | 23 |
| Smart Packing List | **Tie** | 25 | 22 | 25 |
| 1-Week Workout Plan | **Claude** | 25 | 23 | 21 |
| 3 Recipes From Ingredients You Already Have | **ChatGPT** | 21 | 25 | 23 |
| Compare 3 Apartment Listings | **Claude** | 25 | 24 | 22 |
| Compare 3 Books' Core Ideas | **ChatGPT** | 22 | 25 | 24 |
| 10 Personalized Gift Ideas by Budget | **Tie** | 24 | 24 | 22 |
| AI Interview Prep | **ChatGPT** | 19 | 25 | 23 |
| Resume Summary That Gets Noticed | **ChatGPT** | 23 | 25 | 20 |
| Catch Up on Any Group Chat in 5 Lines | **ChatGPT** | 23 | 25 | 23 |
| Understand Any Song's Lyrics Instantly | **Gemini** | 18 | 23 | 25 |
| Summarize Any Article Into a Tweet | **Gemini** | 19 | 24 | 25 |
| Deep Think Mode | **Claude** | 24 | 22 | 23 |

**Totals:** ChatGPT won 8, Claude won 5, Gemini won 3, 4 tied. Average score: ChatGPT 23.9, Gemini 22.8, Claude 22.3.

## Honest limitations

- **Sample size is 20.** Enough to see real patterns, not enough to crown a permanent champion — all three models update constantly.
- **The judge is also an AI** (Claude, scoring anonymized responses it didn't know were its own). Scores were spot-checked by hand and specific factual claims (dates, character counts, price math) were independently verified rather than taking the judge's word for it.
- **One prompt per task, one attempt per model.** Regenerating any answer could change the result — this is a snapshot, not a guarantee.
- **This will go stale.** We're planning to re-run this as a living benchmark. If a model update flips a result, we'll say so.

## Files

- `data.json` — full dataset (prompt, all 3 responses, scores, judge reasoning) per task, keyed by day number matching the site's daily-challenge numbering.
