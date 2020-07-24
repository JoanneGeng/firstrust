# learn rust
> https://doc.rust-lang.org/book/title-page.html

## Ownership
Here are some of the types that are Copy
* All the integer types, such as u32.
* The Boolean type, bool, with values true and false.
* All the floating point types, such as f64.
* The character type, char.
* Tuples, if they only contain types that are also Copy. For example, (i32, i32) is Copy, but (i32, String) is not.

## References and Borrowing