🧬🧬 Genetic Algorithm – Shakespeare Monkey Theorem

  This project is a simple yet fascinating demonstration of how genetic algorithms can evolve random strings of characters toward a target phrase, inspired by the Infinite Monkey Theorem — the idea that an infinite number of monkeys randomly typing on keyboards would eventually reproduce the complete works of Shakespeare.

 Overview

  The goal of this project is to simulate evolutionary optimization in a playful way.
  A population of random strings (chromosomes) evolves over generations through selection, crossover, and mutation until it perfectly matches a target sentence (for example: "To be or not to be").

  This concept is commonly known as the Shakespeare Monkey Problem, and it beautifully illustrates how randomness, guided by selection pressure, can lead to order and intelligent results over time.

⚙️ How It Works

  Initialization
    A population of random strings is generated, each with the same length as the target phrase.
  
  Fitness Evaluation
    Each individual is evaluated based on how many characters match the target phrase (character-by-character similarity).
  
  Selection
    The best individuals (highest fitness) are selected to reproduce.
  
  Crossover
    Two parents combine parts of their strings to create offspring.
  
  Mutation
    Random characters are occasionally altered to maintain diversity in the population.
  
  Termination
    The algorithm repeats until an individual exactly matches the target phrase or a maximum number of generations is reached.


▶️ Running the Project
  Option 1 – Using Jupyter Notebook
  
  Clone the repository:
  
  git clone https://github.com/<your-username>/genetic-algorithm-shakespeare.git
  
  
  Open the notebook:
  
  jupyter notebook "Genetic Algorithm (Shakespeare Monkey Theorem).ipynb"
  
  
  Run all cells to see the algorithm evolve the population step by step.
  
  Option 2 – Running as a Python Script
  
  If you prefer, you can export the notebook as a .py file and execute it directly:
  
  python monkey_theorem.py
  
  ----- Example Output
  
  Generation 0: Evgmzstji pxt!wzc
  Generation 27: To bq or nol to bz
  Generation 36: To be or not to be



🧩 Inspiration

This project was inspired by the Infinite Monkey Theorem and is often used as a pedagogical example to teach:

Genetic algorithms

Natural selection concepts

Evolutionary computation principles

👨‍💻 Author

Gabriel Luiz Limeira Barreto


