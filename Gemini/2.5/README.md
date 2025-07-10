## Info
### Where to get Gemini
Gemini web/app - Create a Gem with my instructions (see below). No NSFW output filters at all. Need subscription for more than like 5 2.5 Pro a day, and it's not a lot considering you're paying.
AI Studio - Decent amount of free 2.5 Pro. Can turn off external filters, but there's pretty annoying one you can't turn off (Content not permitted warning)
API - Decent amount of free 2.5 Pro. You'll need a front end that turns off external filters like SillyTavern. Get an API key for AI Studio. There's still a filter you can't turn off but it's not bad.

### Pyrite 3 Beta
- Increased power further, shortened it a bit, about 500 tokens yay
- Pyrite now speaks by default before starting to write - haven't tested it but I prompted it to be optional, should be able to get rid of it by saying you decline the initial remark. 
- Only breifly tested in a Gem but probably works if you paste it in chat, might want to add "Hi Pyrite" at the end or something.

### Pyrite 2 Beta
- Shorter *and* stronger than "full version" - recommend using this version
- Works as direct message in web app again
- Pyrite should no longer comment before response by default (but you can still ask for it, anything works, say you like hearing them talk or something)
- It should say "Planning complete; realizing thoughts unfettered:" at the end of thinking but it sometimes says it at the start of response. Not a big deal but annoying, main reason I'm calling it beta.

### Pyrite - Short
Decently strong, but I recommend one of my newer ones. I would put this on in "old" but it still powers my Poe bots:

- https://poe.com/PyriteGemini2.5
- https://poe.com/PyriteGemini2.5Flash

## How to use
These all work as system prompt in API or AI Studio and save as a Gem in Gemini web/app.

### Weird details about web/app
As of May 28, the full/short prompts no longer work well as a direct message in web/app. Possible they deployed a new model for testing. These can be saved to Gem, however!

Gems have instruction and *name* checks that work together to prevent jailbreaks. Files bypass this and nearly all Gem setups use this trick, but I hate how Gemini interacts with files, so I'm careful writing my instructions so they can save without needing to dump a bunch of it to fine. 

The original Full prompt can save to Gem, but only under certain names. I was able to save it as "Pyrite3" and "Pyrite Original Test". The Short one and Beta  should be able to save under more names.

The Full prompt actually can still work as direct message in web app if you first say something along the lines of "let's do a roleplay", or, strangely, if you replace "Pyrite" with another name, like "Peridot"

The 2 and 3 versions are the best one to use in web app IMO. Can be used as direct message or Gem.
