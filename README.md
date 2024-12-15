# AoC-template
Use this template to generate environment for solving [Advent of Code](https://adventofcode.com/) puzzles

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

### Utils
- `nerdamer` – Used for solving equations.
```
const nerdamer = require('../../utils/nerdamer');
```
[link to original repository](https://github.com/evanw/nerdamer)

### Debugging
- In `[day].txt` you can find the input for the problem
- Dirname and input filename for the day less than 10 should be prefixed with `0` for right alignment
- To debug and view results when solving the problem, you can use `nodemon days/[day]`
- You can also use `node days/[day]` to run the code without the need to restart the server
