# CSCI 2600 Git Practice

A small Java example for practicing Git collaboration and merge conflict resolution.

## Run

```bash
mkdir -p build
javac -d build Hello.java
java -cp build Hello
```

Expected output:

```text
Hello, class!
```

## Collaboration exercise

After this initial version is published to GitHub, both participants should clone
the repository before either person changes the greeting in `Hello.java`.
Each participant then changes the same greeting differently. One participant
pushes first; the other attempts to push, pulls to merge, resolves the conflict,
and pushes the agreed final greeting. Both participants then synchronize and
compare their working trees and commit IDs.
