# Standards

Collection of style guides, standards and specifications for the whole project.

### Notes on making additions and modifications

* We're using git because of it's rugged versioning and commit history; It allows us
  to see when a change was made and track alterations to and authors of standards.

* Avoid binary files where possible (This means .pdf .doc .docx .odt .eps ...). Git is
  not as good at tracking changes for these and you won't have the history available
  that you would have from a text based file. Suggested formats are the simple .txt,
  .md [(markdown)](http://daringfireball.net/projects/markdown/syntax) and .tex (LaTeX)

* Making big changes - please branch off a large change and then pull request it back
  in to the Standards. This lets everyone see all the changes and prevents confusion
  because people are on different versions.


# Summary

### Programming

* All C & C++ code will follow the Firmware coding style to a tee.
* All Ruby code will use the Ruby Coding style as a guideline, with deviations allowed.

### ElectroMechanical

* All enclosures, connectors and powered devices should be:-
  - Ideally IP 67 or IP 53 as a reccomended minimum. WSC regulations require IP XXD and IP XXB for some components