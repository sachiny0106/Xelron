# Word Count Task

Read the file at `/app/input.txt` and compute the following statistics:

1. **Total word count**: Count all words (separated by whitespace)
2. **Unique word count**: Count unique words (case-insensitive, e.g., "Hello" and "hello" are the same word)
3. **Line count**: Count the number of lines in the file
4. **Character count**: Count all characters including whitespace

Write the results to `/app/output.txt` in exactly this format:

```
Words: <count>
Unique words: <count>
Lines: <count>
Characters: <count>
```

Replace `<count>` with the actual numeric values. Each statistic should be on its own line.

**Example:**

If the input file contains:
```
Hello world
Hello universe
```

The output file should contain:
```
Words: 4
Unique words: 3
Lines: 2
Characters: 26
```
