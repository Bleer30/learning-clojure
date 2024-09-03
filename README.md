# Introduction to Clojure: Your First "Hello World"

Clojure is a functional programming language that runs on the JVM (Java Virtual Machine). It's known for its simplicity, expressiveness, and powerful immutable data structures.

## Installing Clojure

Before you start programming in Clojure, you'll need to install it on your system.

### Installation with `brew` (macOS/Linux)

If you're on macOS or Linux, you can install Clojure using Homebrew:

```bash
brew install clojure/tools/clojure
```

### Installation on Windows
For Windows, you can install Clojure using the choco (Chocolatey) package manager:

```bash
choco install clojure
```

You can also follow the official installation instructions at https://clojure.org/guides/getting_started.

## Your First Program: "Hello World"
# Step 1: Create a Clojure File
First, create a file with the .clj extension in your preferred text editor. Name it hello_world.clj.

```bash
touch hello_world.clj
```

## Step 2: Write the Code
Open the hello_world.clj file and write the following code:

```clojure
(ns hello-world.core)

(defn -main []
  (println "Hello, World!"))
```

## Code Explanation
- (ns hello-world.core): Defines the namespace, which is a way to organize your code in Clojure.
- (defn -main [] ...): Defines a function named -main that takes no arguments.
- (println "Hello, World!"): Prints the text "Hello, World!" to the console.

## Step 3: Run the Program
To run the program, open a terminal and enter the following command:

```bash
clojure hello_world.clj
```
This will execute the code, and you should see the following output in your terminal:

```bash
Hello, World!
```
Congratulations! You've written and run your first Clojure program.

## What Next?
Now that you know how to write a simple "Hello World" in Clojure, you can explore more about the language. Here are some ideas:

- Basic Syntax: Learn about the basic syntax, including lists, vectors, maps, and functions.
- Immutability: Discover how Clojure handles immutability and why it's important.
- REPL: Get familiar with the REPL (Read-Eval-Print Loop) to experiment with code in real time.
You can dive deeper by exploring the official Clojure documentation here.

I hope it serves as a useful starting guide for newcomers to Clojure to start writing their first program. Best of luck!
