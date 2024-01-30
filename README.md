### Stopwatch

This is a stopwatch created for the technical challenge related to Shopify's summer engineering internship.

## Features

    - The stopwatch starts counting when the user clicks the start button.
    - The stopwatch stops counting when the user clicks the stop button.
    - The stopwatch resets to zero and when the user clicks the reset button.
    - The stopwatch records and displays laps when user clicks the lap button.

## File Structure

## Demo

## Learning

This was my first time using TypeScript, and found that it was a great way to make code more reliable.
Initially I explicity typed everything, and removed a few later on that could be inferred from their values - for example, for `const`

Unit testing was certainly the most difficult part of this project. It would make sense to be able to test the functionalities directly, and after some research, I decided to infer the result of the functions by the change of elements in the DOM.

Further improvements for more robust testing would be to refactor the code into modular, smaller components of code with specific functionalities could be tested individually.
