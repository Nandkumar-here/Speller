# 📝 Speller

**Speller** is a command-line program that detects **misspelled words** by comparing a text file to a loaded dictionary using a **hash table**.

---

## 🚀 Features

- Loads dictionary into memory efficiently
- Parses and checks all words in a text file
- Prints all misspelled words
- Tracks performance and memory usage
- Frees all memory before exiting

---

## ⚙️ How It Works

- Words are hashed into a hash table
- The input text is scanned word by word
- Each word is checked with `check()`
- Misspelled words are printed
- `unload()` frees all memory
