# Word Counter in Go

My first CLI tool built with Go! A simplified version of the Unix `wc` command that counts words, lines, or bytes from standard input.

## Usage

```bash
# Count words (default)
echo "hello world" | ./wc_go

# Count lines
echo -e "line1\nline2\nline3" | ./wc_go -l

# Count bytes
echo "hello" | ./wc_go -b
```

## What I Learned

<!-- TODO: Add your personal reflections here! Some prompts to consider: -->
<!-- What surprised you about Go? -->
<!-- What was easy/hard compared to other languages you know? -->
<!-- What would you do differently next time? -->

### Interfaces (`io.Reader`)

<!-- What did you learn about Go interfaces? The count() function accepts an io.Reader, which lets it work with stdin, files, buffers — anything that implements Read(). -->

### CLI Flag Parsing

<!-- What was your experience with the `flag` package? How does it compare to argument parsing in other languages? -->

### Testing in Go

<!-- What did you learn about writing tests with the `testing` package? Did using bytes.Buffer as a fake stdin feel natural? -->

### Scanner and Split Functions

<!-- What did you learn about bufio.Scanner and how ScanWords/ScanLines/ScanBytes work? -->

## Running Tests

```bash
go test ./...
```
