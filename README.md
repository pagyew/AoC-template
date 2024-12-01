# AoC-template
Use this template to generate environment for solving [Adventure of Code](https://adventofcode.com/) puzzles

## How to use

### Setup
1. Create `.env` file in the root of the project to store your session cookie and year
2. Add `AOC_SESSION=YOUR_SESSION` to your `.env` file
3. Add `AOC_YEAR=YEAR_YOU_WANT_TO_SOLVE` to your `.env` file

### Running
You can run the script using the command `node go [next|last]`
  - `next` will create a new directory for the next day and open the file
  - `last` will open the last day's file

### Debugging
To debug and view results when solving the problem, you can use `nodemon days/[day]/[day].js`
