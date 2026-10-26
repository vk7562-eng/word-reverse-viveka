# Reverse a Word (Stack Visualiser)

A web app that reverses any word or phrase and shows every stack operation along the way.

**Live demo:** file:///C:/Users/thanish/Downloads/index%20(1).html

## DSA concept: Stack (LIFO)

A stack removes items in the opposite order they were added (last in, first out), which is exactly what reversing needs:

1. **Push** each letter of the word onto the stack, left to right.
2. **Pop** letters one at a time until the stack is empty. Each popped letter is appended to the output.

For `stack`, the letters go in as `s-t-a-c-k` and come out as `k-c-a-t-s`.

| Operation | Use in the app | Time |
|-----------|----------------|------|
| `push` | Add the next letter to the top | O(1) |
| `pop` | Remove the top letter into the output | O(1) |
| `peek` | Highlight the top of the stack | O(1) |
| `isEmpty` | Know when reversing is finished | O(1) |

The whole reversal takes O(n) time and O(n) extra space.

## Features
- Step through the push and pop phases with a plain-language explanation of each move
- Run all, restart, and load any word or phrase
- Live view of the input letters, the stack, and the output

## Run it
Open `index.html` in a browser. No install or build step.

## Tech
HTML, CSS, and vanilla JavaScript in a single file.
