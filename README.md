# Disclaimer
### This guide is fully hand-written, there is zero prompting involved in the thinking or creation of this guide, i have the belief that AI could never express my own thoughts and lifestyle as good as me no matter how well he is prompted  

Everything shared in this guide is simply my own experience and views, please think for yourself and see if this guide speaks to you, if it does i would love if you shared it to make more people aware of it

# Why should YOU read this guide ?

To keep it short i have been using AI 8h+ per working day (without exaggerating) for a lot of months now, before i started trying it i've been somewhat against full agentic workflow like a lot of coders who spent years in the industry, it just felt like getting robbed of my hobby and that it just became uninteresting  

From where i stand now, i would almost never go back to normal coding, the entire point is that an agentic workflow just allows you to **10x if not 20x your "work power"**, **you will get to achieve literally ANY project you want under 6 months**, where before it could have taken more than a year or two to code extremely complex softwares  

Following this guide will allow you to (almost) fully rely on the AI to code for you, you will become a "leader/manager" rather than the programmer, you need to ditch the idea that you will code anything and rather embrace your role to dictate the AI exactly what to do  

**If you wish to reach 100% usage on all your subscriptions every month and get true work done with AI this guide is for you**  

You will learn about multiple "AI prompt hacks" as well as physiology-based ideas i use daily to improve my workflow to be able to withstand an entire full day of non-stop working, **up to 16+ hours** without "pharmaceutical aids"

I have not written a line of code manually ever since i started working this way  
You envision the code and the way you would code it, the AI codes it for you through a prompt, this is the vision you must have  

Of course i don't claim to have achieved the best way to prompt AI or use it, it is also very model dependant, for reference i have been using Cursor so i use a mix of Claude/ChatGPT/Grok (previously even Composer)  

I am making this guide from my every day usage and most likely people who actually worked in improving AI's have a better understanding on how to prompt than i do  
If you are one of them feel free to get in touch with me on [X](https://x.com/xopp1e), i'd be more than happy to discuss / improve this guide for others

Enough talking, let's get to it !

# Is there any limit to agentic coding ?

There is **almost** no limit to it, you can do things well beyond your current understanding, remember you are a "leader/manager", generally programmers own the technical skills while the leader just requests without fully understanding what it means in terms of implementations  

This is similar except even better because **YOU** might actually have the skillset and understanding that your manager did not and even if you do not it will usually never be worse than what companies used to be in terms of idea to output  

You become more of a "translator", the idea is there and you formulate it in the best way possible for the AI to understand and implement  

This is **not a reason to stop learning**, we will touch on that later in the guide

# Who can learn from this guide ?

Complete beginners as well as extremely advanced coders / AI users, you will always reshape your understanding of AI by reading through it !  

The steps are in order to setup a proper agentic workflow in your directories and how to live with AI, i will later share how i manage my time and how you can "never work" again

# Optimizing your AI workflow in 3 steps

## Step 1 (Setup)

1. Download your favorite IDE with AI integration, it can be Cursor, VS Code, Claude Code, ChatGPT, ...  
2. Think of the AI as a partner, someone who might be more skilled than you overall but may be less skilled in specific areas, which is why you must understand that proper prompting is **EXTREMELY IMPORTANT**, put yourself in the shoes of the AI on every single prompt and try to view how easy it would be to understand what your "boss" expects from you, if it isn't then refine the prompt further and give more context
3. Proper setup of the environment, this is so **underrated and the most important step** and a LOT of people do not bother with that, i can tell you this makes your experience 20x better, let's get into practice

### Practice (Rules, Skills and MCPs)

Whenever you make a new project (or integrate AI in an existing one) it is extremely important that you think of all possible "ends" of the project and how the AI could drift off from what you want, this is exactly what you want to gate  

First off start with basic things such as your coding style, this is where the **first good practice comes in** you must **almost ALWAYS** make your idea go through the lens of the AI, as i mentioned before he most likely knows more than you do in general areas (how to make good rules is the example here)  

- Prompt example: **I need you to build a code style rule from (attach your folder path/url) and apply it as a rule for this repo**  
<mark>Not the best example, continue reading</mark>

This goes for ANY rule you desire to do, rules specifically are very important to put through the AI lens  
**Ensure you review EVERY prompt you are making** because you can usually find a better way to formulate it the second time:

- Prompt example: **I need you to analyze the code style fom (attach your folder path/url) in depth and apply it as a rule for this repo**

This is a much better type of prompting, no redundancy and precising that we need depth  
Of course you also need to think if this rule stands as an user rule or as a repo rule, usually code style and so on better fits into repo's themselves if you are working on multiple projects with different code styles  

Here are example of prompts i have done in the past for rules setup:
- Prompt example: **make a new rule for tests, we need to ensure the tests that are temporary get deleted afterwards or cleaned whenever possible inside "tests\temp"
the long term tests need to sit in one directory "tests" and must be kept clean as well, keep the tests minimal if possible it must target exactly what we desire**

- Prompt example:
\
**we need to have coding style rules so that it does not go out of hand quickly, you can copy the coding style from: (repo_path)**
\
\
**just make sure we are using helpers as little as possible, we usually want code to be cleanly implemented inside their own functions, if a helper is needed ensure it is fully able to be shared from other components, and store it inside "helpers" folder or something like this  
copy the folder structure as well from (repo_path)**
\
\
**you can add good practice (language you work in, f.e C++) rules from (whatever company you like the rules of)  
its very important that the repo is kept clean, after each major change see if we can rework the code into tighter parts / less redundancy**
\
\
**its VERY important that you remember that simplicity is key and we must strive for it, we must avoid overcomplicated systems if they can be minimized while keeping the exact same outcome**

Be extensive with your prompts, ensure they are long enough and have the required context, this is how you avoid "slop" (we will talk about it right after)

For the skills you can apply the same idea, except you need better depth in your prompt:

- Prompt example: **I need you to create a skill that agents will use to work on MySQL, it is important to go in-depth with the MySQL possibilities so that the agent using this skill will always find the best way to implement something**

I am not very familiar with MySQL this is why i am being broad, remember the AI likely knows more than you do unless you are very skilled in a specific field, you may also beforehand ask what the pitfalls are or what are behavior we would not want to encounter while coding using MySQL for longevity and stability of the implementation and then you can shape the prompt for the skill around the answer the AI gives you  

I encourage the use of MCPs that actually help the environment, it is an extremely good way to add more details to your prompting / workflow and let the AI use tools that can be custom made, the main way i am using MCPs is either to help within the AI environment or let the AI interact with certain softwares on the computer  

There are so many uses to MCPs and they are extremely underrated, just make sure you do not download slop MCPs that end up being useless or burn your tokens

## Step 2 (Avoiding slop in a world full of slop)

You must have already heard or seen "vibecoded" or "ai slop", this is almost everywhere in a world where anyone can pretend to be good at something but not everyone is good at using AI correctly, far from that  

It is extremely important that you become careful with the rules / skills / MCP you implement from the web because A LOT of these can make your AI usage **MUCH WORSE** !!!

**Usually** you are better off making your own rules / skills / MCP tied to what you noticed your workflow lacks, it takes more time but evolves your workflow **so much more** in the way you exactly want it to, this is something i would 100% recommend to anybody working with AI  
For that reason i will not share my own rules or skills publicly because they are tied to what i am doing and will most likely not fit for your usage  

On that note, i will share an MCP that i made (coded in Zig to be compilable on every OS, coded strictly with a full agentic workflow, i did not write one line in this repo)  
I believe this MCP improves AI a lot over the longevity of a project, it is called [project progress](https://github.com/xop01/project-progress-mcp)  

The entire point of this MCP is that the AI will update the progress of the project as he is developing, keeping prior changes and future goals strictly documented this way he does not drift off the path you put him onto  

**Be careful, this is likely NOT an "automatic" path to completion of the project** it is not supposed to be used like this even though it might work, this MCP will allow you to work on one feature then if you decide that another feature needs attention, the AI still has a "memory" of what he was doing and what needs to be done next once that side feature is completed  

The MCP is essentially a roadmap until project completion where you can branch out of the main path and come back to it, i myself do not know the full possibilities from using this MCP, you might end up using it better than i do  

This brings the next topic, **documentation**  
It is SO UNDERRATED to keep documentations about important features of the project the AI works in, either write it yourself or let him write the documentation for you but he MUST keep easy ways to understand certain parts of the infrastructure, this way he can quickly deduce which part of the code is related to what, how it behaves WITHOUT having to read files in their entirety each time (which AI's tend to not do anymore, because of how they improved)  

An example of how useful documentation can be is [this bug fix](https://github.com/xop01/project-progress-mcp/blob/main/docs/bugs/2026-08-07-large-tree-session-timeout-opaque-errors.md) inside [project progress](https://github.com/xop01/project-progress-mcp), you can see at the end  
"Follow-ups not done yet: .gitignore / .project-progress-ignore parsing"  
I never paid attention to it but now literally two months later i can see that we could definitely use .gitignore instead of the fix applied which seems dirty for the timeout, i believe i asked the AI to specifically write down documentation about the bug  

Of course this could have been avoided in other ways, such as reading the git changes but at the time i had no git for it, i cannot push the need for documentation enough, it is just so valuable, in any shape or form

One thing to be **careful** of is that you must update these documentations otherwise you will end up with stale documentation that can mislead the AI, the [project progress](https://github.com/xop01/project-progress-mcp) has this feature implemented for you  

The [project progress](https://github.com/xop01/project-progress-mcp) MCP serves to show you what you can achieve with basically no knowledge of a programming language (i never used Zig in my life) but only an idea in mind, i don't claim it to be perfect and likely has bugs / issues and edge cases that i did not notice yet but i have been using it in every one of my repo and it helps tremendously  

An idea can now be turned into a real working program without much effort, this probably took about one or two days to create after i've noticed how bad AI's become misled over time when they are working on big projects  

The main reason a lot of projects made using AI can be called "slop" or "vibecode" is because they did not correctly setup the foundations, you need to steer the AI properly so that it follows the path you put him on as closely as possible, think of it like putting lava on both sides of the path so that he is unable to drift off  

Another good practice is to be as close as possible to the features / implementations he is working on, try to avoid being broad on your requests and instead target specific components of the implementation one by one  

This is the reason **we need skilled developers that can instruct AI properly** rather than complete newbies who just give broad directions because they do not understand the kind of programs they are working on at all  

If you are creating a project from scratch you may ask the AI for stack recommendations for your needs, this will help tremendously so you can pick the correct stack for what you are trying to build:

- Prompt example: **This project will be used to (insert what the project will do here) i need recommendations on what kind of stack would be the best and an explanation on why based on my needs: longevity, stability, scalability, performance**

You must keep in mind that you need to make the final choice, always read what he wishes to do before you actually commit to it  

Building a project from scratch with AI is the same as building a house, you must lay the foundations correctly otherwise everything will crumble and this goes for what you add in the future as well  
This was already a requirement before AI but it is now more relevant than ever  

We haven't talked about the elephant in the room yet: **Tests**  

It is **one of the most important steps of agentic workflow if not THE most important**, you MUST have proper testing suites in your projects, this is how the AI is able to validate and fact check his work  

If you do not have this you WILL end up with many bugs and have to reiterate constantly, we want to set up the AI so that he can work over long period of times alone without us having to reiterate  

The goal is for him to be able to be fully autonomous until the task is over  

We will now talk about prompting for **long tasks**, such as **clearing multiple goals at once**  
This can be extremely good so i will share to you the exact way i proceed with these:
First use plan mode, every single AI IDE has a plan mode nowadays, then describe your goals for this plan, it is very important to you specify in your prompt that after every major change he should have a test case for it  

You should detail the plan as much as possible with all the goals you require, if you need a very big one shot plan i like to use certain phrases in the prompt such as: "time does not matter, the plan has no time limit it can be done over 5+ years", you may have already noticed that **AI's have a very bad expectation of time**, i am unsure if this has been fixed or will be fixed in newer models but using such phrases will let you plan for actual features and not end up with a plan that changes 10 lines in the entire codebase  

Once this is done and you sent the plan **REVIEW IT FULLY**, it is extremely important to do that, i know you will be tempted to scroll quickly through the plan but at least understand what each phase and subphases of the plan covers so that if there are any technical mistakes you can spot them before the plan starts, it is better to iterate the plan multiple times than iterate afterwards  

Once such big plans are done you usually want to have a confirmation prompt that everything has been implemented correctly and nothing is missing or check for bugs, sometimes it is possible that they partially implement something resulting in a "temporary fix", **ensure you tell him that the audit has to be for the longevity, scalability and stability of the project** and reference the original plan in the audit prompt so he properly knows what he is auditing

## Step 3 (How AI can improve your work life and normal life)

You will actually benefit a lot from using AI in terms of lifestyle, mainly gain of time, here are my own main principles that i like to apply, all of them are equally as important:  

1. Use your time to maximize prompting  
2. Learn the stack or subject you work with
3. Know when to walk away
4. Trust in your partner
5. Translating your thoughts
6. Multi tasking
7. Use the right model for the right task

[^1]: ai-777-ctf

### 1 - Use your time to maximize prompting  

I will now explain the main principles in more details  
You need to match the activities you may do during the day with prompting, if you need more intensive prompting / tasks that the AI will not spend much time on, you should be able to stay in front of the computer  

If you are going to cook / eat / watch series / ... try to match your prompt with the time you expect him to spend on it so that when you are back either he is still working or he finished a little earlier  

The main point of using AI is to **work less hours yourself**, this does not mean you should actually have a worse work output, you can organize your time around the AI or you can make the AI organize around you as i've explained, this is what we are seeking  

Doing this technique allows you to "work" for basically infinite hours the better you get at it because it allows you to **rest** or do any other activities during while the AI works  

Ensure you do not fall into the trap of never cutting your time, since you prompt right before you do something else you might be tempted to constantly go back and try to see the status or how the AI thinks and so on, you can do this but with moderation because it exhausts you a lot and actually splits your focus time since you are essentially multi tasking  

I believe this to be bad over the long term so be careful, you might find yourself quickly addicted to it and then you will never live doing one action you will constantly feel split between two choices, do your current action or review what the AI does  

**Moderation is key as they say**

### 2 - Learn the stack or subject you work with

The more you understand the topic your project revolves around, the better you can steer and dictate the AI on what to do, this includes every side of the project, features, debugging and everything else  

Skill is the true key and will always be the true key to being better than your peers, NEVER stop learning, as much as AI feels like a "cheat code" to circumvent this, don't fool yourself it is nowhere near this  

AI when used to create projects should be used as a tool to improve your efficiency and speed NOT as a knowledge bank that you believe blindly / that you cannot fact check

The more you are able to validate and fact check the AI's doings the better your project will be, aim to at least **understand the concepts the AI is working with**, this is the bare minimum if you want to be able to uphold a project without it becoming extremely unstable / hard to scale

I find it very important for AI to have a thinking output, this is the case with Grok on Cursor  
This enables me to take notes: as he is thinking, i am already thinking about the next prompt based on his thoughts, this is why it becomes important to understand the concepts he is talking about, this way you can write proper notes preemptively and gain time  

It also enables you to be able to steer him mid-task if he is going astray, generally this should not happen but if you must steer him / cancel and reprompt, think of it as a failure on your end to make a proper prompt (if you like gaming, think of it as a loss and we are aiming for 100% winrate for the next prompts)  

### 3 - Know when to walk away

This principle goes hand in hand with principle 1, you need to know when to walk away, depending on your focus abilities you cannot truly focus more than a certain time and then you fall into multi tasking or drift away from the task at hand  
Personally after 20 to 40 minutes depending on the task i start losing "the flow state", there are also times where you might start "rage prompting" when something does not work as you intend it to  

I find it extremely important at this state to just go away from your computer and do something else (preferably while the AI works but if you are frustrated take a break otherwise your output will degrade badly)  

While i am doing something else or taking a short break it can be nice to keep a way to hear the completion sound of the task (Cursor has this, you can make an MCP as well if your IDE does not support that)  
This way you are able to simply relax for some minutes until the task is finished  

Depending on if your brain is tired or not, you may need **rest**, do NOT skip or ignore that step you SHOULD NOT push your brain way further than he can handle otherwise you risk cognitive overload / cognitive fatigue  

I will somewhat contradict myself here: ensure that you are pushing your brain a little further each time before you go rest so that you teach him to be more focused for longer periods if you desire to improve your focus  

A good way to do this would be to first note down how long you can stay truly focused for without getting distracted at all  
Once you know this you are able to set a timer/alarm to the time of your focus and increase it by 1 minute each day  

Anyways i am getting distracted by giving you techniques to improve your focus, back to the principles

### 4 - Trust in your partner

You can truly make AI become a good partner that you can rely on with strict rules and skills, you **need** to aim for this  

The more you can trust him the better you can apply the main principles  
Being able to trust him with the work you give him and come back to a good version that needs little to no iteration is key to unlocking true freedom during your day  

### 5 - Translating your thoughts

You must develop the skill to translate your thoughts and goals into better prompts, this will include giving the required context, be as precise as possible the more you detail exactly the task you want him to do the better the output  

You are able to upload pictures, link paths to other files or repos, copy paste full logs and more, there is so many things to use to populate your prompt so do it !  

There is a world where you may prompt too detailed for the task at hand when the AI could have understood it without this much detail but it is usually better to be safe than sorry, on top of it if everything is extremely precise he will take less time to pinpoint the needs of your prompt  
You will figure out the limit as you keep prompting


### 6 - Multi tasking with AI

Humans are famous to be **BAD** if not **HORRIBLE** at multi tasking, if you check out studies you will see that we decrease our abilities by a huge % every time we start multi tasking  
I would recommend that you NEVER multi task complicated tasks that require a good amount of brain power for you  

However regarding AI i would actually encourage multi tasking as long as it is done correctly (from my point of view), the way i use multi tasking in my agentic workflow is usually pair a smaller task with a larger / more complex task OR with a certain research of some type, as in prepare the context for your next prompt  

This way by the time your main prompt finished you can already continue with a new one because you have the full research / context for it ready, you save immense time by not having to wait until the AI researches  

You can also do multiple tasks that do not require you to be present or actively watch them, such as audits where the AI will come back to you with findings to act on

Multi tasking actual prompts that you will review / stay infront of the computer to read the thinking of all of them is not a good idea in my opinion because it splits your attention and can make you fatigued quickly, much quicker than you could normally sustain without multi tasking, which is not the point since we are trying to work more while spending less time on it  

At the end of the day, you may support more or less multi tasking but avoid overdoing it and do not think you are exempt from cognitive overload

### 7 - Use the right model for the right task

As you may already know, models have different trainings and they result in much different output  

It is extremely important that you find the right models for the tasks you need to do, this can be done with a bit of trial and error  

You can find tests on [YouTube](https://youtube.com) to see how good a model performs in terms of frontend (picture generation, designing)  
In terms of backend it will be harder to find, you need to test and see which one you prefer for code generation

## End of Optimizing your AI workflow in 3 steps

The entire point of this guide is that AI work should not feel like endless hours in your day, you **do not** need to stay infront of your computer to get work done properly using the methods i am using  
Whenever possible, **organize your AI around your day**, not the other way around  

This is the end of "Optimizing your AI workflow in 3 steps", i will touch on other subjects related to AI so i still encourage you to keep reading, especially if you are experienced in coding / specialized and looking for more in-depth methods on how you can deal with certain AI bottlenecks

## The current limits of AI

There are limits to what AI's can do without human interaction, this is why i referred to it as a partner, realistically he cannot do anything without you  

Your partner will tend to struggle the deeper you go into a specialized field, this is why it is required for you to learn about that specialization, this is something that currently AI's cannot do, because they are trained on human data they currently struggle/cannot learn further than what human specialists have achieved  

If you have ever tried to create a program that requires a complex understanding / skill it should already be blatant to you how much you need to babysit it, for my part it was trying to create / defeat obfuscation with it, if you let him do his own choices on such specializations he will (almost) achieve nothing relevant to today's standards  

How can we push the limit further ?  

Obviously we have to understand the concept, not only the concept but the logic of what we are trying to achieve on a deep level, you do not necessarily need to know how to code such project from start to finish without AI, which is the power of AI, we are capable of much more than we should be without it, however you must understand enough that you can inspect, edit and steer the AI to make the modifications at the right **choke points**  

I do not have a specific example to give you but if you are experienced in the field you're working on and AI does not output what you desire you should first make a list of these **choke points** and try to see if you can get more done at this level rather than prompting the AI for a certain output on a global level with a global context  

Essentially try to minimize and scope the context as much as possible to the important **choke point**

## Hypothesis / guesses / hallucinations

This is such a big problem that everybody who ever used AI knows that they tend to drift off / make only hypothesis or guesses without fact checking what they are working on  

I assume the AI has been defaulted to save tokens / his thinking on "what matters" but for certain work that needs to be tedious such as reverse engineering this breaks everything  

There is a simple phrase that i like to add to counter this, something along the lines of "verify and validate every step you take" or "verify and validate your findings to be factual"
This phrase is required almost every time you let him work on a tedious task that needs to verify the prior information to continue onto the next  

## Token consumption

I am unsure on the state of this, if IDE's found a way to fix this issue or if every MCPs/Rules/Skills are still sent on every prompt but the behavior when i started coding using AI was that each of them were sent in every prompt under the hood  

This means that your 10 MCPs with 100 commands will be sent on every prompt and it is the same for your rule with 500 phrases, if you are losing your tokens like crazy you might want to review and cut off certain MCPs/Rules/Skills or rework them  

Take it with a grain of salt because it is possible that they already implemented a better solution such as use a local AI or another workaround to avoid burning tokens and only selecting the MCPs/Rules/Skills based on your prompt  

I generally do not have any other advice to "save tokens", i have not tried many MCPs that claim to do this myself but i simply don't want my prompt to be messed up because of an MCP that i do not fully understand, such MCPs can lead to worse output from the AI and so on, if you decide to use them be careful or try to make some deeper research on your own  

Avoid blindly trusting the benchmarks they showcase, this also goes for AI models, try the model yourself and see if it fits your workflow

## AI will take your job

This may be true for most, this is why you need to **aim to be the 1% in your specialization** (or multiple !)  

AI might not take your job literally but someone who is better than you in that specialization and can prompt AI better will  
The current algorithm that AI was created on will **never** take your job because it cannot reach the understanding and knowledge that has not yet been discovered by humans  

From my understanding it is impossible for AI to "discover/invent" new knowledge the same way our brain does, it is simply trained on what humans have already achieved but cannot achieve things before humans achieve it in the future  

It is very important that people keep learning and specializing themselves, as well as keep trying to be part of the 1% in that specific field, if we fail to do this and AI research does not evolve society will not advance  

If you feel like you cannot reach the 1%, there is no better era to give it a shot: you can ask the AI to teach you certain concepts even though i believe that information shared by humans are MUCH more valuable, you are able to take a lot of shortcuts with AI learning such as letting him research resources related to this field for you and it can speed up your learning by an insane amount  

## My personal view on AI

For me it is clear that AI is simply a tool to improve your output and lifestyle but it is clear that it should not be taken as a shortcut to avoid learning, if you completely avoid learning you will stagnate no matter what, having the tool does not guarantees that you know how to use it  

I hope that companies / people who are not familiar with AI will start to understand that one skilled person with AI equals roughly 5 to 10 engineers that do not use it  

AI must be used but it must be used well, as i stated before if we are not careful it could be  possible that society will stagnate in a specific field, think "what if everybody who had this knowledge died" ?  

Currently everybody in IT schools uses AI actively because it feels too "old school" to learn without using AI which i can understand but this might come to be a real problem in the future

If we remain unable to learn or motivate the new generations without them using AI to solve all answers without learning we might actually be going towards a society where AI is simply "smarter" in terms of knowledge than everybody and everybody will stall until people actually start specializing and learning again  

Maybe by then we will achieve AGI, let's see what researchers have in store for us !

# The end

I left a flag to entertain you a little in this README, similar to how CTF's work  
If you found it before reading this you're a special person and if you did not, you read until the end which again, makes you a special person ... did you ?

I think this is about everything i wanted to share,  

Thank you for reading ! - xop