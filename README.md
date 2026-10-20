# Virtual Pet Simulator

## Names of Pair Working on This Fork
<Patrick Wright>

<Sean Whyle>

## Run from Git Bash

```bash
javac *.java
java Main
```

Expected initial output:

```text
Welcome to Virtual Pets!
Buddy says: Woof!
Luna says: Meow!
Buddy | Hunger: 30 | Happiness: 50
Luna | Hunger: 60 | Happiness: 65
```

You can also choose to run from Eclipse, VS Code, or another IDE that you are familiar with using instead

## Class overview

- `Pet`: shared state and behaviors for all pets.
- `Dog`: extends `Pet` and has a `bark` method.
- `Cat`: extends `Pet` and has a `meow` method.
- `Main`: constructs two pets and demonstrates the behaviors.
