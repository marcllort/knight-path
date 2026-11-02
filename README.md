# Knight Path

Find the minimum number of moves between two squares using breadth-first search over a chess knight’s eight possible moves.

## Repository map

- [`src/`](src/)

## Run

Requires a JDK.

```bash
mkdir -p out
javac -d out src/*.java
java -cp out Main
```

The sample in `src/Main.java` uses an 8×8 board, starting at `(0, 6)` and ending at `(6, 0)`. Change those inputs to explore another path.
