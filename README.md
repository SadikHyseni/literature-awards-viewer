# Literature Prize Menu Application (Java 8)

This is a Java 8 console application developed in NetBeans that allows users to interact with a dataset of literature prize winners (e.g., Nobel laureates) from 1901 to 2022. The dataset is read from a file (`literature-prizes.txt`), and the program provides a text-based menu for users to explore the data.

---

## Project Features

- Reads and parses `literature-prizes.txt` on startup
- Represents domain data using `LiteraturePrize` and `Laureate` classes
- Aggregates data in memory (no repeated file access)
- Console-based interactive menu with the following options:
  - `List`: Show all years where prizes were awarded
  - `Select`: View details of prizes for a selected year
  - `Search`: Search laureates by name (partial match)
  - `Exit`: Close the program



