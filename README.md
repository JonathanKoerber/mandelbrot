## Rust CLI Mandelbrot Set
-----

I am working through Programming Rust, 2nd Edition(Programming Rust, 2nd Edition, n.d.) to learn how to work with the Rust programming language. Chapter 2 uses the following code to show several core Rust features. Usually, I don't hold on to code I have copied from a textbook, but this program produces the following image, which is just too cool!

------
To compile, run:
`cargo build --release`

Run program with:
`target/release/mandelbrot mandel.png 4000x3000 -1.20,.35 -1,0.20
`
### Mandelbrot Set
-----

![Mandelbrot Set](mandel.png)

-----

Please just be careful how large you make the image since it requires a lot of computation. 

Programming Rust, 2nd Edition. (n.d.). Retrieved June 24, 2023, from https://learning.oreilly.com/library/view/programming-rust-2nd/9781492052586/
