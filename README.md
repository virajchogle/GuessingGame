# Guess the Number Game

This is a simple **Guess the Number** game implemented in Rust. The program generates a random number between 1 and 100, and the user has to guess it. Feedback is provided after each guess, indicating whether the guess is too low, too high, or correct.

---

## Features

- **Random Number Generation**: Uses the `rand` crate to generate a secret number between 1 and 100.
- **User Input**: Prompts the user for guesses and handles invalid inputs gracefully.
- **Colorful Output**: Uses the `colored` crate to color feedback messages for better user experience:
  - Red for "Too small" and "Too big".
  - Green for "You win!".
- **Looping Mechanism**: Allows the user to keep guessing until they correctly identify the secret number.

---

## Prerequisites

- **Rust**: Make sure you have Rust installed. You can download it from [rust-lang.org](https://www.rust-lang.org/).
- Required crates:
  - `rand` for generating random numbers.
  - `colored` for styled output.

To include these dependencies, add the following to your `Cargo.toml` file:

```toml
[dependencies]
rand = "0.8.5"
colored = "2.0"

