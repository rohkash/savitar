#### Table Of Contents

[Code of Conduct](#code-of-conduct)

[Styleguides](#styleguides)
  * [Git Commit Messages](#git-commit-messages)
  * [JavaScript Styleguide](#javascript-styleguide)
  * [HTML Styleguide](#html-styleguide)


## Code of Conduct

All developers contributing to this project abide by the [Code of Conduct](CODE_OF_CONDUCT.md) defined for this project. Violations should be reported at  [pushkarsdravid@gmail.com](mailto:pushkarsdravid@gmail.com).
Please follow these steps to have your contribution considered by the maintainers:


## Styleguides

### Git Commit Messages

* Use the present tense ("Add feature" not "Added feature")
* Use the imperative mood ("Move cursor to..." not "Moves cursor to...")
* Limit the first line to 72 characters or less
* Reference issues and pull requests liberally after the first line
* When only changing documentation, include `[ci skip]` in the commit title
* Attach issue id in the commit message for easier tracking

### JavaScript Styleguide

All JavaScript must adhere to [JavaScript Standard Style](https://standardjs.com/).

* Prefer the object spread operator (`{...anotherObj}`) to `Object.assign()`
* Inline `export`s with expressions whenever possible
  ```js
  // Use this:
  export default class ClassName {

  }

  // Instead of:
  class ClassName {

  }
  export default ClassName
  ```
* Place requires in the following order:
    * Built in Node Modules (such as `path`)
    * Built in Atom and Electron Modules (such as `atom`, `remote`)
    * Local Modules (using relative paths)
* Place class properties in the following order:
    * Class methods and properties (methods starting with `static`)
    * Instance methods and properties
* [Avoid platform-dependent code](https://flight-manual.atom.io/hacking-atom/sections/cross-platform-compatibility/)
* All files must end in a new line


### HTML Styleguide

All HTML must adhere to [HTML Standard Style](https://google.github.io/styleguide/htmlcssguide.html).

* Use HTTPS for embedded resources where possible.
* Indent by 2 spaces at a time.
    * Don’t use tabs or mix tabs and spaces for indentation.
* Use only lowercase.
* Remove trailing white spaces.
* Make sure your editor uses UTF-8 as character encoding, without a byte order mark.
* HTML5 (HTML syntax) is preferred for all HTML documents: <!DOCTYPE html>.
* Use valid HTML where possible.
* Provide alternative contents for multimedia.
* Separate structure from presentation from behavior.
* Do not use entity references.
* Use a new line for every block, list, or table element, and indent every such child element.