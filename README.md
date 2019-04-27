# checkheaders
## Usage
```
checkheaders <license> <starting-point>
```

Check that each of the C headers and C++ headers in a project have particular
copyright notices, a particular copying permission statement, and properly
named and formatted `#include` guards.  The file `<license>` contains the
copyright notices and copying permission statement.  The directory
`<starting-point>` is the root directory of the project.  C headers are
identified by the file extension `.h`.  C++ headers are also identified by the
file extension `.h`, as well as the following file extensions:

* `.H`,
* `.h++`,
* `.hh`,
* `.hpp`, and
* `.hxx`.
