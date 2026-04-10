# 📰 Fake Headline Generator

A fun Python project that generates random, humorous fake news headlines using Indian celebrities, public figures, and everyday scenarios!

## 🎯 About the Project

This project randomly combines **subjects**, **actions**, and **places/things** to create funny breaking news headlines. Every headline is unique and unexpected!

### Example Output
```
 BREAKING NEWS : Virat Kohli dances with at Ganga Ghat 

 BREAKING NEWS : A group of monkeys organizes a flash mob with at India Gate 
```

## 🚀 Getting Started

### Prerequisites
- Python 3.x installed on your machine

### Installation

1. Clone or download the project files.
2. No additional libraries needed — it uses Python's built-in `random` module!

### Running the Project

```bash
python fake_headline_generator.py
```

## 🕹️ How to Use

1. Run the script.
2. A random **BREAKING NEWS** headline will be displayed.
3. You'll be asked:
   ```
   DO YOU WANT ANOTHER HEADLINE?(YES/NO)
   ```
4. Type `yes` to generate another headline or `no` to exit.
5. On exit, a goodbye message is shown.

## 🧩 Project Structure

```
fake_headline_generator.py
│
├── subject        → List of famous people/groups (e.g., Virat Kohli, SRK, RCB)
├── actions        → List of action verbs (e.g., launches, celebrates, eats)
└── places_or_things → List of locations/objects (e.g., at Red Fort, during IPL match)
```

## ✏️ Customization

You can easily add your own subjects, actions, or places by editing the lists in the script:

```python
subject = ["your name here", ...]
actions = ["your action here", ...]
places_or_things = ["your place here", ...]
```

## 🌟 Features

- Fully random headline generation
- Interactive loop — generate as many headlines as you want
- Easy to extend with new subjects, actions, and places
- Beginner-friendly Python code.

## 👨‍💻 Author

Made with ❤️ and a sense of humor!

---

> ⚠️ **Disclaimer:** All headlines generated are completely fictional and created for entertainment purposes only.
