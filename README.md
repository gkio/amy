Welcome to AMY, a programming language designed for educational purposes. AMY shares many features with Rust, but with a syntax that resembles TypeScript. This language aims to provide an easy-to-learn environment to start learning programming concepts and practices.

Features:

Memory-safe: AMY is built to ensure memory safety, preventing memory-related errors such as null pointer dereferencing, buffer overflows, and other common programming pitfalls.

Object-oriented: AMY supports object-oriented programming (OOP) concepts such as inheritance, polymorphism, and encapsulation, making it easy to write complex programs and applications.

Concurrency: AMY has built-in support for concurrency, allowing developers to write parallel code that can take advantage of multi-core processors.

Jack: Jack is a package manager that makes it easy to manage and share code with others.

Syntax: AMY's syntax is similar to that of TypeScript, which makes it easy for developers who are familiar with TypeScript to get started with AMY quickly.

> For example here is an example in rust (from rust docs):

```rust
fn main() {
    fizzbuzz_to(100);
}

fn is_divisible_by(lhs: u32, rhs: u32) -> bool {
    if rhs == 0 {
        return false;
    }

    lhs % rhs == 0
}

fn fizzbuzz(n: u32) -> () {
    if is_divisible_by(n, 15) {
        println!("fizzbuzz");
    } else if is_divisible_by(n, 3) {
        println!("fizz");
    } else if is_divisible_by(n, 5) {
        println!("buzz");
    } else {
        println!("{}", n);
    }
}

fn fizzbuzz_to(n: u32) {
    for n in 1..=n {
        fizzbuzz(n);
    }
}
```

I want to achieve the same thing in AMY but with typescript syntax:

```typescript
function main() {
  fizzbuzz_to(100);
}

function is_divisible_by(lhs: number, rhs: number) {
  if (rhs === 0) {
    return false;
  }

  return lhs % rhs === 0;
}

function fizzbuzz(n: number) {
  if (is_divisible_by(n, 15)) {
    console.log("fizzbuzz");
  } else if (is_divisible_by(n, 3)) {
    console.log("fizz");
  } else if (is_divisible_by(n, 5)) {
    console.log("buzz");
  } else {
    console.log(n);
  }
}

function fizzbuzz_to(n: number) {
  for (let i = 1; i <= n; i++) {
    fizzbuzz(i);
  }
}
```
Conclusion:

AMY is a programming language that combines the powerful features of Rust with a syntax similar to TypeScript. With its memory safety and support for concurrency, AMY is a language that can help write safe and efficient code.