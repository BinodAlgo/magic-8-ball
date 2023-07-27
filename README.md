# Magic 8-Ball

The Magic 8-Ball is a popular toy developed in the 1950s for fortune-telling or seeking advice. The Python program `magic8.py` simulates the Magic 8-Ball by answering any "Yes" or "No" question with a different fortune each time it is executed.

## How to Use

1. Clone the repository or download the `magic8.py` file to your local machine.
2. Open a terminal or command prompt and navigate to the directory containing `magic8.py`.
3. Run the program using the following command:

```bash
python magic8.py
```

## Tasks

### Setting Up

1. In `magic8.py`, declare a variable `name` and assign it to the name of the person who will be asking the Magic 8-Ball.

2. Next, declare a variable `question`, and assign it to a "Yes" or "No" question you'd like to ask the Magic 8-Ball.

3. We want to store the answer of the Magic 8-Ball in another variable, which we'll call `answer`. For now, assign this variable to an empty string.

### Generating a Random Number

4. In order for the answer to be different each time we run the program, we will utilize randomly generated values. Import the `random` module at the top of `magic8.py`:

```python
import random
```

5. Create a variable called `random_number`, and assign it the value of the randomly generated number using `random.randint(1, 9)`, which will generate a random number between 1 (inclusive) and 9 (inclusive). Optionally, you can add a print statement to check the value of `random_number`.

### Control Flow

6. Implement the core logic of the program using an if/elif/else statement to assign different answers for each randomly generated value. For each possible value of `random_number`, assign the corresponding fortune to the variable `answer`.

7. Continue writing `elif` statements for each of the remaining phrases for the values 2 to 9.

8. Add an `else` statement that will set `answer` to the string "Error" if the number was accidentally assigned a value outside of our range.

### Displaying the Result

9. Print the asker's name and their question in the following format:

```
[Name] asks: [Question]
```

10. Print the Magic 8-Ball's answer in the following format:

```
Magic 8-Ball's answer: [Answer]
```

### Optional Challenges

Feel free to try the following optional challenges to enhance the program:

12. Add more possible answers to the program by increasing the range of randomly generated numbers and adding additional `elif` statements for each new answer.

13. Improve the formatting of the output when the user does not provide a name. If the name is an empty string, print only the question.

14. Handle the case when the question is an empty string. If the user does not provide any question, print a message to the user.

## Example Output

```
Joe asks: Should I do this project?
Magic 8-Ball's answer: Yes - definitely
```

```
Asks: Will I win the lottery?
Magic 8-Ball's answer: Outlook not so good
```

```
Alice asks: 
Magic 8-Ball's answer: Please provide a question.
```

Feel free to explore and modify the `magic8.py` file to add more features and improve the user experience. Enjoy your interactions with the virtual Magic 8-Ball!
