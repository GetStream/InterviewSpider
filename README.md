# InterviewSpider

This is a Go assignment about creating a simple webscraping spider. This program
should be able to scrape a website and generate a graph of all pages that are
connected via the `<a>` HTML tag.

## Requirements
- Create a new repo on github with your code (DON'T fork this one)
- The README of the repo should contain instructions on how to compile and run
  the program, e.g: 

```bash
go run main.go https://getstream.io
```

- Generate a graph internally and output some interesting statistics
- Scrape pages concurrently
- Make search depth configurable from the command line
- Keep searching until any of the following conditions is true:
    - User interrupts with Ctrl+C
    - All nodes in the current search depth have been visited

## Bonus points
- Display the graph in a nice way
- Do it fast
- Exit the program cleanly on Ctrl+C

## Final notes
- If something about these requirements is not clear feel free to ask
