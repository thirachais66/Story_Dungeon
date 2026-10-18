# Story Dungeon: Easy English Adventure

An offline Rain Tower adventure with short English messages and Thai translations

## Project objective

Help beginners understand and use simple English in four situations: asking for help, giving directions, reporting a problem, and passing work to a teammate. Players read a short situation, choose a helpful reply, and build a message from provided phrases. This is **supported phrase building**, not independent writing or a language proficiency test.

The beginner edition responds to playability concerns: shorter story text, visible Thai translations, one small step at a time, friendly retries, a gold-star suggested story choice, and no loss of health. Beginners should be able to reach an ending while learning what their messages mean. Human playtesting still needs to check that assumption.

The teacher's visible overview asks for an English-learning game made with AI assistance, meaningful language practice, an English demonstration, and connections to game design, playtesting, and professional communication for computer science. This edition keeps those purposes while reducing the amount of reading and writing. The full **273411_Practical_Project_Brief.pdf** was not supplied; check its detailed requirements before handing in the project. No coursework has been submitted by the game or this guide.

## Core loop and four missions

**Read the situation → choose a helpful reply → choose one phrase from each of three pairs → send the message → read Tali's response → keep exploring.**

The phrase builder shows one part at a time. Both choices in each pair are useful ways to express that part of the message. There is no essay, typing requirement, word limit, or automatic grammar grading. If a dialogue reply does not help, Tali explains gently and the game highlights a helpful reply so the player can try again. English phrases appear with Thai meanings, even when the interface is set to English.

| Floor and mission | What the player communicates | Connection to teamwork |
|---|---|---|
| 1: **Say Hello!** | Greet Tali, say that you are at the tower gate, and ask for help reading the map. | Give a teammate enough context to help. |
| 2: **Show the Way!** | Take the left raindrop path, go straight to the blue pillar, then turn right and avoid the eye tiles. | Give clear steps that another person can follow. |
| 3: **Something Is Wrong!** | The screen says OPEN, but the gate is closed; ask Tali to check it. | Describe an observed problem without guessing who caused it. |
| 4: **Send the Journal!** | Save the journal, send a copy to Tali, and wait for RECEIVED before turning off the radio. | Check that a teammate received your work before ending a handoff. |

The fourth mission is about the journal and radio, not the tower core puzzle. Tali is a fictional character; sending a message does not contact a real person or server.

To practise meaning beyond clicking, invite a player to explain their completed message in their own words, read it aloud to a partner, or have that partner follow the directions on a simple sketch. These partner activities are presentation/playtest activities, not automatically measured features. If a player cannot explain a completed message, record that honestly and improve the support.

## Adventure, support, and saved progress

The original concept remains: eight main scenes across four dungeon floors, a treasure chest, the Rain Tower's hidden promise, and four different successful endings. Players choose their name and appearance. Short Thai and English story text and a gold-star recommended available option help them decide. Other enabled choices remain playable. In this beginner edition, story choices do not deplete health, so a wrong turn does not cause an exhaustion ending.

Finishing a successful journey automatically starts the approximately 30-second crystal ceremony, unless the player enabled the separate skip-ending setting. Their character walks across the bridge, enters the chamber, and approaches the crystal before five beams reach five treasure chests. Pause, skip, replay, lighter effects, and a 2D fallback remain available. The ceremony celebrates finishing the adventure; it is not a language grade.

Optional listening uses an installed **local English voice** when the browser provides one. It does not use an online speech service. With no suitable voice, players can read normally or ask a partner to read aloud. Sound, interface language, text size, and motion preferences are available in settings.

The English field journal records the selected dialogue, assembled phrase messages, progress, and support/attempt information. Players can download **Story Dungeon - English Journal.txt**. These messages are evidence of supported selection and comprehension practice; do not label them original essays, independent writing, or a complete history of revisions.

When browser storage is available, the current beginner mission parts and story route are saved locally. Loading an older learning-version-one save preserves its story route but restarts the new beginner missions, in order up to the current floor. The old writing answers do not automatically pass the new tasks. A new adventure starts a fresh journal. Sending the HTML to a friend does not send the browser's saved progress.

## AI and computer science communication

AI helped draft and simplify content, develop code, debug, and plan tests. The group must review the result and understand what it presents. There is **no live AI chatbot inside the offline game**: authored dialogue and phrase choices determine its responses. The game does not assess unrestricted text or certify an English level.

Building and presenting this game gives the group practice in explaining requirements, writing usable instructions, describing software behaviour, reproducing bugs, and justifying changes from playtest observations. Keep a short record of which AI suggestions the group accepted, changed, or rejected, and why.

## Live demonstration plan

1. Start a fresh adventure, choose a name and character, and show the short backstory.
2. Show **Say Hello!** and explain its situation. Demonstrate a friendly retry, then select a useful reply.
3. Build a message by selecting one phrase from each pair. Explain what the finished message means, send it to Tali, and continue.
4. Show a short story scene and its gold-star suggestion. Explain that health cannot run out in this edition.
5. If time is short, use a clearly labelled prepared save to show a later mission, the ending, and the journal download. Do not call a prepared save a complete live playthrough.
6. Describe one actual human playtest observation and resulting change, or state that human playtesting is still planned.

Check the final packaged HTML on the demonstration computer before presenting. Rehearse to the time limit in the full teacher brief.

## Approximately three-minute English script

Replace bracketed text with truthful information. Read naturally and adjust the pace after rehearsing.

> Hello. We are [group name]. Our project is Story Dungeon: Easy English Adventure. It is an offline game in the Rain Tower. Players explore four floors, help friends, find clues, and choose what to do with a treasure chest and its keeper.
>
> Our goal is to make simple English useful during play. We designed this edition for beginners. The earlier activities asked players to write longer messages. We changed them because the game needed to be easier to finish. This version uses short situations, Thai translations, and small steps.
>
> The core loop is read, choose, build, send, and continue. Each floor has one English mission. Players ask for help, give directions, describe a problem, or send a journal to their teammate, Tali. These purposes connect to everyday teamwork and simple computer science communication.
>
> Here is the first mission. Tali asks if we need help. [Show a reply.] If we choose an unhelpful reply, she gives a friendly hint and we can try again. Next, we choose one phrase from each of three pairs. We introduce ourselves, give our location, and ask for help with the map. Then we send our message and read Tali's response.
>
> The game supplies these phrases, so this is supported message building, not independent writing. To check understanding, we ask players to explain their message or read it to a partner. For the directions mission, a partner can follow the message on a simple map. Clicking through alone does not prove understanding.
>
> The adventure also has short story text and a gold-star suggested choice. Health does not run out. Players can reach four different endings, with a crystal animation and their own character. The field journal records their assembled messages and can be downloaded for discussion.
>
> AI helped us draft content, create code, and investigate problems. The finished game has no live AI chatbot and does not grade grammar. It uses prepared dialogue and phrases locally. Optional listening depends on a local English voice in the browser.
>
> Our playtest checks whether players understand the steps, can explain their messages, and can finish without a facilitator giving answers. [Report one real observation and change, or say that human testing is still planned.] We must also check the teacher's full project brief before submission. Thank you. We are ready to show the game and answer your questions.

## Group roles and evidence

Fill in real contributions and observations only.

| Responsibility | Group member | Evidence reviewed |
|---|---|---|
| Requirements and learning goals | __________ | __________ |
| Story and English/Thai review | __________ | __________ |
| Interface, code, and build | __________ | __________ |
| Human playtesting and improvements | __________ | __________ |
| English presentation and demo | __________ | __________ |

| AI suggestion | Accepted, changed, or rejected? | Human reason and check |
|---|---|---|
| __________ | __________ | __________ |
| __________ | __________ | __________ |

## One-file hand-in

**Story Dungeon.html** is the playable offline file. The ZIP includes that file, opening instructions, licences, this guide, and the blank playtest worksheet. If the teacher accepts ZIP, it can serve as a single-file hand-in. Otherwise use the accepted format specified in the full brief. The package is not a published website.

Before handing it in, open the exact final file in a fresh browser profile or on another computer, complete a beginner mission, check the journal download, and record the actual result. Add real group names and contributions, complete human playtests, rehearse the English demo, and compare the package with the full brief.
