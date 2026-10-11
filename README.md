# Python Assignment

Three solutions using Python 3. No extra packages are required.

## 1. Numbers divisible by 7 but not by 3

Run:

```powershell
py question1.py
```

Checks numbers from 2000 through 3200, inclusive. The `%` operator gives
the remainder. Matching numbers are printed as one comma-separated sequence.

## 2. Convert a list of characters into a string

Run:

```powershell
py question2.py
```

Input list: `["C", "O", "D", "I", "N", "G"]`

Output:

```text
Coding
```

`"".join(characters)` joins the characters into `CODING`. `capitalize()`
changes it to `Coding` to match the assignment example. To preserve the
original capitalization, use `print(word)` instead.

## 3. Generate a dictionary of squares

Run:

```powershell
py question3.py
```

Enter an integer for `n`. The loop adds keys from 1 through `n`, with each
value equal to the square of its key.

Example:

```text
Enter n: 5
{1: 1, 2: 4, 3: 9, 4: 16, 5: 25}
```

## Submit the assignment

1. Create or open your assignment repository on GitHub.
2. Use **Add file > Upload files** to upload `question1.py`, `question2.py`,
   `question3.py`, and `README.md`, then commit the files.
3. Copy the repository's URL.
4. Open the assignment in Google Classroom, choose **Add or create > Link**,
   paste the repository URL, and use **Turn in** to submit.
