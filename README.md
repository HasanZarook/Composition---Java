
# 🏠 Composition and Garbage Collection in Java

This project demonstrates **composition** in Java along with object destruction using the `finalize()` method. It shows how objects are created and how the garbage collector handles object cleanup.

---

## 📝 Classes Overview

### 1. Room
- Represents a **room** in a house.
- Prints messages when created and destroyed.
```java
Room r = new Room(); // "Room Created"
````

### 2. Person

* Represents a **person**.
* Prints messages when created and destroyed.

### 3. House

* Represents a **house** containing a `Room` (composition: House *has-a* Room).
* Prints messages when created and destroyed.

---

## 🚀 How to Run

1. Clone or download the repository.
2. Compile the program:

```bash
javac CompAgg.java
```

3. Run the program:

```bash
java composition.CompAgg
```

4. Observe console output for object creation and potential garbage collection messages.

---

## ⚡ Example Output

```
Person Created
House created
Room Created
Out and about
```

> Note: Messages from `finalize()` may appear later or not at all, as garbage collection is non-deterministic.

---

## 🛠 Concepts Demonstrated

* **Composition** (`House` contains `Room`)
* **Object Lifecycle** (construction and garbage collection)
* **Finalize Method** (`finalize()` used before object destruction)
* **Non-deterministic Garbage Collection** (`System.gc()` request)

---

## 📜 License

This project is licensed under the **MIT License**.
You are free to use, modify, and distribute this code.

```
MIT License
```

---

## 📧 Contact

For any questions, suggestions, or issues, contact:
**Email:** [hasanzarook46@gmail.com](mailto:hasanzarook46@gmail.com)

```
