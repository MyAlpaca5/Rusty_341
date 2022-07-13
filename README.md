## Rusty 341
Rusty 341 contains solutions written in Rust for the machine-graded and lab assignments for CS341.

It's a personal practice project meants for me to get familiar with system programming and get comfortable with Rust.

**Contributions are welcome!!**

## Motivation
[CS341](https://cs241.cs.illinois.edu/), former CS241, is an introductory System Programming course offered in the University of Illinois Urbana-Champaign.

It was a fruitful journey for me as a graduate Lab TA for this course, I consolidated what I have learnt and still remembered from my undergraduate study while picked up a few new things along the way. However, it got frustrating sometimes to help students debug their solutions, because all of the MPs and Labs were required to solved in C and students were constantly failed the auto grader due to memory related issues or poorly implemented data structures.

Recently, I get interested in Rust and I think this is a great opportunity for me to learn more about Rust by solving some of the assignment using Rust. What's more, each assignment has clear objectives and solid test cases, it is easy for me to adopt Test Driven Development strategy when working on it.

## Disclaimer
- Those solutions are meant for personal practices, therefore, they may not be efficient or idiomatic.
- For CS341 students, please don't just translate the solutions presented in here into C, they may simply not work for AG.
    - I may use different test cases than those of AG may use.
    - Due to the ownership model in Rust, I don't have to free/drop the resources manually most of the time, but you may get memory leak if you don't free the recourses in C.
    - Rust has rich container types in standard library, such as Vector, there may not be native alternative in C.
