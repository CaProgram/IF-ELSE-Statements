# Avengers Character Quiz

## Purpose
This is a simple Python-based quiz that helps users determine which character from the *Avengers* franchise they are most like based on a few fun questions. The code takes user input and, depending on the answers, assigns a character from the *Avengers* universe.

## How It Works
The program asks the user a series of yes-or-no questions, and based on their responses, it prints out which *Avengers* character they resemble. The character determination is based on the following questions:

1. **Do you like the color green?**
   - If yes, the user is assigned the Hulk.

2. **Do you think building robots is cool?**
   - If yes, the user is assigned Iron Man.

3. **Do you like traveling through time?**
   - If yes, the user is assigned Captain America.

4. **Are you super strong?**
   - If yes, the user is assigned Thor. If not, the quiz concludes that the user might not resemble any Avengers character.

## Code Explanation
1. **Input Gathering:** 
   The program asks the user questions about their preferences and stores their answers as variables (`likeGreen`, `IronIsCool`, `TimeTravel`, `Strong`).
   
2. **Conditional Logic:**
   The program uses `if` statements to check the answers. Depending on the responses, the program prints out the name of the corresponding character.

3. **Output:**
   Based on the user's input, the program prints which Avenger they are most like.

## Example Output

```plaintext
Which character are you from 'Avengers?'

Answer these questions and let's find out.

Please use Y or N for yes and no.
Do you like the color green?: Y
You must be the Hulk!
Do you think building robots is cool?: N
Do you like traveling through time?: N
Are you super strong?: Y
You have got to be Thor!
