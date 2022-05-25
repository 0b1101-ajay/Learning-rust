                                                                    Day-1
   **Writing and Running a Rust Program**
   
   make a new source file and call it main.rs. Rust files always end with the .rs extension.
   Now open the main.rs file you just created and enter the code written in Day-1 main.rs file.
   Save the file and go back to your terminal window. 
   On Linux or macOS, enter the following commands to compile and run the file:
         
         $ rustc main.rs
         $ ./main
           Hello rust (Output)
         
         
         On Windows, enter the command .\main.exe instead of ./main:
         > rustc main.rs
         > .\main.exe
           Hello rust (Output)
           
           
   **Cargo**
          
   Cargo is Rust’s build system and package manager. Most Rustaceans use this tool to manage their Rust projects because Cargo handles a lot of tasks for us, such as        building code, downloading the libraries our code depends on, and building those libraries.
         
   **Using Cargo to create above rust project**
   
   Let’s create a new project using Cargo and look at how it differs from our original “Hello rust” project. Navigate to Day-1 folder(or wherever you decided to store 
   your code). Then, on any operating system, run the following:
   
    $ cargo new using_cargo
    $ cd using_cargo
    
   The first command created a new directory called using_cargo. We’ve named our project using_cargo, and Cargo creates its files in a directory of the same name.
   In the using_cargo directory Cargo has generated two files and one directory for us: a Cargo.toml file and a src directory.
  **Use cargo run to compile the code and then run all in one command**


    $ cargo run
    Finished dev [unoptimized + debuginfo] target(s) in 0.0 secs
    Running `target/debug/hello_cargo`
    Hello, world! (Output)
