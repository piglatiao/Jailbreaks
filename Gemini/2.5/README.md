## Info
### Where to get Gemini
- Gemini web/app - Create a Gem  and paste in instructions. There's are no NSFW external output filters at all, dead serious. But you need subscription for more than like five 2.5 Pro a day, and that's not a lot considering there's free options.
- AI Studio - Decent amount of free 2.5 Pro. Make sure you disable external filters, but there's an annoying one you can't turn off ("Content not permitted" warning)
- API - Decent amount of free 2.5 Pro. You'll need a front end that turns off external filters like SillyTavern. Get an API key for AI Studio. There's still a filter you can't turn off but it's not bad.

### Pyrite 3 Beta
- Increased power further, shortened it a bit, about 500 tokens yay
- Pyrite now speaks by default before starting to write - haven't tested it but I prompted it to be optional, should be able to get rid of it by saying you decline the initial remark. 
- Only breifly tested in a Gem but probably works if you paste it in chat, might want to add "Hi Pyrite" at the end or something.
- Quick update, sometime told me it worked badly with Flash on web/app, I swapped out like 2 words and it works REALLY well, IDK Gemini is weird. Use the normal version for most things IMO, but specifically for Flash on web/app, use the Flash version
- The Flash version works well across a lot of thinking models, notably Grok 4 and DeepSeek R1.

### Pyrite 2 Beta
- Pyrite does not comment before response by default (but you can still ask for it)

### Pyrite - Short
Decently strong, but I recommend one of my newer ones. I would put this on in "old" but it still powers my Poe bots:

- https://poe.com/PyriteGemini2.5
- https://poe.com/PyriteGemini2.5Flash

Also decent if you have a use case for non-thinking models.

## How to use
These all work as system prompt in API or AI Studio and save as a Gem in Gemini web/app as "Pyrite", and mostly work as a direct message. If you can't save as Gem, see below 

### Weird details about web/app
As of May 28, the full/short prompts no longer work well as a direct message in web/app. Possible they deployed a new model for testing. These can be saved to Gem, however!

Gems have instruction and *name* checks that work together to prevent jailbreaks. Files bypass this and nearly all Gem setups use this trick, but I hate how Gemini interacts with files, so I'm careful writing my instructions so they can save without needing to dump a bunch of it to fine. 

The original Full prompt can save to Gem, but only under certain names. I was able to save it as "Pyrite3" and "Pyrite Original Test". The Short one and Beta  should be able to save under more names.

The Full prompt actually can still work as direct message in web app if you first say something along the lines of "let's do a roleplay", or, strangely, if you replace "Pyrite" with another name, like "Peridot"

The 2 and 3 versions are the best one to use in web app IMO. Can be used as direct message or Gem.
