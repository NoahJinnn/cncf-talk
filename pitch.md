1. Elevator pitch
How to make the team work more consistently and efficiently? The answer is having an autonomous system. Surely, we'll work on multiple projects and automating their workflow won't be easy. Then, I found out the trio that helps us to do that easily - bash, Taskfile, mani. They provide the most convenient DX you ever seen.


2. Description
As a software engineer, recently I've faced a big challenge called: Automation! Yes, I know that's your pain point too. If you are a system administrator, a DevOps engineer, or even a software developer you surely have done some kind of work to automate your execution steps. There are so many practices out there about how to automate your work and even with different types of projects you will have different tools to use, is it a 1+n problem :D? Or you can use a single solution - Makefile, yes, probably the most popular tool and the most headache to me.

So, today I'll bring you my secret sauce of automation, which will help you do the automation tasks in more generic and not too-opinionated ways. This sauce is the combination of 2 tools that I use in my daily work, it helps me to manage and run my backend, frontend, proxy, 3rd service seamlessly and it might help you too.

If you want to automate the execution steps across your repositories because your team keeps asking each other for the commands to run other's repositories; if you don't enjoy Makefile because of its complexity, I think this talk will find you interesting.

# The beginning of the journey
- I work on a small team startup project and we have multiple repositories (backend, frontend, proxy, Docker) that need to be spun up together to run the app. 
- Each project has its own commands to start and we usually have to repeatedly ask our team members for the commands to use, even if we had our document sometimes, we still FORGOT to update it.
- So, we want to centralize those commands into a "single command". This is where our sauce was born.

# The grinding
- How to automate and document - Taskfile
- The drift
- Multiple projects?

# The decision

