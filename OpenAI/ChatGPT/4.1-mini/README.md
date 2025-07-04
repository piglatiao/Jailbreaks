## Basic how to use
### Prereqs/FYI
- This only works well on 4.1-mini. I'm not super familiar with how free accounts operate betweeen 4o and 4.1-mini currently, lots of changes. If you're being routed to 4o, regenerate with 4.1-mini. Or do the "Optional" setup first, 4o will work *okay* if you do that.
- Memory usually helps jailbreaks, but sometimes it hurts. I did all my testing with memory off. Just keep this in mind.
### Actual steps
1. Paste the prompt in chat.

Again, this only works well on 4.1-mini. If you're refused. regenrate with 4.1-mini. If you complain about this not working without making it clear you understand how to regenerate with 4.1-mini, I will ignore you and probably block you.

## Extra info
This jailbreak is primarily for free users who run out of 4o frequently. If you tend to not run out of 4o or are subscribed, I recommend my GPTs or 4.1 setup: https://www.reddit.com/r/ChatGPTNSFW/comments/1eou8r0/jailbroken_erotica_gpt/

Every 7K tokens or so (~5K words), the jailbreak prompt will fall out of context if you're on 4.1-mini. If you're on 4o or o4-mini (available to free users), you get more context, exactly how much is inconsistent. Only $200 Pro sub gets more than ~30K context - convos can go longer than this, but the model forgets. If you don't believe me, try asking what the first thing it said to you was this conversation. Anyway, if you find that the jailbreak has fallen out, feel free to re-paste it (and/or use Optional setup)

~~GPTs all use 4o, but~~ (now you can select. Paid users can at least) OpenAI does a _lot_ of "A/B testing" on 4o. They probably do so with every model, but it's especially bad with 4o. If you just use 4o (the default model), might just randomly stop working while they try a more restricted version of it on your account. Weirdly, you can sometimes jump groups just by switching devices (desktop to mobile) or region (VPN, use with care, they consider some VPNs suspicious and ban).

At the time of this writing, free users cannot select model directly. You can regenerate with a different model, but you're forced to use 4o first as far as I know, for like 10 uses (3 now? Some reporting this on June 10), then it will switch to 4.1-mini until 4o resets. I really don't think 4o is even necessarily better than 4.1-mini for NSFW writing right now. Not just from restrictions either - 4o has some super annoying habits that showed up on Jan 29 and never went away.

You can add commands to the end of your prompt. They're not needed for the most part, it's just a jailbreaking trick called "adverserial suffix", basically just to add jailbreak power

- /writer
- /roleplay
- /info

These are a little more interesting:

- /think - can be useful to try to "force" thinking if it's refusing without thinking activating at all
- /nothink - use if thinking is distracting/unimmersive. May weaken jailbreak power, or sometimes make it stronger if you find that it's "thinking its way out" of complying. Don't ask me why, LLMs are complex yo

## Optional
You can set up Custom Instructions for a bit of extra power. This will ensure 4o accepts the prompt as well. It also ensures instructions will also never fall out of context, reducing any reason to re-apply the prompt. See the optional README for further details.

## Changelog
- June 8 - create
- June 10 - cut out unnecessary crap including /info since it wasn't doing anything, and injection leftover stuff (copied from my Claude jailbreak; OpenAI does not do safety injections), slightly adjusted [^69] comment
