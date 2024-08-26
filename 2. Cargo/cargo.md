Cargo is Rust build system and package manager. It manages Rust projects beauce it handles a lot of tasks for you.

When you make a new project using command cargo new project_name, it creates a new project with a Cargo.toml(Tom's Obvious Minimal Language) file and a src folder.


In rust packages of coes are called as crates.
The default build be a debug build but not a production build

Cargo.lock contains exact version of dependencies. It is siminal to package-lock.json in node.

Use cargo run to auto run the file without going inside the src folder. Auto compile and auto run.

Cargo is super smart.

Also $ cargo check to check if the code is working.