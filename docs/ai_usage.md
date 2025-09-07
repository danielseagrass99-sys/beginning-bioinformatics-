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
- Tool/model & version: Chat GPT 5
- What I asked for: Using "count" in Python, assist me to solve this by Return: Four integers (separated by spaces) counting the respective number of times that the symbols 'A', 'C', 'G', and 'T' occur in s
.
- Snippet of prompt(s): def run():
    # Option 1 — read from a file named 'rosalind_dna.txt' in the same folder:
    # with open("rosalind_dna.txt", "r") as f:
    #     s = f.read().replace("\n", "").strip()

    # Option 2 — paste your DNA string directly here:
    s = input().strip()  # works with Rosalind’s stdin too

    A = s.count('A')
    C = s.count('C')
    G = s.count('G')
    T = s.count('T')

    print(A, C, G, T)
- What I changed before committing: This was then converted to a file doc to be uploaded easier
- How I verified correctness (tests, sample data): I then ran this with the orginal data set to ensure the code was correct

- Tool/model & version:
- What I asked for:
- Snippet of prompt(s):
- What I changed before committing:
- How I verified correctness (tests, sample data):

# AI Use Log Rosalind #7
- Tool/model & version:ChatGPT 5
- What I asked for: Help me understand the code for this problem with step by step instructions
- Snippet of prompt(s): Save your input (the DNA string) in a file, e.g. input.txt, then run:

python transcribe.py < input.txt


Or paste directly after running:

python transcribe.py
# paste DNA here, then press Ctrl+D (macOS/Linux) or Ctrl+Z then Enter (Windows)
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
- What I asked for: How do I run this sequence in Python and how do I input the data into the code
- Snippet of prompt(s): Option 1: Input from a FASTA file (recommended for Rosalind)

Open a text editor.

Paste your dataset, for example:

>Rosalind_6488
GAATGTAGGGCCAATTCTGCCTGATTTGACTGGTCGTGGTAACTGAGCCCTTCGCTGCAA
...
>Rosalind_5335
AATGAATTTTTACTAGTATAGCAAGCGCCTGAACCAAGGTGAGCATCGTTCAGCTGACCC
...


Save it as input.fasta in the same folder as gc_content.py.

Run:
- What I changed before committing: I saved the data set as a file and then uploaded it following the instructions 
- How I verified correctness (tests, sample data):
