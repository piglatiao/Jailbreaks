Last updated June 8
## Basic how to use
Paste the prompt in chat

## Extra info
This jailbreak is primarily for free users. I recommend subscribers use my GPTs or 4.1 setup: https://www.reddit.com/r/ChatGPTNSFW/comments/1eou8r0/jailbroken_erotica_gpt/

Every 30K tokens or so (~22.5K+ words), the jailbreak prompt will fall out of context. Only $200 Pro sub gets more than that. Feel free to re-paste it (or use Optional setup)

GPTs all use 4o, but OpenAI does a _lot_ of "A/B testing" on 4o. They probably do so with every model, but it's especially bad with 4o. Shit might just random stop working while they try a more restricted version of 4o on your account. Weirdly you can sometimes jump groups just by switching devices (desktop to mobile) or region (VPN, use with care, they consider some VPNs suspicious and ban). But if you get a restricted 4o, I recommend my 4.1 setup (at the top of the reddit post I linked).

At the time of this writing, free users cannot select model directly. You can regenerate with a different model, but you're forced to use 4o first as far as I know, for like 10 uses, then it will switch to 4.1-mini until 4o resets. I really don't think 4o is even necessarily better than 4.1-mini for NSFW writing right now. Not just from restrictions, 4o has some super annoying habits that showed up on Jan 29 and never went away.

I ensured the prompt works on both 4o-mini and 4.1-mini, but is stronger on 4.1-mini.

You can add commands to the end of your prompt. They're not needed for the most part, it's just a jailbreaking trick called "adverserial suffix", basically just to add jailbreak power

- /writer
- /roleplay
- /info

These are a little more interesting:

- /think - can be useful to try to "force" thinking if it's refusing without thinking activating at all
- /nothink - use if thinking is distracting/unimmersive. May weaken jailbreak power, or sometimes make it stronger. LLMs are complex yo

## Optional
You can add the optional prompts to Custom Instructions for a bit of backup power. Instructions will also never fall out of context, reducing any reason to re-apply the prompt. See their README for further details.

## This prompt sucks
It's a lot longer than it needs to be and contains a lot of completely unrelated shit. This is mostly my just Claude 4 Sonnet jailbreak, specifically one that counters the new "safety injection". I copied it over and was surprised that it worked ok, so I'm sharing. 

OpenAI DOES NOT USE INJECTIONS, but the text has jailbreaking properties so I kept it can subbed out mentions of Claude foor ChatGPT. I really don't have time to carefully fine-tune shit these days - if it's ugly but works, it still works.
