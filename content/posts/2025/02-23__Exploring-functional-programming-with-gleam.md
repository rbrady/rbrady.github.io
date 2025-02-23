---
title: Exploring Functional Programming with Gleam
date: 2025-02-23T09:00:00+05:00
slug: /exploring-with-gleam/
description: Documenting the first steps with learning Gleam
image: images/gleam-star.jpg
caption: The Gleam Logo
categories:
  - programming
tags:
  - gleam
  - languages
  - functional
draft: false
---

# Getting Started with Gleam

Gleam is a functional programming language that runs on the Erlang virtual machine (BEAM). It has a strong type system, which helps catch mistakes before your program runs. It’s also designed to work well with Erlang and Elixir, making it great for building reliable and scalable applications.

## Who Created Gleam?

Gleam was created by Louis Pilfold. He wanted a language that combined the reliability of the Erlang ecosystem with a more structured and easy-to-use type system. Gleam takes inspiration from languages like OCaml and Elm, focusing on simplicity and performance.

## Installing Gleam

To start using Gleam, you first need to install it. Here’s how to do that on macOS and Linux.

### macOS (Homebrew)

```sh
brew install gleam
```

### Linux (via script)

```sh
curl -fsSL https://gleam.run/install.sh | sh
```

Once installed, you can check if it worked by running:

```sh
gleam --version
```

## Creating a New Gleam Project

Now that Gleam is installed, you can create a new project by running:

```sh
gleam new hello_gleam
```

This command sets up a new Gleam project with everything you need to get started. Change into your project’s directory:

```sh
cd hello_gleam
```

## Writing a Hello World Program

Let’s write a simple program that prints "Hello, world!" to the screen.

Open the `src/hello_gleam.gleam` file and add this code:

```gleam
import gleam/io

pub fn main() {
  io.println("Hello, world!")
}
```

To compile and run the program, use:

```sh
gleam run
```

You should see:

```sh
Hello, world!
```

## Wrapping Up

Gleam is a great choice for anyone interested in functional programming and reliable software. With its strong type system and the power of the Erlang VM, it’s an exciting language to explore. If you’re looking for something new and fun to learn, give Gleam a try!