# AI Use Log Rosalind #3
- Tool/model & version: Chat GPT 5
- What I asked for: explain this loop code to me a, b = 100, 200 total = 0 for i in range(a, b + 1): # b+1 so b is included if i % 2 == 1: total += i print(total)
- Snippet of prompt(s): for i in range(a, b + 1):   # b+1 so b is included
range(a, b + 1) generates numbers starting at a and ending at b.

In Python, range stops just before the second number, so we use b + 1 to make sure b is included.

So here, i will take on every number from 100, 101, 102, … , 200.
- What I changed before committing: I changed the numbers for Rosalind 3 to include the new downloaded data
- How I verified correctness (tests, sample data):

- # AI Use Log Rosalind #4
- Tool/model & version: Chat GPT 5
- What I asked for: use the run function to only read the even number lines of this text file
- Snippet of prompt(s): def run():
    # open the file (place it in the same folder as this script)
    with open("jabberwocky_side.txt", "r") as f:
        for lineno, line in enumerate(f, start=1):  # line numbers start at 1
            if lineno % 2 == 0:  # keep only even lines
                print(line.strip())
- What I changed before committing: Saved into a file before Rosalind submission
- How I verified correctness (tests, sample data): 

- # AI Use Log Rosalind #5
- Tool/model & version: Chat GPT 5
- What I asked for: Use this code to find the number of iterations in this text file
- Snippet of prompt(s): s.split() turns the string into a list of words, separated by spaces.

counts = {} creates an empty dictionary to store counts.

Loop through each word:

If the word is already a key, increment its count.

If not, add it with count 1.
- What I changed before committing: I changed the data set to the Beatles song and ran the code again in ChatGPT. I also needed to upgrade to GPT Plus 
- How I verified correctness (tests, sample data):

# AI Use Log Rosalind #6
- Tool/model & version:
- What I asked for:
- Snippet of prompt(s):
- What I changed before committing:
- How I verified correctness (tests, sample data):

- Tool/model & version:
- What I asked for:
- Snippet of prompt(s):
- What I changed before committing:
- How I verified correctness (tests, sample data):

# AI Use Log Rosalind #7
- Tool/model & version:
- What I asked for:
- Snippet of prompt(s):
- What I changed before committing:
- How I verified correctness (tests, sample data):

# AI Use Log Rosalind #8
- Tool/model & version:
- What I asked for:
- Snippet of prompt(s):
- What I changed before committing:
- How I verified correctness (tests, sample data):

# AI Use Log Rosalind #9
- Tool/model & version:
- What I asked for:
- Snippet of prompt(s):
- What I changed before committing:
- How I verified correctness (tests, sample data):
