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
  - Write your solve function in `solve.js` (it's open automatically when you run the script) and return answer

### Debugging
- In `[day].txt` you can find the input for the problem
- To debug and view results when solving the problem, you can use `nodemon days/[day]/[day].js`
- You can also use `node days/[day]/[day].js` to run the code without the need to restart the server
- Directory name for the day less than 10 should be prefixed with `0` for right alignment
