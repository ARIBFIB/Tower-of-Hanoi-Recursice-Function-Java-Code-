# Tower-of-Hanoi-Recursice-Function-Java-Code-
Solve the classic Tower of Hanoi puzzle using recursion in Java
# Tower of Hanoi

![How it works (6)](https://github.com/ARIBFIB/Tower-of-Hanoi-Recursice-Function-Java-Code-/assets/125716994/f25eb99b-9829-4316-9285-d6fc816491f4)
Check out the video tutorial on [YouTube](https://youtu.be/VGcayd8EO2E) for more information.

![the-tower-of-hanoi-a-game-to-end-the-world](https://github.com/ARIBFIB/Tower-of-Hanoi-Recursice-Function-Java-Code-/assets/125716994/577e49ab-1e20-4732-9b5a-0d7e4595c426)

# Code
```
public class TowerOfHanoi{
    public static void main(String[] args) {
        int numDesk = 5;
        moveDisk(numDesk, 'A', 'B', 'C');
    }
    public static void moveDisk(int n, char from, char to, char aux) {
        if(n == 1){
            System.out.println("Move Desk 1 from " + from + " to " + to);
            return;
        }
        moveDisk(n-1 , from , aux , to);
        System.out.println("Move Desk " + n + " from " + from + " to " +  to);
        moveDisk(n-1 , from , aux , to);
    }
}
```
# Output
![image](https://github.com/ARIBFIB/Tower-of-Hanoi-Recursice-Function-Java-Code-/assets/125716994/1dbffcda-384e-429f-8459-652c129b8a51)
```
Move Desk 1 from A to B
Move Desk 2 from A to C
Move Desk 1 from A to B
Move Desk 3 from A to B
Move Desk 1 from A to B
Move Desk 2 from A to C
Move Desk 1 from A to B
Move Desk 4 from A to C
Move Desk 1 from A to B
Move Desk 2 from A to C
Move Desk 1 from A to B
Move Desk 3 from A to B
Move Desk 1 from A to B
Move Desk 2 from A to C
Move Desk 1 from A to B
Move Desk 5 from A to B
Move Desk 1 from A to B
Move Desk 2 from A to C
Move Desk 1 from A to B
Move Desk 3 from A to B
Move Desk 1 from A to B
Move Desk 2 from A to C
Move Desk 1 from A to B
Move Desk 4 from A to C
Move Desk 1 from A to B
Move Desk 2 from A to C
Move Desk 1 from A to B
Move Desk 3 from A to B
Move Desk 1 from A to B
Move Desk 2 from A to C
Move Desk 1 from A to B
```

![Tower of Hanoi][]

> **Solve the classic Tower of Hanoi puzzle using recursion in Java**

## 🗼 About the Tower of Hanoi

The Tower of Hanoi is a classic mathematical puzzle that consists of three poles and a number of disks of different sizes, which can slide onto any pole. The objective of the puzzle is to move the entire stack of disks from the initial pole to another pole, obeying the following rules:

- Only one disk can be moved at a time.
- Each move consists of taking the upper disk from one of the stacks and placing it on top of another stack or an empty pole.
- No disk may be placed on top of a smaller disk.

## 🎮 The Challenge

In this project, you'll find a recursive Java implementation of the Tower of Hanoi puzzle. The goal is to create a game challenge that tests the player's problem-solving skills and understanding of recursive algorithms.

## 🛠️ Features

- Recursive solution for the Tower of Hanoi puzzle
- Customizable number of disks
- Visual representation of the puzzle state
- Step-by-step solution display

## 🚀 Getting Started

1. Clone the repository:
   ```
   git clone https://github.com/your-username/tower-of-hanoi.git](https://github.com/ARIBFIB/Tower-of-Hanoi-Recursice-Function-Java-Code-.git
   ```
2. Compile and run the `TowerOfHanoi` class:
   ```
   cd tower-of-hanoi
   javac TowerOfHanoi.java
   java TowerOfHanoi
   ```

## 🤝 Contributing

Contributions are always welcome! If you find any issues or have suggestions for improvements, please feel free to open an issue or submit a pull request.

## 📄 License

This project is licensed under the [MIT License](LICENSE).

## 👨‍💻 Software Developer

- [Abdul Rehman Irfan](https://github.com/ARIBFIB/Tower-of-Hanoi-Recursice-Function-Java-Code-.git)
[Tower of Hanoi]: https://github.com/your-username/tower-of-hanoi/blob/main/assets/tower-of-hanoi.png

In this example, the GitHub README includes the following elements:

- A main image for the Tower of Hanoi project
- A beautiful description of the Tower of Hanoi puzzle and the challenge
- A section explaining the features of the project
- Instructions for getting started with the project
- A contribution section
- A license section
- Information about the author(s)

The README also uses various fonts, styles, and icons to enhance the visual appeal and organization of the content.
