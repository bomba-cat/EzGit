# EzGit
Make git easier on Linux !

# Install Instruction
- ```Install git```
- ```git clone https://github.com/xk-rl/EzGit```
- ```cd EzGit```
- ```chmod +x ezgit```
- ```sudo cp ezgit /bin``` (system search path)

After this the ezgit script is in your system seach path and you can execute it inside your terminal using: ezgit

# Feautures
- Push: Yes
- Pull: Yes
- Commit: Yes
- Init: Yes
- Stash: Yes
- Auto fill token and user: Yes
- Basic Features: Planned
- Some QOL Features: Planned
- Other stuff: Probably no, maybe if the idea is good

Working on bringing everything git has to a more easy to use userface for beginners.

# Inspiration
I was learning assembly and always kept the scripts i made updated on my github and then came to the conclusion that using git was annoying when having to type multiple commands just to add my scripts on my github and then came to the idea, why not make a script which makes using git easier and more fun as all i have to to is type in ```ezgit``` and then select number 1 and it would do everything automatically. Then i realized why not make it so my script saves my logindata and automatically fills it in whenever i push? So thats what i implemented too and now im here. I also made it so ezgit saves the logindata inside the /bin directory so i can go in my shell and just type in ```ezgittoken``` and it would show me my logindata. For this to work the script requires sudo so now im working on a way to add it inside the /home directory so it would be possible to run this script sudo free.
