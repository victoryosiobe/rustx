# RUSTX

Starting out with an android, and needing to learn rust, here's how it goes.

Right now, I can do some hello world, but how did i get there?

There are ton of free resources to learn rust from, but it's how to get started that is the burden.

___

**Installion:** On your ready terminal, Termux from f-driod, As I'm using Android, just run `pkg install rust`.

Let rust install, but don't go use other methods to install, you could mess things up and then turn to delete and start again.

Now go to your coding folder, make a directory of any name, then create a file of any name ending with the rust extension, **rs**.

In that file, write this code in it.

```rust
fn main() {
    println!("Hello, world!");
}
```

Too lazy, coppppyyyy & paste.

When done, depending on your editor, save it, and in your terminal, run in that same directory, `rustc your_file_name.rs`

This will compile your hello world code.

Done, then, run `./your_file_name`. Bash would run this compiled form of your code to get an output.

Vvvoila!!!

___


But If you didn't get to this stage, Let me help.

If you came across some `cannot find "libLLVM.so" ...` error, simply run `pkg install libxml2`.

Compiling should be good after that.

If you are running the compiled file, and getting `permission denied` error, this wouldn't be because of the directory you are executing the compiled code from.

Android, due to security reasons won't allow you to execute files anywhere—except from app levels.

So if you had your code folder in `/storage/emulated/0/...` or just about anywhere and you get the errror, you'd have to move it to the termux app level storage, so you can execute from there.

That would be `cd ~`, or `$HOME` directory.

When you run it again from there, you'd definitely get your output. [Look this up](https://stackoverflow.com/a/65480966/20313640), if you don't understand.

....Learning mmorree....
