# Java Number Guessing GUI - Interactive Swing Application

An event-driven desktop application built in Java Swing that generates a randomized target integer within a defined search space (0–1000) and provides dynamic visual feedback based on user input proximities.

## Core Features & Architecture

* Graphical User Interface: Built using standard Java Swing components (`JFrame`, `JTextField`, `JButton`, `JLabel`) with dynamic background color transitions based on feedback states.

* Proximity Evaluation Engine: Calculates numerical distance between target values and player guesses to dynamically determine "warmer/colder" temperature metrics and high/low directional hints.

* Key & Event Bindings: Configured `ActionListener` and `KeyListener` mappings allowing submission via explicit button interaction or keyboard inputs (`Enter` key).

* Replay Loop Management: Dynamic state resets that allow continuous play cycles without restarting the application lifecycle.

* Standalone Executable: Pre-packaged `.exe` distribution bundled with UI image assets for native operating system execution.

## Key Technical Focus Areas

* Event-Driven Programming: Handling user input events across both keyboard and mouse triggers.

* Dynamic Asset Loading & Path Management: Managing relative image asset paths for background visual updates during runtime state shifts.

* Conditional Business Logic: Efficient integer parsing, range-checking, and state-evaluation algorithms.

## Tech Stack

* Language: Java

* UI Framework: Java Swing / AWT

* Concepts: Event-Driven Architecture, Graphical User Interfaces (GUI), Algorithmic State Evaluation

#
![](images/guessnumberpic.png)
![](images/guessnumberpic2.png)
![](images/guessnumberpic3.png)
![](images/guessnumberpic4.png)
