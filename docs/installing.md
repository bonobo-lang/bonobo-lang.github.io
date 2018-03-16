# Installing Bonobo
The Bonobo toolchain is written in [Dart](https://dartlang.org),
and includes everything you need to build applications productively.

## Getting the Toolchain
1. Make sure that the [Dart SDK](https://dartlang.org/install) installed, and in your `PATH`.
2. Install the toolchain by running `pub global activate --source git https://github.com/bonobo-lang/bonobo.git`.
3. The toolchain will now be available in your system as `bonobo`.

## Available Commands
Run `bonobo help` for a full list of available toolchain commands.
The following are some you might use very often:

* `bonobo compile` - Verifies and compiles a Bonobo program to C. 
* `bonobo language_server` - Runs a [Language Server Protocol](https://microsoft.github.io/language-server-protocol/) analysis server.
* `bonobo document` - Generates documentation for a Bonobo library.
* `bonobo format` - Formats a document of Bonobo code according to opinionated guidelines.