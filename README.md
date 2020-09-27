
Skip to content
Pulls
Issues
Marketplace
Explore
@maxloosmu
smucclaw /
complaw

6
13

    3

Code
Issues
Pull requests
Actions
Projects
Wiki
Security

More
complaw/doc/juniors/
Latest commit
@mengwong
mengwong advice on how to join slack channels
4 days ago
Git stats

    History

Files
Type
Name
Latest commit message
Commit time
. .
README.org
advice on how to join slack channels
4 days ago
recommended-configs.MD
Add link to GitHub guide to generate a new SSH key
4 days ago
README.org
Onboarding for SMU CCLAW Assistant Research Engineers and Trainees

SMU CCLAW’s Research Programme in Computational Law welcomes junior engineers.
Welcome

This is a welcome letter from the Research Programme’s principal investigator to the recently hired junior engineer. Thank you for choosing to join us. If it’s your first day and you’re wondering “what am I supposed to do?” you’ve come to the right place.
Onboarding

Somebody should have given you access to:

    an email address at the university
    (which should get you into the university library, through which you can reach many of the readings linked from this document)
    Google Drive, our file repository, which also contains many readings under the “BlackHole” folder
    Asana, for task management
    Github, our code repository
    Slack, for chatting amongst the team; you should join all the channels which you can.

If you don’t have access to those resources, say something!
Your place in the team

When recruiting the team we selected for a range of backgrounds and levels of experience. Some team members have decades of experience; some are relatively new to coding, but I believe that everyone will have a chance to make a contribution.

Whether that contribution takes the form of programming, documentation, evangelism, testing, support, or design, remains to be seen. But in general, the best way to position yourself to make useful contributions to the team, is to have a wide range of relevant skills and competencies. Take it from Robert C. Martin, author of The Clean Coder: A Code of Conduct for Professional Programmers:

    Do you know what a Nassi-Shneiderman chart is? If not, why not? Do you know the difference between a Mealy and a Moore state machine? You should. Could you write a quicksort without looking it up? Do you know what the term “Transform Analysis” means? Could you perform a functional decomposition with Data Flow Diagrams? What does the term “Tramp Data” mean? Have you heard the term “Conascence”? What is a Parnas Table?

Obviously, people aren’t born knowing these things. Some people studied them in (what must have been a very thorough course in) undergraduate computer science. Others acquire them mostly during their career – “on-the-job training”. If you’re reading this, you’re probably in the latter category. I certainly am. Some of those things I had never heard of, until “Uncle Bob” made me go look them up.

To help you acquire useful skills, we have outlined an experience that is equal parts

self-instruction
    a reading list and links to recommended third-party courses
project-based
    structured contributions to the Research Programme at various levels of difficulty
apprenticeship
    opportunities to pair program with engineers and work together on the same teams

This document focuses on the readings and video component. If you have joined the Programme as a junior engineer, consider this one pillar of your professional education. If you are worried that this is too much for you to take on, please be assured that your employee performance will not be tied directly to completion of readings and courses. This is not school and your manager is not your lecturer; nobody has time to test you. But if in conversation with the rest of the team we use terms that you aren’t familiar with, we may gently direct you back to the recommended reading, where you will find clues that may turn out to be essential to delivering your actual assignments.
Qualifications and Temperament

The following curriculum assumes minimal computer science experience. You might have a degree, but that degree might not be in CS. If you’re a self-taught programmer with significant technical abilities already, I beg your indulgence; just keep in mind that this document caters to people who may not have done any programming at all. Please feel free to edit it to be a better resource for them!

The curriculum does assume a temperament suited to problem-solving, acquisition of technical skills, and high tolerance for frustration.

And it assumes the sort of intelligence associated with logical reasoning and critical thinking, but also with creative imagination.

It also assumes that you possess very strong English reading, writing, and conversational skills both spoken and written. You should be fluent enough in English that the idea of reading and writing a lot of it does not bother you.

How do you know if you have these skills? If, as a child, you were always to be found reading a book, you’re probably fine. If the Sorting Hat would put you in Ravenclaw, rather than Gryffindor, if your friends and family go to you for help with technology problems, you’re probably a pretty technical person. (See what others have said: 1, 2)

Maybe you enjoy games like the Portal series and Zelda: Breath of the Wild. You try hard to solve the puzzles yourself before giving up and looking for the answer online. Maybe your hobbies are all creative in some way, and technology-related as well.

We tried to recruit for people who are good at both technology and people.

A career in software can rarely be conducted in isolation. The saying goes: “technical skills get you in the door, social skills get you up the ladder.” Some highly technical individuals may scoff at that, and say: ”I can single-handedly develop a filesystem; I don’t need people.” And it’s true that unlike kings and queens, wizards have an alternative path to power and impact: scaling through technology, rather than through people. But that is the archetype of the Saruman; isn’t it be better to be a Gandalf?

See Dan Rose on his Facebook 360.

At SMUCCLAW, even if you are working from home, or working remotely, you will be expected to participate as a member of a team. Because opensource communities often attract people with widely varying personal backgrounds, social norms, and communication styles, not to mention all the concrete characteristics that usually come up in discussions about “isms”, they adopt Codes of Conduct to clarify standards of behaviour. We have a code of conduct too. Please read it and help us keep standards high!

Where teamwork is concerned, the business world frequently recommends:

    Crucial Conversations
    Nonviolent Communication
    Getting To Yes

Why go through this curriculum?

The world is full of people in situations which do not give them the opportunity to fulfill their potential: they are fish who have been asked to fly, birds who have been asked to swim.

Check out Epicurious’s Ingredient Swap. Two chefs: one home cook, one professional expert. Most self-taught working programmers are like Lorenzo: well-meaning, doing the best they can, really likeable people. But if you’re Frank, you know the history, the context, the pros and cons. Your mastery of technique is so complete that you can guess pretty accurately how something will turn out even if you’ve never done it before.

Would you rather be a Lorenzo or a Frank?

More importantly, do you even enjoy cooking in the first place?
Is Programming “For You”?

The Japanese notion of “Ikigai” can be useful for young people trying to make career decisions. Study the Ikigai Venn diagram. How does it structure your thinking? Where do your friends and family fall?

Some of the junior engineers at the Research Programme are only a few years into a technical career, and they may be asking themselves if it’s the right choice. Technical careers can be challenging.

Type 1 challenging: “I go to the gym three times a week; this month I can lift 40kg, next year I want to lift 60kg.” You think of a computer as a toy, or a tool. A medium for personal expression. A way to make the world a better place. Or a way to have fun! – to make yourself smarter and more creative. These positives outweigh the inevitable frustrations.

Type 2 challenging: “I’m constantly lost and I just can’t seem to keep up with my peers – even when I can get the computer to do what I want, I just don’t enjoy the time I spend programming; it doesn’t give me a sense of flow, or mastery, or achievement. When I want to express myself creatively I have plenty of other avenues that have nothing to do with technology. When I even think about computers, I start to feel bad.”

Type 3 challenging: “the people around me are toxic.” The tech industry is rife with stories about bad behaviour. We’ll get into this later in this README. Back to the main point –

Some people start out in type 2 and switch to type 1. Many self-taught programmers got into software as a mid-career thing. They developed enough mastery to start treating computers as a fun challenge, a toy, a tool that they could start to apply in their own lives, perhaps in the way that the pioneers of computing called ”intelligence amplification”.

But some people don’t see the point of any of that, and are quite happy living an essentially non-computational life, finding fulfilment and pleasure elsewhere. If they need something done, rather than scripting a machine to do it, they get a human to do it. For most of human history, the route to power was through people. That’s how kings and queens have extended their will into the world since the invention of agriculture. Only in the past few centuries and decades has it been possible to extend your will into the world directly, using, basically, magic.

If, after a year with us, you find that you aren’t having fun, that you do not enjoy the work, that magic is, for you, not just hard but simply incompatible with the way your brain works, that’s a good discovery: better to know now, than spend years doing something you hate. But give it a chance, if you can: maybe find some way to connect technology to other areas of your life which you already care about, and see if you can use computers to help make the world a better place, or at least have some fun, in those areas. Or maybe you can “go into management” – product management, project management, account management. Having spent time in the trenches of software development you can put your experience to good use helping to coordinate and organize the work that others do.

The senior engineers on the team tend to be type 1 people who got into computing early because they had an affinity for it. If you already have one or two languages under your belt, and a number of projects in your portfolio, you might recognize yourself as belonging to the same tribe as them. You already understand what the Three Virtues is saying. In that case, this curriculum assumes that you see yourself as a lifelong learner; that you are challenging yourself to go outside your comfort zone; that your goal is to level up.
What does leveling up mean?

It means that some people spend their entire careers doing app development, building shopping carts and enterprise workflow systems and template fillers for clients. Many people would be proud to say in their bio:

    I am an expert in both JavaScript-the-language and the JavaScript front-end ecosystem. I know all of the language, good parts and bad, and I have experience working with React, Redux, Backbone, Angular, Babel, Webpack, Browserify, Gulp, Mocha, Ramda, and most of the rest of the JS frontend soup.

Some people consider that the modern equivalent of blue-collar labour. Some people go far beyond that. They might add It’s not my favorite technology, but knowing the language and its tools is pretty important for building modern web applications, even if you decide to use a compile-to-JS language.

And then they stick the paragraph on to the end of their bio, as an “oh, I almost forgot”, because it’s really the least of their skills. What does the rest of their bio say? https://lexi-lambda.github.io/resume.html
Don’t just use a library. Write a library.

Most programmers rely on third-party libraries; but can you imagine yourself writing a third-party library that other programmers rely on? All programmers start by learning an existing language, like Python or Javascript; can you imagine yourself writing a new language that other programmers learn? Language design and development is one of the highest forms of achievement in computer science, and if you start climbing those mountains you will find yourself in rarefied and respected company.

Let me offer a couple analogies. If you ask some people “where do eggs come from?” they will say, “the supermarket.” Where does water come from? “Out of the tap.” And that’s fine for 98% of the population.

But you’re in the other 2%. Maybe not quite so special as this legendary quote from the music community – this is closer to 0.0002%:

    I thought using loops was cheating, so I programmed my own using samples. I then thought using samples was cheating, so I recorded real drums. I then thought that programming it was cheating, so I learned to play drums for real. I then thought using bought drums was cheating, so I learned to make my own. I then thought using premade skins was cheating, so I killed a goat and skinned it. I then thought that was cheating too, so I grew my own goat from a baby goat. I also think that is cheating, but I’m not sure where to go from here. I haven’t made any music lately, what with all the goat farming and all.

The point I’m trying to make is this: when you write a program, you are very conscious that your program is a made thing: it was created in response to specific goals, by a specific person who was born on a specific date and has a specific set of skills. It has a certain amount of documentation and a user interface that makes it easy or hard to use. And it has shortcomings and flaws that you can see quite clearly, because you have a Platonic intention for what you want it to be, and you can see all the ways in which your work falls short.

Programming languages are also made things, with histories and biographies of their own. Just as you might be curious about the life story of a particular celebrity chef or a music band that you like, you might want to know where languages come from, how they are born, and how they grow up.

If you have the right temperament for technology, this curriculum will help you gain the theory and practice needed to understand and create computing technology across the span from individual bit in a CPU register, to Internet-scale applications. In the past, you may have used languages like Python and frameworks like React. But have you ever wondered where Python came from, what kind of thinking it would take to create a framework like React? This curriculum will, with luck and perseverance, move you closer to being able to make your unique contribution to the world of technology.

Donald Knuth said: ‘The idea that people knew a thing or two in the ’70s is strange to a lot of young programmers.’

Knowing the history of the field is helpful because as the saying goes, “Those who do not read history are doomed to repeat it.” (See also: https://www.quora.com/Why-was-the-prediction-of-future-of-programming-Bret-Victor-not-realized)
Sidebar: On Work

Speaking of “work”: most people use “work” as a verb: “I worked really hard today.” Professional creatives have the luxury of using “work” as a noun: “this is my greatest work to date.” As a professional programmer, “work” is both verb and noun. And, if all goes well, “work” is also “play”.
Sidebar: On Jargon

One of the risks of being self-taught is that you don’t know the official names for things, and that leads to really unproductive Googling.

A fair chunk of formal education is knowing what certain concepts are called, so that when you find yourself working with them, you can talk about them intelligently with other people. They don’t let you be a doctor if you don’t pass anatomy.
Sidebar: On Promotion

The senior researchers on the project, sadly, aren’t going to be with us forever. Some will be with us for only a year. That’s not much time for you to learn to fill their shoes. But the junior engineers are expected to learn what they can so they can become the next generation of senior engineers. I need you to pay attention to the work they do, and to how they do it, and how they teach it.
The skill tree

In video games like Zelda: Breath of the Wild, players acquire armour, skills, and weapons in a rough sequence from easy to hard (the technical term for this is a ”partial order”). The early training levels acquaint you with basic game mechanics: how to walk, run, jump, crouch. How to engage in combat with ranged weapons and hand-to-hand. How to add things to your inventory and purchase upgrades. How to talk to NPCs and other characters.

Once you’ve leveled up enough, you start fighting mini-bosses, bosses, and, eventually, the final boss. Many games follow that structure for a reason: it’s deeply human. It’s how people learn, and stay motivated. Learning is play!

The partially ordered sequence in which you acquire these skills is called a “skill tree”.

Developing software is similar enough to playing videogames that people have sketched skill trees for coding: http://dungeonsanddevelopers.com for web development, https://github.com/miloyip/game-programmer for game development. If you don’t like the thought of reading dozens and dozens of thick books, a professional career may not be right for you … whether that career is in law, medicine, or engineering. But if you approach those books as fun – as opportunities to gain skill, mastery, and power, which help to level you up, then that attitude will keep you motivated through the slog.

Zelda: BOTW has four divine beasts (Vahs Ruta, Rudania, Medoh, and Naboris) and one final boss: Calamity Ganon.

Likewise, the Research Programme has four major quests (NLG, FV, IDE/LSP, DMN/BPMN) and one final boss: the DSL.

Zelda also has dozens of side quests, 120 shrine dungeons, and 900 Korok puzzles scattered across the landscape. While you don’t have to solve all of them to win the game, they will make you a better player and offer many opportunities to enjoy the game more. Have you followed the blue glow at night to Satori Mountain? It’s really beautiful!

The Research Programme likewise offers numerous side quests: Internet protocols, cryptography, standards processes, the philosophy of open source, editor integrations, data visualization, SVG, APIs. And there are plenty of slightly tedious Korok puzzles. All this might smack of yak-shaving, but it’s part of skilling up.

Imagine a conversation with a skilled chef:

“I want lasagna for dinner. But I don’t have any pre-bought in the fridge.”

“I can make lasagna.”

“But I don’t have any lasagna pasta sheets.”

“No problem, I can roll them; just give me flour and an egg.”

“I have some eggs in the fridge but I don’t know which are hardboiled and which are raw.”

“There’s a spinning trick you can use to find out.”

“Ok. I want extra onions and garlic. Can you do that?”

“Sure, no problem. I’ll start the prep by chopping onions and garlic.”

“Here you go.”

“So, uh, this knife you have, it really needs to be sharpened.”

“Do you how to sharpen a knife? I think I have a sharpening stone lying around somewhere, that I’ve never used.”

“Yes, I can sharpen your knife. Give me the stone.”

“Uh, actually, I can’t find it.”

“Okay, do you have sandpaper?”

“Let me check … nope, I don’t have any.”

“Never mind, I can use the bottom of a ceramic bowl.”

This is the sort of skill tree that comes up all the time in cooking. A master of the kitchen doesn’t just know how to cook a dish; they know how to strip and season a wok, build a fire for smoking, upgrade the firmware on the sous vide circulator, bandage a wound, and sharpen a knife three different ways.

In computing, the training levels begin with Unix, file editing, and connecting to our shared server over a cryptographically secured link. In the immortal words of Trinity in the Matrix: ”I’m in.”
Resources

CCLAW has a shared Linux instance which you will be given a user account on. If you do not have access to a Unix system of your own, you can use your shell account there to do your work. All you need on your computer is a terminal program and SSH.
Workstation

If you do not have a computer of your own, please mention this to management; it may be possible to issue you a work laptop.

A magician never forgets their first wand; a hacker never forgets their first Unix machine. For less than $200, you can order your own Raspberry Pi with 8 gigs of ram. Or you could boot up an AWS instance in their free tier; do this using your own Amazon account.
Access to readings and courses

You may prefer to buy your own copy of books; alternatively, look to the library.

The edX CS50 courses recommended in this guide are free to take, though if you want certification you will have to pay separately.
Your Teammates

Your teammates are a resource, but a valuable resource. One way you can show respect for them is by asking Google first and your teammates second.

What do I mean by that?

You may have had the experience of being in a movie theatre movie with someone who constantly asked their friends, out loud, “oh my god, who do you think was the murderer? Who is this character and why are they behaving that way?”

Don’t be that person. Try to solve your own problems first; some amount of time between five minutes and an hour is probably appropriate. Beyond an hour, if you’re still lost, it’s probably okay to reach out to ask for clues. If you’re following explicit directions and the directions seem to be obviously faulty, go with the five-minute end of that range. If you can suggest an improvement to the directions, even better.

It’s okay to document your learning journey out loud, by the way. On our shared Slack chat you can say, “Here is a thing I’m trying to figure out. I’m not asking anyone for help yet, I’m just letting you know what I’m doing, and when I reach the solution, I’ll share that too, in case it benefits anybody else in future.” We have a channel on Slack for this: #rubberduck. (Indeed, it’s not just okay, it’s a virtue; the willingness to be wrong, or ignorant, in public goes hand in hand with humility and, ultimately, confidence.)

At that point someone else may feel the urge to jump in and help. This is better. Everybody likes to be helpful. Nobody likes to be interrupted.

You may also have had the opposite experience: you ask somebody to do something. If you did it, it would only take you ten minutes; but you decide to delegate. Two days later, you ask if they’re done; they say, “no, I’ve been trying for the last two days, and I just don’t get it.” Digging deeper, you discover that they were lacking some crucial piece of information: a password, maybe, or maybe their computer is weirdly misconfigured. “Why didn’t you tell me sooner?”

Don’t be that person either.

I wrote this section with the hopes of pre-empting such a situation; if I were to write it after an incident occurred, the people involved in that incident might feel unfairly singled out, as the victims of passive-aggressive policy-making. So, better safe than sorry.

See also:

    How To Ask Questions The Smart Way
    How to ask good questions
    Why Ask Questions in Public?
    XY Problem

How To File A Bug Report

When you do ask for help, by default, you can frame your question in this way:

    I’m using version VVV of this software (and I’m running on OS version XXX).
    I’m trying to achieve this goal:
    I did this action:
    I expected this to happen:
    But something else happened instead:
    Here is a screenshot or a copy-and-paste of the error message I got:

Meng sometimes goes a bit overboard and submits an entire YouTube video of his session, but he only does that when he is feeling extra frustrated.
Tracking Your Progress

    Figuring out how to get people to consistently track what they’re doing, and making it easy to do so with minimal duplication of effort, remains one of the hardest problems in tech. I hate doing it, I hated enforcing it, and I hate when we don’t have the visibility it provides. @darkuncle 2020-08-18

We use Asana to track progress at work. Work includes readings and learning exercises.

A task management system may take some getting used to – but in time I hope you will come to see it as a friend and not a chore. In traditional office-bound organizations, people rely on meetings and informal social mechanisms to know what others are working on, and to communicate what they are working on. In early 2020 when many organizations were forced to go remote, there was a great deal of disruption: some old-fashioned managers’ old-fashioned paranoid instincts may have kicked in, to the tune of “if I can’t see my staff sitting at their desks, then I’m going to assume they are at home slacking off watching TV and idling.” The technology sector turns out to have been more ready than most, in that many successful software organizations have been remote-first or remote-only for ages. They make heavy use of task-tracking software, which helps quell the fears of those old-fashioned managers, or least transmute them to “if I can’t see my staff updating Asana …”

Tracking your tasks helps you answer the question: “gosh, what did I even do this day/week/month?” Looking at my list of completed tasks helps me realize that I actually get quite a lot done, even if it wasn’t work that I originally planned on; it was emergent work. It still feels satisfying to mark a task complete.

But this takes discipline: the only way you get to mark a task complete is if you created it in the first place. And I sometimes have to remind myself to do that. For example, I just went and created a task: “update onboarding README”.

Two good ways to report progress: by creating subtasks and by logging comments to tasks.

Yak-shaving is a good example of recursion; sometimes it’s part of the learning process, and sometimes it’s unnecessary work which you can trim. Often it’s hard to know in advance which category the work falls into; if in doubt, ask others! Either way, though, you deserve to get credit for that work. So create subtasks. If you’re really off on a tangent, this gives your teammates a chance to gently steer you toward not wasting your time.

Logging comments to tasks is often a good way to share your thinking with others and clarify it with yourself. Get that rich inner dialogue out in the open: log your findings, your working hypotheses, and your opinions. Blow off a little steam. Again, this gives your team members an opportunity to step in; if you’re getting frustrated or stuck or lost, they can help bail you out. In turn, when you watch your teammates struggling with something you already solved, you can step in and help.

TODO: As a starting point, go duplicate out some of the standard learning/reading tasks under “Learning Computational Law” for yourself, and log your readings as you go.
Working in Public

Being verbose in Asana is one way of working in public, keeping your visibility up so that your teammates don’t have to wonder if you’ve been hit by a bus. You might think, as long as I turn in my work on time, why should everybody else need to know of my progress? The problem with software is that working in isolation tends to not be very sustainable in the long term: it takes only one episode of “oops, I didn’t actually get it done on time” or “oops, the work you turned in was actually based on a misinterpretation of the requirements” for everybody else to assume that if they’re not hearing from you then you’re off in your own world again … and that doesn’t inspire confidence.

It’s natural to feel shy about sharing your work:

    https://twitter.com/darcy_sandall/status/1294178520873070592
    https://twitter.com/chrisalbon/status/1294858338522423301

The antidote:

    https://twitter.com/MariaShen/status/1293025429238853633

Working in public also means having conversations on public channels, by default, rather than private messages. If you save your private messages for truly confidential content, then the discussions you have in public, even if they appear to only be one-on-one, can be read by someone in the future who might be hunting for clues as to why certain “historical” decisions were made.

Hm, maybe we’ve identified one evolutionary driver of techbro culture? Because the willingness to be verbosely wrong in public actually helps the organization as a whole. Well, let’s see if we can take the good parts (confidence, communication) and leave behind the less savoury bits.

Anyway, this is also a cultural thing, and for the junior engineers to feel the psychological safety needed to engage, the senior engineers have to set an example.
This Guide is Open Source

If you find any errors or want to make any changes, fork the repository, commit changes to your fork, and send a pull request.

The content of this guide is licensed under CC BY-NC-SA 4.0: https://creativecommons.org/licenses/by-nc-sa/4.0/
Project-based Learning

If you’re champing at the bit, this section will satisfy – or at least pique – your curiosity about what we are trying to accomplish at CCLAW.

Actual tasks are defined elsewhere – in Asana, or Github Issues – but these are some of the main quests and side quests that the team may attempt over the coming months and years.

As you read through this list of projects, ask yourself: “how would I attempt to do this with the skills I currently possess? What new skills might I have to learn to achieve these goals?”
From Your Own Experience

Have you ever been in a situation where you wanted expert advice about a body of rules, to inform your choice of actions?

How did you solve that problem?

Did you learn the body of rules for yourself? How long did that take?

Did you look for answers online in some community of practice, e.g. Reddit or Stack Overflow?

Did you seek advice from an expert human? E.g. a lawyer?

Did you use computational resources rooted in machine reasoning?

How do you approach problems in medicine and health differently from problems in law and contracts?

How do you approach problems in the fields where you have the most experience, differently from the above? E.g. finance, accounting, data science, music, arts?
Make it possible for a non-lawyer to think through a legal scenario with the help of their computer, without having to ask a human.

If you need to think about a business scenario that deals largely with numbers – for example, with a budget – you might turn to a spreadsheet and use that to “help you think”.

Today, that’s not possible for legal scenarios. You wouldn’t open Microsoft Word and start typing and expect to see sentences automatically compute themselves, the way Excel might automaticallly calculate a sum or an average.

“Am I allowed to do X?”

“I want to achieve X. What do I need to do?”

“I want to make an agreement with someone else. Help me draft an agreement that sets out our respective obligations and deadlines.”

“I’ve been asked to sign a contract for X. I’m concerned about scenario Y – can I do Z, or will I have to do Z? How does X deal with Y?”
Make it possible to encode a law or a contract in a formal language.

… this is the goal of the DSL track of work.
Make it possible to convert such an encoded law or contract, back to a natural language such as English, automatically.

… and other languages, too.

This is the goal of the NLG track of work.

The English doesn’t have to be super readable; it only has to be as good as current legal writing.
Make it possible for a non-lawyer to download existing libraries and examples of source code written by other people, and tweak them.

… from Github, perhaps.
Make it possible for somebody drafting in our DSL to get the same kind of help from their editor as you would for another language.

IntelliSense, tab completion, linting, type checking … all these things should help a drafter.

This is the goal of the IDE track of work.
Make it possible for advanced IDE features to help a drafter find bugs in their code.

“Your proposed law/contract makes it impossible for somebody to actually perform their obligations, because line 12 conflicts with line 63.”

This is the goal of the FV track of work.
Make it possible to embed an encoded contract via XML into a PDF using XMP.

XMP does for PDFs, what EXIF does for JPGs … kind of.
As part of DSL development, identify and leverage an existing formalism for constitutive rules.

As the Rates Rebates example shows, some rules are essentially mathematical formulae: how much rebate am I entitled to under condtions X and Y.

There are existing business tools that save us from reinventing that particular wheel. Explore DMN: Decision Model & Notation. There’s a good tutorial by Camunda. See also https://twitter.com/hillelogram/status/1248082689149861888

Read about the history and the pros and cons of Model-Driven Architecture.
Specify DMNMD for Markdown

DMN is too good a DSL to be stuck in a graphical UI. Use Markdown tables to allow people who prefer text editors, to write decision tables in text.

See:

    https://twitter.com/hillelogram/status/1248082689149861888
    https://www.youtube.com/watch?v=0XL-LM0fpN4

What would a decision table look like, translated to Markdown? Let’s call that DMNMD, where the “MD” stands for Markdown.

This is the start of the DMN track of work.
Implement DMNMD in native Python

Now we have a way to avoiding massively complex if/then/else statements. Build it in Python.

    Read Hillelogram’s article on decision tables.
    Try out the Camunda DMN demo online. Read their tutorial.
    Write documentation and a specification for DMNMD in your favourite language.
    Try converting some gnarly code you wrote recently to DMN syntax.
    Implement an MVP proof of concept in your favourite language for a simplified DMNMD: supporting only a unique hit policy and S-FEEL comparison expressions in your favourite language. Don’t bother supporting separator escaping, just do a string split. You can revisit this and do a proper parser later when you have more programming language / compiler theory under your belt. You can do a simple implementation just by reading the Camunda tutorial, you don’t even really need to read the DMN spec to grasp how it works.

Implement DMNMD in native Typescript

Same as Python, but for Typescript. Stick your work on Github first. Then consider sticking it in npm under the SMUCCLAW account. Eventually this will become a top-level package.
Implement DMNMD in your favourite language

If you come from some other language, like Rust or Go or Ruby, go nuts – same idea as above.
Document your implementation of DMNMD.

There are four kinds of documentation. https://documentation.divio.com/
Make it possible to convert a DMNMD table to natural language.

How would you spell out the DMNMD table in English?

This is part of the NLG track of work.
Consider doing the same for BPMN that we did for DMN.

While DMN is “purer” in a functional sense, BPMN deals with multiple actors, passing messages to one another, acting in time.
Build out planners, expert systems, and interactive scenario explorers.

See the Drools suite of systems, like OptaPlanner, for an example. See also ILOG CPLEX. How would you integrate against these things? How would you write one?
Can legal text be drafted as a satisfaction of a system of constraints?
README FIRST: Foundational reading and Courses

I’m impatient to get started! What should I read?
In the Beginning was the Command Line, Neal Stephenson
The Clean Coder, by Robert C. Martin
Research Meets Practice

Browse the presentations at http://www.remep.net/materials-2020/

    Michael Genesereth: https://www.remep.net/wp-content/uploads/2020/06/Michael-Genesereth_Computational-Law_The-Cop-in-the-Backseat_ReMeP2020.pdf?x45466
    Robert Kowalski: https://www.remep.net/wp-content/uploads/2020/06/Bob_Kowalski.png?x45466
    Marcus Triska: https://www.remep.net/wp-content/uploads/2020/06/Markus-Triska_Logic-Programming-in-modern-e-Government-Services_ReMeP2020.pdf?x45466

CS50 from edX

This is a roughly 12 week course.

https://courses.edx.org/courses/course-v1:HarvardX+CS50+X/course/

There are actually three different courses that are worth checking out, all under the brand CS50.

CS50x
    the basic prata kosong. Do the exercises.
CS50 AI
    seven lectures on different techniques in AI. Do the exercises.
CS50 for Lawyers
    revisit CS50, but from the perspective of lawyers. If you’ve done the above then you can probably skip the exercises and just skim the videos to get a sense of what the lawyer audience cares about.

So, all told, the CS50 curriculum will probably take you several months.
Learn Haskell

This will probably take you several more months. See Haskell resources below.
I feel like I’m back in school again.

Well, this research programme is hosted at a university.

“But the CS50 stuff took me three months, and now you’re asking me to take another three months to learn Haskell. When am I going to do actual work? Are you paying me for six months to just sit around and be unproductive?”

In short, yes. Most juniors come onboard without a CS degree. You need to spend some time catching up. Most CS degrees take four years. Cramming that into six months is ambitious. But this is our commitment to train juniors. And even then, staff who join with a CS degree don’t have specializations in computational linguistics, formal verification, and programming language design. Most CS master’s programmes take two years. We’re cramming that into another six months.

“So you’re saying, this research programme is doing work at the PhD and post-doc level.”

Yes, that’s what research programmes do. And we’re trying to give you enough training in your first year to be able to participate usefully alongside people who have spent ten years in school. How do we do that? By focusing on specific areas of instruction; by minimizing the time spent unproductively trying dead ends; and by encouraging you to share your learning journey with your fellow researchers, so that when one person learns something, everyone else learns it too.

“But I hate school … I have so many bad memories.”

Do you hate school or do you hate learning? Learning new things is hard: it’s a cognitive burden that requires lots of naps; and it’s an emotional challenge because learning requires you to be wrong, and people don’t like to be wrong.

And it’s a time challenge: it turns out that the geeks who stayed home on weekends to play with computers instead of going drinking were getting a head start on everyone else, measured in the thousands of hours. It takes time to learn tools, make mistakes, read documentation, write programs, reinstall OSes, explore dead ends, ask for help on forums, and give help on forums.
“I think I’m done with the curriculum … what should I do next?”

If you find yourself at a loose end:

    review Asana; are there really no tasks assigned to you?
    review your learning objectives; are you all caught up on the assigned reading? Are you “done” learning Haskell and Python and Unix? Have you studied everything on Matt Might’s list? Have you asked your colleagues to help you learn the material listed under the Detailed Syllabus below?
    look around for where you could help; does some other team need help? Can you help that team move forward?

What Every Computer Science Major Should Know, by Matt Might

Matt Might gathers on a single page what most university curricula incoherently scatter across four years’ worth of course descriptions.

Robert Martin’s Clean Coder says “Know Your Field”:

    A wealth of ideas, disciplines, techniques, tools, and terminologies decorate the last fifty years of our field. How much of this do you know? If you want to be a professional, you should know a sizable chunk of it and constantly be increasing the size of that chunk.

At CCLAW, we focus on the “traditional AI” aspects of computer science: knowledge representation and reasoning (“KRR”), logic programming, scheduling and planning problems, rule systems.

But the more you learn, the better. Knowledge is power. If you ever find yourself struggling because you’ve bitten off more than you can chew, remember there are giants whose shoulders you can stand on.

For a sense of the “last fifty years of our field”, take a look at:

    The Future of Programming, by Bret Victor
    Forecasting the Internet, work by Paul Baran
    Tools for Thought, by Howard Rheingold

This web page tries to help the self-taught programmer learn CS: https://teachyourselfcs.com/

I recommend taking up Matt Might’s curriculum in the following order:
The Unix philosophy

The original Unix paper is at http://www.scs.stanford.edu/18wi-cs140/sched/readings/unix.pdf – I think his link to it may have bit-rotted.

    https://www.amazon.com/UNIX-Linux-System-Administration-Handbook/dp/0134277554/ref=dp_ob_title_bk
    https://en.wikipedia.org/wiki/Unix_philosophy

If you run a Mac, you have a Unix system. If you run Windows, you may be successful with https://en.wikipedia.org/wiki/Windows_Subsystem_for_Linux, or you may be better off with an account on our shared Linux server.
Shell multiplexing

You have your choice of tmux or screen. Most people prefer tmux nowadays.
Shells themselves

You have your choice of bash or zsh.
SICP

Structure and Interpretation of Computer Programs helps you realize how ubiquitous parsers and domain-specific languages are in computing. Every time you run a Python program in your terminal, at least two interpreters swing into action, doing an enormous amount of work within just a few short milliseconds. Can you say what the interpreters are and what they do?

SICP expands your mental vocabulary and grammar; you will start to think about computing problems the way computer scientists do.
About Editors

A good first editor nowadays might be VS Code, Atom, or Sublime.

If you are a Mac user, learn just enough Emacs to use its keybindings, and then see where else those keybindings work. The tutorial should take you about an hour. See https://gist.github.com/cheapRoc/9670905

If you’re curious about Elder Magics, you might go deeper into Emacs. Sacha Chua has a good Emacs blog: https://sachachua.com/blog/emacs/

Speaking of keybindings, you may enjoy installing Vimium for your web browser, so you don’t have to reach for the mouse so often.

Other colleagues like to use NeoVim.
Languages

The fact that there are multiple programming paradigms may come as news to those who grew up monolingual, or had strongly vocational educations in programming. This is perhaps the weakest point of the self-taught programmer: it is too easy to pick one language and stick to it, defining your identity narrowly. “I’m a Python programmer” subtly implies “I’m a not-Javascript, not-Ocaml, not-Ruby programmer”. But languages facilitate cognition. Why accept constraints on your ability to think and solve problems?

The 2007 Model Curriculum for a Liberal Arts Degree in Computer Science is emphatic about learning multiple paradigms:

    Different paradigms, such as object-oriented and functional, provide distinctive ways of thinking about and solving problems. Students who experience multiple approaches and appreciate their tradeoffs understand the value of applying alternative problem-solving models when confronting complex, real-world applications. Two approaches that integrate object-oriented and functional programming are presented in detail in Appendices A and B. If desired, functional programming could be replaced by another sufficiently different paradigm, such as logic programming.

In How Programming Languages Have Evolved (2019) Rebecca Parsons said: “We use the phrase polyglot programming to capture the idea that we should judiciously expand our language choices to address different problem spaces.”

Peter Van Roy’s Programming Paradigms for Dummies shows the ingredients that go into programming languages. If natural languages differ by features, programming languages differ by paradigm.

From Matt Might’s list, I would suggest starting with

Javascript
    (update: Typescript and Deno); this is the lingua franca of the web today. But it is not a well-designed language; it has many flaws, both in its native syntax and in its jungle of packages. It’s gotten better over the years.
Python
    after Javascript will give you a good appreciation for “comparative linguistics” – you can analyze differences in vocabulary and grammar, and begin to abstract the idea of a language feature. Python and Javascript are like two dialects of Chinese.
Haskell
    Extreme FP is a very different, almost alien, mode of thought. You may, after some time, say “nice place to visit, don’t want to live there.” But you will never use lodash the same way again; and when you work with a dynamically typed language, you will better understand what people mean when they say ”BIGNUM% of bugs are type errors”. More below.
Prolog
    for an introduction to unification and backtracking as first-class language features; know enough to appreciate the Power of Prolog. You want German for philosophy, Italian for romance, and Prolog for logic and constraints.
Racket
    enough Lisp to hack your .emacs, understand homoiconicity, and appreciate the Lisp Curse essay.

together, these will give you good exposure to enough programming paradigms that you will know which language to use for a given situation.

Once you’re there, you can proceed to more advanced, specialized languages. For example, if you work in constraint or logic programming, you can explore Curry, Flora-2, and ErgoAI. Or try Oz.

Most programming languages take at least two weeks to even begin to grapple with. Getting the compiler installed, and your editor working with the language, may take an hour if you’re lucky or a day if you’re not. Ask your teammates for help. Any introductory tutorial will come with exercises that you really should work through. After that, it will take you many months to get good – to know the idioms, the warts, and the libraries.

For the purposes of this curriculum you might choose to dedicate at least three months to each language; and you should use all the resources you can find, including books (yes, actual physical hardcopy books from the library – sometimes softcopy books have formatting and layout issues which create unnecessary mysteries), video courses, online documentation and third-party tutorials, and community forums.

http://www.rosettacode.org/wiki/Rosetta_Code is kind of like cheat codes: “programming chrestomathy”.
Standard Skills

In every language you should master a basic set of useful skills:

    read, manipulate, and write text files, line-by-line
    work with regular expressions; implement grep
    construct an HTTP request and retrieve it
    read, manipulate, and write HTML
    read, manipulate, and write XML
    read, manipulate, and write JSON
    interact with the end user at the terminal or in a REPL
    handle dates and times

You should be able to implement a web scraper in at least one language. Don’t worry, there are plenty of good libraries out there, like Puppeteer for Javascript and hxt for Haskell.
Implementing an interpreter

Work through the New Zealand Benefits RaC exercise (link to be provided).
<<<Haskell resources>>>

When the University of Texas tried to replace Haskell with Java, Dijkstra himself objected in the strongest terms.

Matt Might says: “Haskell is the crown jewel of the Hindley-Milner family of languages. Fully exploiting laziness, Haskell comes closest to programming in pure mathematics of any major programming language.”

Sounds nice in theory! But you deserve to know what you’re getting into: it would be unfair to downplay the cons. Read Why Not Haskell; The Pain Points of Haskell; On Marketing Haskell for some straight talk.

Matt Might’s remark is worth unpacking. Back in the 1990s, an influential book was published with the title Design Patterns: essentially, problems that repeatedly arise in software development, and how to solve them.

In cooking, every culture implements the Dumpling pattern: a meat or vegetable filling is wholly encapsulated by a carbohydrate layer, and cooked. The insides stay edible longer, because the carbohydrate layer acts as a barrier to microbes and insects. The product is also easier to handle as the outside layer stays dry while the insides are moist.

The Dumpling Emoji Project says: “Dumplings are a seemingly universal food, popular throughout the world’s cultures. Poland has pierogi. Nepal has momos. Russia has pelmeni. Japan has gyoza. Italy has ravioli. Georgia has khinkali. Korea has mandoo. Argentina has empanadas. Jews have kreplach. China has potstickers.”

But we don’t force beginner cooks to learn germ theory and material science before letting them make the dumplings. We just give them a spoon, because dinner has to be on the table tonight.

The Wikipedia page says: a primary criticism of Design Patterns is that its patterns are simply workarounds for missing features in C++, replacing elegant abstract features with lengthy concrete patterns, essentially becoming a “human compiler” or “generating by hand the expansions of some macro”. Peter Norvig demonstrates that 16 out of the 23 patterns in Design Patterns are simplified or eliminated (via direct language support) in Lisp or Dylan.

Haskell programmers, being masters of abstraction, would agree: if a certain programming problem keeps recurring, then obviously the correct approach is to solve the general case in the form of a reusable library; wearing the hat of library author, you abstract out the essence of the pattern, taking care of the hard bits; then wearing the hat of the developer, you to customize it to suit your particular problem. If you can’t solve it at the library level you put on the hat of language developer and crack open the compiler itself.

Follow that line of thinking to its logical conclusion. In Imperial China, certain challenge poems forbade repetition: you couldn’t use the same word twice through the entire poem. In Haskell, the idea of factoring out repeated code can be taken to similar extremes.

Let’s add to the challenge: every line of your poem is also required to reference a different classic poem written by some centuries-dead poet.

Why? Because (to satisfy the criticism above) the advanced programming patterns are no longer in a popular book everybody has to read: instead they are embodied in the language itself and in popular libraries that everybody has to learn. Such great power! But also such great responsibility! (“If Spider-Man wrote Haskell.”)

Now, before you can write your program you now have to understand twenty other libraries and arcane language features. Before you can do anything useful, you first have to study all the history and learn all the masterpieces and read all the papers. Before you can build any bridge you have to be able to build every bridge.

In most languages, it’s at most five lines to write “Hello world”. It’s at most five minutes to make a peanut butter sandwich.

In Jiro Dreams of Sushi, it’s ten years before you’re allowed to cook eggs. Haskell can be closer to that.

This is Joel’s Law of Leaky Abstractions at work: there is a certain amount of complexity in any field, and abstractions can only hide it from you for so long; sooner or later you will have to open up the black box and learn how it works. Haskell wants you to learn CS early, singing in the choir; other languages let you learn CS late, as a sinner born again. (A New Jersey worse-is-better sinner, to be precise. Essay, Context)

All that being said, we’ll try to make Haskell accessible, so you can climb the learning curve less painfully than most. We’ll show you the easier routes up the mountain and how to get unstuck. We write junior code.

When Lisp programmers look at code written by less sophisticated programmers in less sophisticated languages, their reaction is often: “dude, 90% of the work you’re doing here isn’t even about solving your actual problem; it’s just you micromanaging the computer to get you to the point of being able to solve it. Why don’t you all have a library for that? Or language features that make the solution easy?”

Hence Greenspun’s Tenth Rule: “Any sufficiently complicated C or Fortran program contains an ad hoc, informally-specified, bug-ridden, slow implementation of half of Common Lisp.”

But also, hence the Lisp Curse.

That evolution can be seen in many languages: the libraries increase in number and complexity; the language gains functional idioms and type annotations. And you end up with a sort of convergent evolution in language design. Landin foresaw this in 1966; retrospective.

As https://twitter.com/mcclure111/status/1272727666802786304?s=20 put it: “The only three programming languages are ASM, Python and Haskell. Anything else is actually just one of those three languages in disguise.”

Coming back down to earth, these resources are recommended for learning Haskell:

    http://haskellbook.com/ and Get Programming With Haskell are our top recommendations. Using two texts at once is a good way to triangulate; when one doesn’t make sense, try the other. GPWH is available via the library.
    And ask for help! You are surrounded by experts who are literally being paid to teach you. You are being paid to learn. This is a rare situation. Make the most of it.
    https://www.udemy.com/course/learning-path-haskell-functional-programming-and-haskell/ offers 73 lectures. They may be a useful complement to the book, worth watching at mealtimes maybe.
    https://twitter.com/aymannadeem?lang=en blogs frequently at https://www.aymannadeem.com/
    https://lexi-lambda.github.io/index.html is another blog
    http://dev.stephendiehl.com/hask/ is an entire book pretending to be a blog post
    https://ocharles.org.uk/ starts getting into intermediate Haskell
    https://www.quora.com/What-effects-did-learning-Haskell-have-on-you/answer/Panicz-Godek for historians only

“Learn You A Haskell” has been popular for some time, perhaps due to stylistic similarities with why’s (poignant) Guide to Ruby, but it was written at a time when those other two resources were not available. Now that they are, I no longer recommend LYAH except when you need a third point of triangulation.

Other Haskell random factlets:

    You may have heard that Haskell is really good for programming language design and compiler development. That’s one of the reasons we’re using it. You might have heard of Perl 6; you might not have heard that Perl 6 (now Raku) was first implemented in Haskell, by Audrey Tang, who went on to be digital minister of Taiwan.
    Haskell is used for data science (at Target, at least): https://www.forbes.com/sites/quora/2018/01/24/when-is-haskell-more-useful-than-r-or-python-in-data-science/#522db41e69e4
    See the Haskell data analysis cookbook: http://haskelldata.com/

After you’ve achieved Beginner Haskell status you can proceed to Intermediate Haskell:

    https://alpacaaa.net/thoughts-on-haskell-2020/ argues in favour of Boring Haskell
    https://github.com/commercialhaskell/rio
    https://ocharles.org.uk/posts/2014-12-01-24-days-of-ghc-extensions.html starts getting into intermediate Haskell
    https://ocharles.org.uk/pages/2012-12-01-24-days-of-hackage.html
    https://ocharles.org.uk/pages/2013-12-01-24-days-of-hackage.html
    http://felixmulder.com/writing/2020/08/08/Revisiting-application-structure

Formal Methods

    https://www.hillelwayne.com/post/decision-tables/
    https://www.theatlantic.com/technology/archive/2017/09/saving-the-world-from-code/540393/

Artificial Intelligence

    Gödel, Escher, Bach.
    Russell & Norvig.
    https://www.doc.ic.ac.uk/~rak/history.pdf
    https://www.doc.ic.ac.uk/~rak/papers/newbook.pdf
    https://cs50.harvard.edu/ai/2020/

Networking

Understand the workings of TCP/IP, UDP, DNS, SMTP, and HTTP.

Using the telnet or netcat commands, send an email by hand by talking to SMTP port 25.

Load a web page by hand by asking for it from port 80. Maybe from neverssl.com.

Visit the history of cloud computing (once called “grid computing”). Visit a machine room after reading The Eternal Mainframe.
Ethics

Discuss:

    What did ”I never argue with a man who buys ink by the barrel” mean when it was first said? What argument do The Internet’s Original Sin and The Eternal Mainframe have in common? Where would you locate projects like Carl Malamud’s Public.Resource, FreedomBox, and Mastodon on a spectrum relative to Facebook, LexisNexis, and Westlaw? What predictions did Tim Wu’s Master Switch make, and how have those predictions fared in the ten years since publication?
    What is an imprimatur? How did state and religious powers respond to the invention of the printing press? The life of Christophe Plantin may prove instructive. How were his professional duties at odds with his personal beliefs? The dates June 1, 1501, and June 15, 1520, may turn up as significant in your research. How would you compare those events with news from June 3, 2020?
    How do you see these considerations applying to the future of legal tech, and to the specific aims of the Research Programme in Computational Law?
    Why factors contribute to the widespread sharing of standards via forums like the IETF, sharing of software on sites like Github, and to the sharing of knowledge about software on sites like Khan Academy, Udemy, and Stack Overflow? What degree of sharing can be found in other fields such as medicine, accounting, law, makeup, cooking, costuming, and applied psychology?

The rest of Matt Might’s curriculum

… can probably wait until you find yourself embarking on specific side quests that need those skills. While the research programme does not touch these areas specifically, every working (web-era) programmer should know:

    SQL (Postgres, SQLite, or MySQL)
    Apache and Nginx; wget and curl
    Some Javascript framework for front-end development
    basic public-key cryptography (GPG to understand the concepts, openssl to create an SSL certificate of your own)

Enough OS architecture to understand https://blog.quarkslab.com/playing-around-with-the-fuchsia-operating-system.html

Content addressing. DHTs. The architeture of BitTorrent. IPFS. And Unison. Nix and NixOS.
Law as an Application Domain in Computer Science

    https://courses.edx.org/courses/course-v1:HarvardX+CS50L+Law/course/

Know your tools.

https://missing.csail.mit.edu/

We make heavy use of the Unix shell.
Git

You may need to work through an introduction to Git and Github to get comfortable with cloning things to your local workstation.

By default, when people pass around Github URLs or talk about such-and-such a repository, you are expected to clone that repository locally, the better to explore it using your own editor environment.

Hint: you want to set up ssh access to your Git account. If your git remote -v shows https rather than git@github you will have trouble pushing.
Other Things An Educated Technologist Should Know

In conversations among experienced technologists, many of the following references are expected to be common knowledge “within the tribe”.
History of the Internet and the Web
As We May Think, by Vannevar Bush introduces the Memex
Probably the closest thing today is Roam Research. Give it a try, see if you like it.
What is the history of Wikipedia? Where did wikis come from? What was the first wiki?
If you are an Emacs user, try out org-mode. There are online tutorials.
Open Source Community Culture

A great deal of Unix history is bound up with the FOSS movement.

    The GNU Manifesto and Public License
    The Cathedral and The Bazaar
    https://opensource.com/resources/what-open-source
    http://creativecommons.org/

The Soul of a New Machine and Halt & Catch Fire go well together
The Mother of All Demos
When and what was the AI Winter and the AI Spring?
The Social Network

about Facebook
Jobs biography movies

there are quite a few
Infrastructure

    What is an IP address?
    What are the reserved IP addresses?
    What is your IP address?
    How is an IP address different from an ethernet address?
    What is your ethernet adress?
    What is a domain name?
    What is a URL?
    What is the URL, domain name, and IP address for the last website you opened?
    What is HTML?
    What is HTTP?
    What is an RFC?
    What RFC defines HTTP?
    What is the IETF?
    What is RFC 2119? What piece of legislation in your country is most similar to RFC 2119?

Science Fiction
Neuromancer, William Gibson
Snow Crash, Neal Stephenson
Diamond Age, Neal Stephenson
Critical Thinking
The Wason Selection Task
Cognitive Biases
Logical Fallacies
The Three Virtues of a Programmer
Software Engineering as a Professional Career
The Clean Coder, by Robert C. Martin

makes a case for test-driven development and argues for professionalization of software engineering.
Hamming’s Art of Doing Science and Engineering: http://worrydream.com/refs/Hamming-TheArtOfDoingScienceAndEngineering.pdf
Hacker Culture
A Portrait of J. Random Hacker offers a snapshot from the early days of the American Internet, reflecting the gender and cultural biases prevalent at that time.
How To Ask Questions The Smart Way
How to ask good questions
Don’t ask to ask, just ask
Why Ask Questions in Public?
XY Problem
The Tao of IETF
Open Source

If you’re new to open source, there are plenty of guides out there:

    https://opensource.guide/how-to-contribute/

After you’ve gained some familiarity with open source and open standards in computing,
Communities of Coders

Github was once described as a social network where every post has to make the world better in some way.

    https://www.atlassian.com/git/tutorials/merging-vs-rebasing

Stack Overflow is where we go to ask for help. Don’t just be a taker, be a giver too: answer other people’s questions, and soon you’ll be learning much faster than if you were only trying to answer your own.

Go on IRC and lurk on your favourite channels; when I’m learning a new technology, watching other people struggle with problems, and watching the experienced members of the channel help out, is like a sneak preview of the issues I can expect to face in a few weeks or months myself, and a cheat code to learn the answers ahead of time.

If you already know Python, then sit on the Freenode #python channel.

If you already know Javascript, then sit on the Freenode #javascript channel. Or #typescript.

Watch newbies pop up with questions.

Watch how the experienced members of the channel deal with them.

When a new question comes up, can you get to the answer before someone else does?
Data Visualization, Graphic Design, and Architecture
Edward Tufte’s books are a classic in visual communications.
Robert Bringhurst does for typography what Tufte does for graphics.
A Pattern Language, and Christopher Alexander’s other books.

inspired the software design patterns movement.
Professional and Collegial Communication
It’s okay to say “I don’t know”.

All things considered, humans are pretty good at making guesses under conditions of uncertainty: it’s what we’re evolved to do.

But science and engineering are domains where admitting that you don’t know the answer, is a virtue – or at least, an important fact so that others do not proceed on faulty or incomplete information.

In fact, the scientific method itself could be seen as turning “I don’t know” into an engine responsible for most of the human advancement of the last four hundred years.

If we were less embarrassed about our own ignorance, we would cure it much faster. Just think of anybody who admits “I don’t know” as one of today’s lucky 10,000.

https://www.pinkelephantcomms.com/dont-know-answer/
Egoless programming requires psychological safety.

https://en.wikipedia.org/wiki/Egoless_programming

https://en.wikipedia.org/wiki/The_Five_Dysfunctions_of_a_Team

https://en.wikipedia.org/wiki/Psychological_safety
Crucial Conversations: https://www.amazon.com/Crucial-Conversations-Talking-Stakes-Second/dp/1469266822
The School vs Work Value System

20th-century style schooling imparts the following unspoken rules to those in their teens:

    The problem is a standard question which has been solved before; there is a known, correct answer.
    The problem is a slight variation on something posed to millions of other schoolchildren.
    You have to solve it on your own; working with others is considered cheating.
    Looking up the answer is considered cheating.

If you move into tech, the rules change in your twenties:

    The problem has never been solved before; if a known answer existed, you would be able to download it.
    While the problem may be a variation on a theme, you may never have been properly taught that theme.
    You are encouraged to work with colleagues to solve the problem as well and as fast as you can.
    Looking up the answer is called “research”. How do you do research? You can start by searching Google. At least twice. Or it wouldn’t be re-search. Ha, ha.

Sometimes you will encounter somebody who seems to be applying the school value system at work, applying long hours to developing their own solution to a problem which they could have just downloaded, and refusing to accept outside help because that would be cheating. Don’t be that person.

Esther Dyson likes to say: “Make new mistakes!”

In software (unless you’re working on a kata), write new code!
Domain Specific Languages

As Bjarne Stroustrup once remarked, if you’re trying to solve a problem, first design a programming language expressive enough to elegantly represent solutions in your problem domain; implement the language with an interpreter or compiler or embedded DSL; then implement the solution to your original problem in that language, which should now be simple enough for you to do “as an exercise for the reader.”

You may already know a number of DSLs: HTML; Markdown; Wiki; regular expressions; TeX and LaTeX; Makefile syntax; shell scripts. You can think of them as side quests.
Lost Arts from the Early Days of Computing

Hillel Wayne’s introduction to Decision Tables describes them as having “fallen out of common knowledge”. It is interesting to think of computing, being one of the youngest disciplines in the world relative to, say, medicine or law, as being old enough to have a history that people forget; but so it goes.
Innovation and Business
Clayton Christensen’s Disruption Framework
Wardley Maps
Doing Capitalism in the Innovation Economy, by Janeway
The Nature of Technology by W. Brian Arthur
Inside the Publishing Revolution

is a history of Adobe
Technical people can make the transition to business

What technical accomplishments did the following people achieve before doing well in the startup world?

    Reed Hastings
    Eric Schmidt
    Paul Graham

What does it take to be next on this list? Obviously, if your first name has 4 characters and your last name has 5, please go ahead and make your billions so I (Meng Wong) can follow after you. You’re the only thing standing in my way.
Apprenticeship

The Centre works with a number of senior engineers. Juniors will have the opportunity to join them in pair programming sessions.
Your Workstation

For your home setup, consider these options:

    4k is for programmers. 32” 4K UHD monitors have really come down in price: $449 for Samsung’s U32R590 as of [2020-07-16 Thu], though obviously this may be out of date by the time you read it.
    A mechanical keyboard; options include the Filco Majestouch 2 TKL BT. Get the Blue switches if you’re working solo, Brown if you’re sharing space.
    You can elevate your laptop with a Nexstand.
    Ergonomics is important. Some people have reported success with a standing desk.

Onboarding Checklist

You should see invites in your email for

    Google Drive
    Slack
    Github
    Asana
    and assuming you have an SMU email address, library.smu.edu.sg should link you through Clean Coder

Setting up your computer

We standardise on Macbook Airs as development workstations.

    Turn on FileVault
    require password or fingerprint access after sleep

If you are more comfortable working in Windows, we recommend at the least installing

    PowerShell
    Windows Subsystem for Linux

We recommend you install

    Git (and set git config --global pull.rebase true) to make life better; see https://www.atlassian.com/git/tutorials/merging-vs-rebasing for details
    Slack
    Emacs
    VS Code / Atom / Sublime Text
    Zoom
    node and npm
    python 3
    Docker
    ssh; and set up an ssh key using ssh-keygen; you will use this for Github and other logins.
    Synergy, from Symless, to span multiple computers with one keyboard/mouse; particularly useful if you’ve got multiple computers connected to one display using PBP/PIP.

On your phone, consider installing:

    Google Authenticator, because a lot of the things we do have 2FA set.
    Slack

<<<Detailed Syllabus>>> for readings and software

The following syllabus is organized by modules lasting an average of 2 weeks. About half of the material listed below is optional and not part of the official Trainee Development Plan for two reasons: one, we needed to make the official plan fit within a year, and two, the plan requested only technical skills and competencies. There’s no room in the official TDP for ethics or history or design, which is the sort of thing that one could imagine Grady Booch getting grumpy about. The extended “director’s cut” content is here, but it may well take you more than a year to get through. That seems about right, though: many master’s in CS take two years. This syllabus assumes you can read very very fast, are very very smart, and have aptitude for both theoretical computer science and real-world programming.

While most software packages come with standard tutorials and introductions, other areas involve specific academic readings that will be provided separately.

Specific readings will be assigned according to the trainee’s background, interest, and progress. Some of the books are pretty long and probably can’t be finished in two weeks; in those cases, you are expected to just skim through and read chapters of particular interest.

You need to take the lead in learning this stuff. Many resources are available through the school library – in particular, everything by O’Reillly is available, so use that as a starting point. Use Google. Find documentation. Ask your colleagues for help if you feel stuck. But you’re not stuck until you’ve tried.
Web Development: Introduction
Technical Skills and Competencies

    front-end programming on the web: Javascript
    basic web development: HTML, CSS, Node, Express
    introduction to types: Typescript
    use cases, customer personas, storyboards, mockups

Outcomes

    able to conceive and realize a simple single-page web app

Training Duration (Weeks / Months)

2 weeks, 4 meetups
The Cultural Context of Software
Technical Skills and Competencies

    read: In the Beginning was the Command Line
    read: As We May Think
    read: IFTF / Baran / Forecasting the Internet
    watch: the Mother of All Demos
    watch: Hidden Figures
    watch: the Imitation Game
    read: Neuromancer
    watch: the Matrix (1999)
    read: Licklider, Man-Computer Symbiosis
    read: Engelbart: Augmenting Human Intellect
    read: Diamond Age

Outcomes

    understand the history of computing over the past 70 years and the visions of some of the pioneers

Training Duration (Weeks / Months)

2 weeks
The Missing Semester

refer to the MIT Missing Semester course.
Technical Skills and Competencies

    learn at least one modern editor: VS Code
    learn at least one classic editor: Emacs or Vim
    literate programming in Python using Jupyter Notebook
    cryptography with GPG and SSH
    version control: using Git. Read Atlassian on merge and rebase.
    the Unix command line and pipes. tmux and screen
    regular expressions
    Windows PowerShell and structured pipes
    working with CSV, YAML, JSON, XML, and HTML at the command line
    curl to fetch
    wget -m to mirror
    ohmyzsh
    alternatives to vanilla Emacs and vim

exercise: does the website https://missing.csail.mit.edu/ contain any mention of “graphviz”? How would you answer this question:

    as a non-magic-user? (by hand)
    as a magic-user? (google site:)
    as a magic-wielder? (wget … grep -r)
    as a sorceror?

Outcomes

    comfortable operating in the Unix / Linux terminal
    know how to save and run macros in Emacs
    know how to use Emacs keybindings in the Mac environment and other editors

Training Duration (Weeks / Months)

2 weeks
Intro to Logic Programming
Technical Skills and Competencies

    SWI-Prolog
    Flora-2
    LPS by Kowalski & Sadri

Outcomes

    able to write simple programs in Prolog to perform deduction
    aware of Flora-2; able to write simple programs using frame logic
    aware of LPS; able to write simple programs involving the event calculus
    able to solve abductive problems using unification and backtracking

Training Duration (Weeks / Months)

3 weeks
Introduction to Symbolic AI
Technical Skills and Competencies

    read Godel, Escher, Bach
    work through the following CS50AI lessons: Search, Knowledge, Uncertainty, Language

Outcomes

    understand the concept of a formal language and well-formed syntax
    be able to solve planning problems

Training Duration (Weeks / Months)

2 weeks
Introduction to Expert Systems and Rule Engines
Technical Skills and Competencies

    read: British Nationality Act as a Logic Program
    tracing the logic of an expert systems in Prolog
    DocAssemble
    DMN

Outcomes

    understand backward-chaining vs forward-chaining rules
    able to build an interview in DocAssemble
    able to model a simple ruleset in a language-independent manner
    what is the difference between deductive, inductive, and abductive reasoning? Give examples of each.

Training Duration (Weeks / Months)

2 weeks
Introduction to Modal Logics
Technical Skills and Competencies

    Temporal Modal Logics: LTL, CTL: forever vs once
    Deontic Modal Logics: Must vs May
    Epistemic Modal Logics: knows vs believes

Outcomes

    understand the historical context of computational law: Genesereth
    able to compose meaningful sentences in formal modal logic and translate them to English

Training Duration (Weeks / Months)

2 weeks
Formal Methods: Introduction
Technical Skills and Competencies

    read pp 6–9 of Dramatically Reducing Software Vulnerabilities (2016) on formal methods.
    Constraint Satisfaction Problems using Z3 and PAT; work through the Z3 tutorial.
    Prolog: CLP(FD) and CLP(B)
    A tour of SMTLIB and TPTP: kinds of problems that SAT can solve
    Decision Tables as Lightweight Formal Method: read Hillel Wayne
    Types as Lightweight Formal Method

Outcomes

    able to formulate a range of problems for solving by SAT/SMT engines
    able to write native Prolog CLP(x) to solve logic problems
    able to write native Z3 to solve logic problems
    able to write native Z3 to solve simultaneous equations and other math problems
    able to interface with SAT solvers from common languages

Training Duration (Weeks / Months)

2 weeks
Formal Methods: Intermediate
Technical Skills and Competencies

    Alloy: read the book

Outcomes

    able to model and debug simple relational systems and state protocols in Alloy

Training Duration (Weeks / Months)

3 weeks
Formal Methods: Advanced 1
Technical Skills and Competencies

    TLA+

Outcomes

    able to model and verify programs and protocols in TLA+

Training Duration (Weeks / Months)

2 weeks
Formal Methods: Advanced 2
Technical Skills and Competencies

    PAT

Outcomes

    get to know PAT

Training Duration (Weeks / Months)

1 week
Introduction to Functional Programming
Technical Skills and Competencies

    Introductory Haskell
    some Haskell libraries: HXT and Aeson

Outcomes

    can write basic Haskell programs
    can parse and emit XML and JSON
    can read and modify intermediate Haskell programs

Training Duration (Weeks / Months)

4 weeks
Formal Methods: Advanced 3
Technical Skills and Competencies

    Coq or Agda

Outcomes

one of the below:

    learn a little Coq
    learn a little Agda

Training Duration (Weeks / Months)

2 weeks
Introduction to Computational Linguistics and Computational Semantics
Technical Skills and Competencies

    GF

Outcomes

    able to write application grammars in GF
    able to extend existing resource grammars in GF

Training Duration (Weeks / Months)

2 weeks
Introduction to Data Modeling with Ontologies, Types, and OOP
Technical Skills and Competencies

    OWL and the Semantic Web
    some awareness of SUMO, Cyc, and UFO-L
    some awareness of KIF and LKIF
    practice modeling the world using Haskell and GF grammars

Outcomes

    aware of the shortcomings of the RDF approach
    aware of the available open ontologies
    aware of automated inference engines as used by Protege
    able to draft a domain of discourse in a type system

Training Duration (Weeks / Months)

2 weeks
Software Modeling with UML, SBVR, DMN, and BPMN
Technical Skills and Competencies

    UML
    SBVR
    DMN
    BPMN

Outcomes

    Aware of the expressive capabilities, strengths, and weaknesses of each modeling notation.
    able to construct legal rules in CCLAW’s extension of DMN

Training Duration (Weeks / Months)

2 weeks
Other Logics and Programming Paradigms
Technical Skills and Competencies

    Communicating Sequential Processes
    the Pi Calculus
    Erlang
    two classic approaches to concurrency

Outcomes

    able to speak intelligently about concurrency
    draft a simple Erlang program

Training Duration (Weeks / Months)

2 weeks
Applications in Computational Law
Technical Skills and Competencies

    watch Ron Dolin: https://youtu.be/YHri1NdYKS0
    read: Layman Allen, Howard Darmstadter, Ken Adams
    read and work through the case studies provided by CCLAW
    learn the CCLAW L4 DSL in whatever forms it currently takes

Outcomes

    able to formalise contracts and laws
    able to write and run software to formally verify and find loopholes in contracts and laws
    able to work through a CCLAW use case as developed with industry partner

Discuss: Alice has three children. Bob has four children. Does Alice have a child? Does Alice have one child? Does Bob have two children?
Training Duration (Weeks / Months)

4 weeks
Computational Foundations
Technical Skills and Competencies

Following the Harvard CS50 syllabus:

    Understanding of binary logic and ASCII representations
    Initial familiarity with Linux and C programming
    Algorithms
    Python from first principles
    Data Structures
    SQL: databases and the concept of a normal form
    spreadsheets: vlookup(), index(match()), and query()

Outcomes

Trainee will:

    be able to view problems through a computational lens
    be able to sketch solutions to computational problems using pseudocode and architectural diagrams
    be able to do simple programming in Python
    be able to work with relational databases
    be able to work with spreadsheets at an advanced level

Training Duration (Weeks / Months)

12 weeks

    © 2020 GitHub, Inc.
    Terms
    Privacy
    Security
    Status
    Help

    Contact GitHub
    Pricing
    API
    Training
    Blog
    About

