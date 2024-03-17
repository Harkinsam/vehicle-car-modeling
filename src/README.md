# Vehicle and Car Classes

This project includes Java classes for modeling vehicles and cars, along with a main class to demonstrate their usage.

## Getting Started

To get started with the project, clone this repository to your local machine using the following command:

```bash
git clone https://github.com/harkinsam/banking-system.git
```

**Usage**
Compile the Java files using the following command:

```bash
javac *.java
```

Run the Main class to execute the banking system:

```bash
java Main
```
# Classes

## Vehicle Class

The `Vehicle` class represents a basic vehicle with properties such as name, size, current velocity, and current direction. It includes methods for steering, moving, retrieving details, and stopping.

## Car Class

The `Car` class extends the `Vehicle` class and adds specific properties for cars, including the number of wheels, doors, gears, and whether it's manual. It also includes methods for changing gears and velocity.

## Outlander Class

The `Outlander` class extends the `Car` class and adds a specific feature for an Outlander car related to road service months. It includes a method for accelerating based on different rates and gear changes.

## Usage

In the `Main` class, an instance of the `Outlander` class is created, and various methods are called to demonstrate functionality such as acceleration, steering, and gear changes.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for 