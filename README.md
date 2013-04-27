Had a need for a script to identify issues with converted config files.

The files contained information in a key=value entry per line in plain text.
The issues that needed to be found:
  - Sometimes a key was changed to a key[x].
  - Need to identify when the value of a key changed.
  - Need to identify when a key was added.
  - Need to identify wnen a key changed.

Also found an edge case where the file had incorrect keys:
  - In the same file there should not be a case where there is "key" and "key[x]".


