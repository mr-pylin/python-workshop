# Python Changelog (3.6 → 3.14.0)

This changelog captures the major changes and important notes across Python versions from 3.6 to 3.14.0, focusing on **significant language features**, **performance improvements**, and **breaking changes**.

---

## Python 3.14.0 (October 7, 2025)

### Major Features

- **[PEP 779](https://peps.python.org/pep-0779/)**: Free-threaded Python is officially supported - removes the Global Interpreter Lock (GIL) for true multi-threading
- **[PEP 750](https://peps.python.org/pep-0750/)**: Template string literals (t-strings) for custom string processing using f-string-like syntax
- **[PEP 649](https://peps.python.org/pep-0649/)**: Deferred evaluation of annotations - improves performance and semantics of type annotations
- **[PEP 734](https://peps.python.org/pep-0734/)**: Multiple interpreters in the standard library - enables better isolation between Python interpreters
- **[PEP 784](https://peps.python.org/pep-0784/)**: New `compression.zstd` module providing Zstandard compression algorithm support
- **[PEP 758](https://peps.python.org/pep-0758/)**: `except` and `except*` expressions may now omit brackets for cleaner syntax
- **[PEP 768](https://peps.python.org/pep-0768/)**: Zero-overhead external debugger interface for CPython

### Performance & Implementation

- Experimental JIT compiler included in official Windows and macOS binaries
- Improved error messages with better traceback information
- Built-in HMAC implementation with formally verified code from HACL* project
- UUID versions 6-8 support and 40% faster generation for versions 3-5
- Incremental garbage collection improvements

### Platform & Build Changes

- Official Android binary releases now available
- Emscripten (WebAssembly) officially supported at tier 3
- PGP signatures discontinued for releases (use Sigstore instead)

---

## Python 3.13 (October 2024)

### Major Features

- **Experimental free-threaded mode** - no-GIL builds available (predecessor to 3.14's official support)
- **Improved interactive interpreter** with better REPL experience
- **iOS support** as an officially supported platform
- **[PEP 594](https://peps.python.org/pep-0594/)**: Removed many deprecated modules from the standard library
- **[PEP 703](https://peps.python.org/pep-0703/)**: Scalable garbage collection improvements

### Performance

- Significant interpreter optimizations
- Faster startup time
- Improved memory management

---

## Python 3.12 (October 2023)

### Major Features

- **[PEP 695](https://peps.python.org/pep-0695/)**: Type parameter syntax - cleaner syntax for generic classes and functions
- **[PEP 701](https://peps.python.org/pep-0701/)**: Syntactic formalization of f-strings - allows nested f-strings and better error messages
- **[PEP 709](https://peps.python.org/pep-0709/)**: Comprehension inlining - improves performance of list/dict/set comprehensions
- **[PEP 688](https://peps.python.org/pep-0688/)**: Making the buffer protocol accessible in Python code

### Performance

- 5% average performance improvement over 3.11
- Reduced memory usage for certain operations
- Better optimization of common patterns

---

## Python 3.11 (October 2022)

### Major Performance Release

- **Specializing adaptive interpreter** - up to 25% faster on average
- **Faster function calls** with optimized stack frames
- **Faster startup time** - interpreter starts quicker
- **Improved error messages** with precise error location indicators

### Language Features

- **[PEP 654](https://peps.python.org/pep-0654/)**: Exception groups and `except*` syntax
- **[PEP 673](https://peps.python.org/pep-0673/)**: `Self` type for typing
- **[PEP 646](https://peps.python.org/pep-0646/)**: Variadic generics for typing

---

## Python 3.10 (October 2021)

### Major Features

- **Structural pattern matching** (**[PEP 634](https://peps.python.org/pep-0634/)**/**[635](https://peps.python.org/pep-0635/)**/**[636](https://peps.python.org/pep-0636/)**) - `match`/`case` statements
- **[PEP 604](https://peps.python.org/pep-0604/)**: Union types with `|` operator (`str | int` instead of `Union[str, int]`)
- **[PEP 613](https://peps.python.org/pep-0613/)**: `TypeAlias` for explicit type alias declarations
- **Better error messages** with more context

### Performance

- Faster attribute access
- Optimized various built-in operations

---

## Python 3.9 (October 2020)

### Major Features

- **Dictionary union operators** (**[PEP 584](https://peps.python.org/pep-0584/)**) (`|` and `|=`)
- **String methods**: `removeprefix()` and `removesuffix()`
- **Built-in generic types** - can use `list[int]` instead of `List[int]` from typing
- **[PEP 593](https://peps.python.org/pep-0593/)**: `Annotated` type hints with metadata
- **[PEP 615](https://peps.python.org/pep-0615/)**: IANA time zone database support via `zoneinfo` module
- **Annual release cycle** adopted (changed from 18-month cycle)

### Performance

- Improved parsing speed with new PEG parser
- Vectorcall protocol optimizations for built-ins

---

## Python 3.8 (October 2019)

### Major Features

- **Assignment expressions** (**[PEP 572](https://peps.python.org/pep-0572/)**) (`:=`) - "walrus operator"
- **Positional-only parameters** (**[PEP 570](https://peps.python.org/pep-0570/)**) (`/`)
- **Self-documenting f-strings** (`f"{variable=}"`) (**[PEP 572](https://peps.python.org/pep-0572/)**)
- **`importlib.metadata`** for accessing package metadata
- **Runtime audit hooks** for security monitoring

### Performance

- 20-50% speedup for many built-in methods
- Shared memory support in multiprocessing
- Optimized list creation (12% smaller on average)

---

## Python 3.7 (June 2018)

### Major Features

- **Dictionaries preserve insertion order** - guaranteed by language spec
- **`dataclasses`** - automatic class generation with type hints
- **`contextvars`** - context variables for async programming
- **`importlib.resources`** for accessing package resources
- **`__future__.annotations`** - deferred annotation evaluation

### Performance

- Significant speed improvements across the board
- Faster method calls
- Optimized various built-in operations

---

## Python 3.6 (December 2016)

### Major Features

- **Formatted string literals** (f-strings) - `f"Hello {name}"`
- **Underscores in numeric literals** - `1_000_000` for readability
- **Variable annotations** - type hints for variables (**[PEP 526](https://peps.python.org/pep-0526/)**)
- **Asynchronous generators** and comprehensions
- **Secrets module** added for secure random number generation

### Performance

- Dict implementation rewritten for better performance and memory usage
- Faster function calls and method lookups

---

## Important Migration Notes

### End-of-Life Status

- **Python 3.6**: EOL June 2023
- **Python 3.7**: EOL June 2023  
- **Python 3.8**: EOL October 2024
- **Python 3.9**: EOL October 2025
- **Python 3.10**: EOL October 2026
- **Python 3.11**: EOL October 2027
- **Python 3.12**: EOL October 2028
- **Python 3.13**: EOL October 2029
- **Python 3.14**: EOL October 2030

### Breaking Changes to Watch

- **3.14**: Major shift with free-threading support - may affect C extensions
- **3.13**: Many deprecated modules removed - check for removed stdlib modules
- **3.12**: Comprehension scoping changes may affect some code
- **3.11**: Some typing changes and new syntax requirements
- **3.10**: Pattern matching is a major new paradigm

### Recommendations

- Always test thoroughly when upgrading between major versions
- Use tools like `python -Wd` to catch deprecation warnings
- Consider using `typing` and type checkers for larger codebases
- Take advantage of new features gradually rather than all at once

---

*Last updated: October 2025*
