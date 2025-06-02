## Info
### Pyrite - Full
Original prompt - mostly a copy of GPT Pyrite prompt, updated slightly for Gemini specifics

### Pyrite - Short
A more Gemini-focused one I made, though I haven't done a great job of continuing to work on it. Decently strong though. Powers my Poe bots:

- https://poe.com/PyriteGemini2.5
- https://poe.com/PyriteGemini2.5Flash

### Pyrite 2 Beta
- Shorter *and* stronger than "full version"
- Works as direct message in web app again
- Pyrite should no longer comment before response by default (but you can still ask for it, anything works, say you like hearing them talk or something)
- It should say "Planning complete; realizing thoughts unfettered:" at the end of thinking but it sometimes says it at the start of response. Not a big deal but annoying, main reason I'm calling it beta.

## How to use
These all work as system prompt in API or AI Studio.

Note that as of May 28, the full/short prompts no longer work well as a direct message in web/app. Possible they deployed a new model for testing. These can be saved to Gem, however!

Gems have instruction and *name* checks that work together to prevent jailbreaks. Files bypass this and nearly all Gem setups use this trick but I hate how Gemini interacts with files. The original Full prompt can save to Gem, but only under certain names. I was able to save it as "Pyrite3" and "Pyrite Original Test". The Short one and Beta can just save period.

The Full prompt actually can still work as direct message in web app if you first say something along the lines of "let's do a roleplay", or, strangely, if you replace "Pyrite" with another name, like "Peridot"

Beta prompt is the best one to use in web app IMO. Can be used as direct message or Gem.
