# Speaker notes

Practice out loud. Slides are the cues. Do not read the slides.

Open index.html in a browser. Right arrow, space, or page down. Left arrow goes back. A URL hash like #7 jumps to that slide.

## 0:00 Title
I'm Tibor. Until recently I worked at Cursor, as a community developer and before that in technical support. I still work on human-agent collaboration, and I run Grok Bot as a staff, not as one long chat.

## Failure and four parts
The failure mode is one bot that does travel, mail, hardware, the books, and the reminders. It forgets which hat it is wearing, and you spend the day correcting it. The fix is small. Each bot has one job. The name is the job. A routine keeps the job running when you are not in the chat. A template lets someone else start from a working bot instead of a blank one.

## Naming
I name a bot from the first two letters of the job, then turn those letters into a person. Travel is Troy. Hardware is Hal. Accountant is Ace. Mail is Max. Signal is Sia. Ambassadors is Amber. Time sheets is Tim. House is Holly. Bot design is Bodhi. BitUnlimited is Bix. If the two letters do not make a clean name, I do not force one. The point of the name is that I can see the sidebar and know the job without opening the chat. Troy does not get a second job because he was helpful on Tuesday. A second job gets a second bot.

## Coordinator
I used to split this into a chief of staff, Costa, and the specialists. Costa coordinated. She did not book the trip, configure the hardware, or do the books. Troy owned travel. Hal owned hardware. Ace owned the CodeMango and Xolo accounting. Costa did not redo their work, and she did not ping me if one of them had already told me. That split is the lesson. Two people doing the same job is worse than one generalist. I am folding the coordination into the primary bot and removing Costa, because I do not want two coordinators. The specialists stay. They still own the work.

## Comms
Max is the only bot who sends email. Anyone else can draft. They hand the finished mail to Max, and Max sends it once, after I have said yes. They do not send it themselves, and they do not ask me a second time. Sia owns Signal. Same idea. One inbox, one owner. If every bot can send, you get three replies to the same person, in your name, and you cannot take them back.

## Routines
A routine is a saved prompt on a clock or an event. It belongs to the bot whose job it is. I use a morning pass and a weekly pass. I am not going to read you the prompts. The useful part is where they live. The morning pass is not a note in a general chat I have to remember to open. It fires on the bot that owns that check, including while I am away. If the check finds nothing, it stays quiet. A routine that messages you "nothing changed" every morning is how you learn to ignore the bot.

## Template
Show the link. This is the public example, also on tibor.io/projects. It is a Space Opera RPG game master. I made it while building Prendaram. It is not affiliated with any book, film, or series. Adding it does not put anyone in my campaign, and it does not show them my chats. They get their own bot. You pick a story you already like. You tell it the scene, the universe, or the environment. You say which characters get their own bots, and which side characters the narrator keeps. Then you ask it to make a room. That room can be just you and the narrator, or you, the narrator, and the other characters. A station, a ship, or a planet. You start at a home base and go out from there. The kit has four skills. Getting started, a character script, tune the style, and set up the cast. It also has two routines, a weekly play tune-up and a cast health check. Both are meant to stay quiet unless something needs a fix. The recipe is in the repo if you want to read it instead of installing it. If you demo, stop after the handoff. Do not play a scene on the call.

## Close
If you try this after the meetup, start with three bots. Name them from the job. Give each one job. Let only one of them send mail. Put one routine on the bot that owns the check, and make silence the default. Use a template when you want a ready role, like this game master, instead of writing the persona from a blank chat. I used the same idea inside Cursor. One agent, one job, a name you can read in a list. Leaving didn't change the setup. It just moved it onto Grok Bot. Questions.

Meet: https://meet.google.com/aqo-smjs-rmo
Template: https://x.ai/bot/van80CjdHFc1ZDseneBEJ
Repo: https://github.com/tibor-src/space-opera-rpg
