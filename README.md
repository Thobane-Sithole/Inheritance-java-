# Java Inheritance Example

This project demonstrates a basic inheritance structure in Java using a simple example of animals. The project defines a base `Animal` class with two subclasses, `Cat` and `Dog`, each inheriting and expanding on the behavior of the `Animal` class.

## Project Structure

The project includes the following Java files:

- **Animal.java** - The base class that represents general characteristics and behaviors of animals.
- **Cat.java** - A subclass of `Animal` that represents characteristics specific to cats.
- **Dog.java** - A subclass of `Animal` that represents characteristics specific to dogs.
- **inheritance.java** - A supporting file to manage or demonstrate inheritance relationships within the program.
- **Main.java** - The main entry point of the program, used to run and demonstrate the functionality of the inheritance structure.

## File Descriptions

### Animal.java
The `Animal` class serves as the parent class for all animal types in this project. It typically defines common attributes and behaviors shared by all animals, such as:

- Attributes like `name`, `age`, and potentially others that every animal would have.
- Methods that describe common behaviors like `makeSound()` (a placeholder method that each subclass will override to provide specific sounds).

### Cat.java
The `Cat` class extends the `Animal` class, inheriting its properties and methods. Additionally, it defines behaviors and attributes unique to cats. This class overrides methods like `makeSound()` to return a sound typical of a cat, such as "Meow."

### Dog.java
The `Dog` class also extends the `Animal` class and follows a similar structure to `Cat.java`. It overrides the inherited methods to return dog-specific behaviors. For example, it might override `makeSound()` to return "Bark."

### inheritance.java
This file serves to organize the inheritance structure or may include auxiliary logic to demonstrate inheritance principles within the project. This could involve utility functions, configurations, or additional features that enhance the main examples of inheritance.

### Main.java
`Main.java` is the main driver of the project, where objects of `Animal`, `Cat`, and `Dog` are created to showcase polymorphism and inheritance. This class may instantiate instances of `Cat` and `Dog`, calling methods to illustrate how each subclass behaves according to its specific traits while adhering to the structure defined by `Animal`.

## How to Run

To compile and run this project, follow these steps:

1. **Compile the Classes**:
   ```bash
   javac *.java
   ```

2. **Run the Main Class**:
   ```bash
   java Main
   ```
## License

This project is open-source and available under the MIT License.

---

