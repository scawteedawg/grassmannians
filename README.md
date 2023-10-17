# Grassmannians paper

This is supposed to be an introduction on getting this repository onto your computer, how each of us contributors can see what is changed, and then make updates. 

---
## 1 Clone this onto your computer

In your terminal, go somewhere you would like to copy this repository. Here is an example on my end:

`cd Documents/myFavoriteMathFolder` [^1]

Once you get where you'd like this repository to be saved, click the `<Code>` button to get a link to this repository. 

![copy-text-things](image-1.png)

Finally, in the terminal, type `git clone https://github.com/scawteedawg/grassmannians.git` 

You'll now see all of the files on your computer in a folder 'grassmannians' in the directory you changed to.

--- 
## 2 Adding and changing files

Now, say you've changed a few files, or you would like to add a new file, such as `boundary_maps_Gr_20_40.tex`. 

In terminal, move directories to where you have this project saved. In our above example, it would be `cd Documents/myFavoriteMathFolder/grassmannians`.

Then, to add the things you would like, type
1. `git add .` : this says to add all of your changes to the table to be ready to be sent off
2. `git commit -m "my little message about what I did"` : this is you telling git you are committing to making these changes and you can add a little message about what you edited
3. `git push` : this officially sends all the things on the table to the internet into my repository. 

--- 
## 3 Receiving my changed files
Sometimes, I'll change files before you, so it would be wise, before you start working, to get into the directory `cd Documents/myFavoriteMathFolder/grassmannians`, and then write the command `git pull` which pulls all of my changes that I put on the internet down to your local computer and merges them with your files. This way we have similarly updated things. 

Another option here is to do `git fetch` which takes all my stuff from the internet and sets it up on your computer, and then `git merge` combines our files together, locally on your computer. `git pull` is the composition `git merge` o `git pull` in the category with the single object of your terminal, and morphisms things you can type and hit enter on. (JOKE!)

---
## 4 Final things

I think that this is enough right now, but if you run into trouble, let me know. 

If you open the github page to our repository, and are curious about VSCode (the software I use to do LaTeX), type `.` in the browser and it will open a browser-level VSCode. I think it is awesome, but use whatever you would like. You'll have to install "LaTeX Workshop" by clicking on the three squares on the left side of your screen and searching for it. It's great. 







[^1]: (Note `cd` stands for change directory)