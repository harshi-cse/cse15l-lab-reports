# Lab Report 5 (Week 10)

**Important links:**
- [Implementation of markdown-parse from lab 9](https://github.com/ucsd-cse15l-w22/markdown-parse)
- [Implementation of markdown-parse by our group](https://github.com/harshi-cse/markdown-parse)
- [Commands used to complete this report](https://ucsd-cse15l-w22.github.io/week/week9/)

---

**How I found tests with different results:**

---

*What I did with the provided implementation:*

After cloning the markdown-parse repository provided [here](https://github.com/ucsd-cse15l-w22/markdown-parse) for lab 9, in the `script.sh` file, I added the line `echo $file` to line 4 before the command to run MarkdownParse on the file, as below:

![Image](lab5_1.PNG)

The `script.sh` file loops through all the files in the `test-files` directory, outputting the name, followed by the result of calling the lab 9 implementation of markdown-parse on the test file, for each of the test files.

Then, in the terminal while in the directory containing the lab 9 markdown-parse repo clone, I entered the command `bash script.sh > results.txt`, which created a file that looks like this:

![Image](lab5_2.PNG)

This command stores the output of `script.sh` for each test file into a new file called `results.txt`.

---

*What I did with our group implementation:*

In my clone of the markdown-parse repository containing the markdown-parse implementation of my group, seen [here](https://github.com/harshi-cse/markdown-parse), I copied over the `test-files` directory and the `script.sh` file from my clone of the lab 9 markdown-repository (which now has `echo $file` added in to `script.sh` as previously described).

The `script.sh` file loops through all the files in the `test-files` directory, outputting the name, followed by the result of calling our group implementation of markdown-parse on the test file, for each of the test files.

Then, in the terminal while in the directory containing my group markdown-parse repo clone, similar to the step for the lab 9 markdown-parse clone, I entered the command `bash script.sh > results.txt`, which created a file that looks like this:

![Image](lab5_3.PNG)

This command stores the output of `script.sh` for each test file into a new file called `results.txt`.

---

*How I put things together to find differences:*

While in the directory containing my clone of the lab 9 markdown-parse repo, I entered the command `diff ./results.txt /Users/harshi/Documents/Github/markdown-parse/results.txt `. 

Running this command produced output as below:

![Image](lab5_4.PNG)

In the `diff` command, the first argument is the path to the `results.txt` file for the lab 9 markdown-parse implementation, and the second is the path to the `results.txt` for my group markdown-parse implementation. 

Thus for each line by line comparison of differences, the text following the `<` symbol is from the lab 9 markdown-parse implementation while the text following the `>` symbol is from our group markdown-parse implementation.

---

**First test difference:**



---

*Which implementation is correct:*

---

*Describing bugs:*

---

**Second test difference:**

---

*Which implementation is correct:*

---

*Describing bugs:*
