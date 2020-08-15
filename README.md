# Rust Learning Path

## Where to Start your Rust Journey
- [The Rust Programming Language (RPL) Book](https://doc.rust-lang.org/book/) - This is ideal for grasping some of the core constructs of Rust, and understanding some of the main differences in the language, namely Ownership, Borrowing, Lifetimes, and to a lesser extent, error handling. You can also generate the book locally by running `rustup doc --book`
- [Rustlings](https://github.com/rust-lang/rustlings/) - This is a by-example guide to most of the same content of the RPL Book. It was developed originally by Carol Nichols, who is one of the main authors of the RPL, designed to get you familiar with the code by learning how to fix the code in each example.
- [Rust By Example](https://doc.rust-lang.org/stable/rust-by-example/) - Helpful guide to Rust concepts at a broad overview level with, well, examples.
- [The Rust Standard Library](https://doc.rust-lang.org/std/index.html) - I honestly recommend poking around through the standard library after you’ve spent a bit of time in the RPL Book or other learning materials. This will hopefully give you a high level overview of what Rust itself offers you without using any crates
- [The Rust Discord](https://discord.com/invite/rust-lang) - This is where you can find the incredible Rustlang community. The #beginners channel is absolutely fantastic at helping newcomers to the language.
- [The Rust Newsletter](https://this-week-in-rust.org/) - The weekly newsletter typically has articles relevant to beginner to advanced/mature engineers

## Guides on specific topics
- Moves, copies and clones in Rust: https://hashrust.com/blog/moves-copies-and-clones-in-rust/
- Memory Safety in Rust, Part 1: https://hashrust.com/blog/memory-safey-in-rust-part-1/
- Memory Safety in Rust, Part 2: https://hashrust.com/blog/memory-safety-in-rust-part-2/
- Building a CLI, Part 1: https://www.youtube.com/watch?v=v1L91-rCiQs
- Building a CLI, Part 2: https://www.youtube.com/watch?v=cLk47gn6A1M
- Async/Await: https://fasterthanli.me/articles/surviving-rust-async-interfaces
- How are Rust Traits different from Go Interfaces? - https://softwareengineering.stackexchange.com/questions/247298/how-are-rust-traits-different-from-go-interfaces


## Videos
- Async Interview with Without Boats: https://smallcultfollowing.com/babysteps/blog/2020/03/10/async-interview-7-withoutboats/#async-fn-main
- Steve Klabnik:
    - The talk you've been `.await`ing for: https://www.youtube.com/watch?v=NNwK5ZPAJCk
    - Rust, WebAssembly, and the future of serverless: https://www.youtube.com/watch?v=CMB6AlE1QuI
- Jon Gjengset videos:
    - Considering Rust: https://youtu.be/DnT-LUQgc7s
    - Crust of Rust - Iterators: https://www.youtube.com/watch?v=yozQ9C69pNs
    - Crust of Rust - Smart Pointers & Interior Mutability: https://www.youtube.com/watch?v=8O0Nt9qY_vo
    - Crust of Rust - Channels: https://www.youtube.com/watch?v=b4mS5UPHh20
    - Crust of Rust - Lifetime Annotations: https://www.youtube.com/watch?v=rAl-9HwD858
    - Crust of Rust - Declarative Macros: https://www.youtube.com/watch?v=q6paRBbLgNw

## Testing
- Async Testing: https://blog.x5ff.xyz/blog/async-tests-tokio-rust/

## Rust for X or Y developers
- Rust for Pythonistas: https://dygalo.dev/blog/rust-for-a-pythonista-1/

## Libraries
- Building a CLI?
    - Structopt: https://docs.rs/structopt/0.3.16/structopt/
    - https://www.youtube.com/watch?v=IVifko1fqjw
- Data parallelism: https://docs.rs/rayon/1.3.1/rayon/
- Error Handling: https://docs.rs/eyre/0.6.0/eyre/
- X or Y language Bindings:
    - Python:
        - PyO3: https://github.com/PyO3/pyo3
        - Pyo3-log: https://vorner.github.io/2020/08/08/pyo3-log.html
    - Ruby: https://usehelix.com/


## General Blog Articles in Rust
- Why Rust is a great second language: https://dev.to/blorente/why-learning-rust-is-great-as-a-second-language-5583
- I want off Mr. Golang's Wild Ride: https://fasterthanli.me/articles/i-want-off-mr-golangs-wild-ride
- How Microsoft is Adopting Rust: https://medium.com/the-innovation/how-microsoft-is-adopting-rust-e0f8816566ba
- Frustrated? It's not you, it's Rust: https://fasterthanli.me/articles/frustrated-its-not-you-its-rust
- Coming from Java/C/C++/C# : https://fasterthanli.me/articles/i-am-a-java-csharp-c-or-cplusplus-dev-time-to-do-some-rust

Ideas for projects:
- To Do CLI tool (list of things to do with commands to add and remove)