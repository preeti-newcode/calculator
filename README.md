### **Project: Console-Based Calculator Using Circular Queue in C**

* Developed a simple **console-based calculator** in **C language** to perform basic arithmetic operations: addition, subtraction, multiplication, division, and modulus.

* Implemented a **circular queue of size 3** to store the **three most recent calculation results**, allowing efficient memory use and automatic overwriting of the oldest result.

* Designed the calculator to:

  * Accept two operands and an arithmetic operator from the user.
  * Compute the result using a **`math()` function** with a `switch-case` structure.
  * Store each result using an **`insert()` function** that manages circular queue logic.
  * Display only valid stored results using a **`display()` function**, avoiding garbage values.

* Used a **circular queue instead of a regular array** to:

  * Optimize memory usage.
  * Eliminate the need for manual data shifting.
  * Simulate real-world usage of fixed-size buffers in constrained environments.

* The circular queue correctly handles the **wrap-around** condition when the rear reaches the end of the array.

* The project reinforced concepts of:

  * **User input handling** and **arithmetic operations** in C.
  * **Data structure implementation**, specifically circular queues.
  * **Efficient memory management** and **overflow prevention** in fixed-size buffers.

* Resulted in a **lightweight, functional, and educational calculator** that combines core C programming with practical data structure application.
