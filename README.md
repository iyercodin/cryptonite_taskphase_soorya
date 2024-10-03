# cryptonite_taskphase_soorya
module 2 
1.To capture the flag, open the terminal and run the program located at the root directory /. Just type /pwn and press Enter. This is called an absolute path because it starts from the root directory. Once you run the program, it will give you the flag!


2.Alright, here’s what you need to do. You’ve got a program in a folder called "challenge," and that folder is right inside the root directory (`/`). The program is called "run." The challenge is all about finding stuff using an **absolute path**, which is just a fancy way of saying you're starting from the very top of the directory structure (the root) and working your way down.

So, the absolute path for the program is `/challenge/run`. Think of it like giving directions, but starting from the main road instead of some random spot. You’re telling the computer exactly where to go, step by step.

Once you run the program using the right path, it’ll give you the flag. Basically, you’re learning how the computer organizes stuff and how to tell it exactly what to do by giving it the full path to follow. Just get that part right, and you’re golden!


3.To tackle this challenge, I’ll first open up the terminal on my computer. Once that's up, I'll check the path they gave me because knowing where I need to go is super important. I’ll use the cd command to switch to that specific directory mentioned in the challenge. After I’m in the right folder, I’ll run the program they want me to execute. If everything goes as planned, I should see the flag pop up in the terminal. If I don’t see it, I’ll double-check to make sure I typed the path right and that I’m in the correct directory. If something’s off, I’ll just go back and give it another shot. It's all about following these steps to capture that flag

4.So, here’s the deal with the Linux filesystem: it’s packed with tons of directories and files. To move around these directories, you use the `cd` command, which stands for "change directory." You just need to type the command followed by the path you want to go to.

For example, if I want to switch to a directory, I’d type something like `cd /some/new/directory`, and that would change my current location to that folder. This is important because every process (like the bash shell I’m using) has a specific "current working directory" where it hangs out. 

You might notice the `~` symbol in the prompt; that just shows that I’m currently in my home directory. When I change directories, that `~` will change based on where I am now.

For this challenge, you’ll be given a specific path. You need to use the `cd` command to navigate to that directory first before running the `/challenge/run` program again. So just remember to get to the right directory, and then you can execute the program to capture the flag. Good luck!





