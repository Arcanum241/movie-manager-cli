# movie-manager-cli
# Movie Management System

A command-line movie management application built with Python, featuring 13 operations across CRUD, search, filtering, sorting, and analytics — with persistent file storage and exception handling.

Built as part of the **Advanced Programming** course at Corvinus University of Budapest.

---

## Features

- **Add, update, delete** movies (full CRUD)
- **Search** by title, genre, director, or year
- **Sort** collection by various attributes
- **Filter** movies by genre, rating, or release year
- **Analytics** — view stats across your collection (e.g. average rating, genre distribution)
- **Persistent storage** — data is saved to file and survives between sessions
- **Error handling** — input validation and exception management throughout

## Tech Stack

- **Language:** Python 3
- **Storage:** File-based persistence (no external database)
- **Architecture:** CLI with menu-driven interface

## Getting Started

### Prerequisites

- Python 3.8 or higher

### Run

```bash
git clone https://github.com/Arcanum241/movie-manager-cli.git
cd movie-manager-cli
python main.py
```

> Replace `main.py` with whatever your entry file is named (e.g. `movie_manager.py`).

## Usage

On launch, the program presents a numbered menu. Example session:

```
=== Movie Management System ===
1. Add a movie
2. View all movies
3. Search movies
4. Update a movie
5. Delete a movie
6. Sort movies
7. Filter movies
...
Enter your choice: 
```

## Project Structure

```
movie-manager-cli/
├── main.py              # Entry point
├── movies.txt           # Persistent data file (auto-generated)
├── README.md
└── ...
```

> Update this section to match your actual file names.

## What I Learned

- Designing a CLI application with a clean menu-driven interface
- Implementing persistent storage without a database
- Writing robust error handling and input validation
- Structuring a Python project with multiple operations and clean control flow

## License

MIT

---

*Built by [Arcanum241](https://github.com/Arcanum241)*
