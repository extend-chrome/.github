# Please include a repro

<some text explaining why we need a minimal reproduction repo: too much time, effort, etc...>

## How to create a minimal reproduction

1. Create a sample repo on GitHub
2. Demonstrate the problem, and nothing but the problem. If the app where you're experiencing the issue happens to use Gulp, I don't care, unless the problem involves Gulp. Remove that stuff. Whittle it down to the *bare minimum* of code that reliably demonstrates the issue. Get rid of any dependencies that aren't *directly* related to the problem.
3. Install all your dependencies to `package.json`. If I can't clone the repo and do `npm install && npm run build` (or similar – see point 4) to see the problem, because I need some globally installed CLI tool or whatever, then it's not really a minimal reproduction.
4. Include instructions in the repo, along with a description of the expected and actual behaviour. Obviously the issue should include information about the bug as well, but it's really helpful if `README.md` includes that information, plus a link back to the issue. If there are any instructions beyond `npm install && npm run build`, they should go here.

## Better still, file a test case or a fix!

Maintainers will *love* you if you submit test cases and fixes via pull requests. Generally, if it's a non-trivial or controversial fix then you should probably just file the test case and discuss the solution before adding code, but straightforward fixes (that pass CI and follow the project's code style!) are hugely appreciated.

## Thank you

<say thanks for putting together a repro>
