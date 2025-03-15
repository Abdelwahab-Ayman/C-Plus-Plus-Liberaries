# C++ Libraries

Here’s a list of **C++ libraries**, categorized into **default libraries** (part of the C++ Standard Library) and **community libraries** (third-party libraries). These libraries are widely used for various purposes, such as data structures, algorithms, graphics, networking, and more.

---

## **Default C++ Libraries**

These libraries are part of the C++ Standard Library and are available in any standard-compliant C++ compiler.

### 1. **Standard Template Library (STL)**
   - **Containers**: `vector`, `list`, `deque`, `set`, `map`, `unordered_set`, `unordered_map`, `stack`, `queue`, `priority_queue`.
   - **Algorithms**: `sort`, `find`, `binary_search`, `copy`, `transform`, `accumulate`, `for_each`.
   - **Iterators**: `begin`, `end`, `next`, `prev`, `advance`.
   - **Function Objects**: `less`, `greater`, `bind`, `function`.
   - **Utilities**: `pair`, `tuple`, `optional`, `variant`, `any`.

### 2. **C Standard Library**
   - **Input/Output**: `printf`, `scanf`, `fopen`, `fclose`, `fread`, `fwrite`.
   - **String Manipulation**: `strcpy`, `strcat`, `strlen`, `strcmp`, `strstr`.
   - **Memory Management**: `malloc`, `free`, `calloc`, `realloc`.
   - **Mathematical Functions**: `sqrt`, `pow`, `sin`, `cos`, `tan`, `log`, `exp`.
   - **Time Utilities**: `time`, `clock`, `difftime`.

### 3. **Input/Output Streams**
   - **Standard I/O**: `std::cin`, `std::cout`, `std::cerr`, `std::clog`.
   - **File I/O**: `std::ifstream`, `std::ofstream`, `std::fstream`.
   - **String Streams**: `std::istringstream`, `std::ostringstream`, `std::stringstream`.

### 4. **Threading and Concurrency**
   - **Threads**: `std::thread`, `std::async`, `std::future`, `std::promise`.
   - **Mutexes**: `std::mutex`, `std::lock_guard`, `std::unique_lock`.
   - **Atomic Operations**: `std::atomic`, `std::atomic_flag`.

---

## **Community Libraries**

These are third-party libraries developed by the C++ community and are widely used for specialized tasks.

### 1. **Boost**
   - A collection of peer-reviewed, high-quality libraries that extend C++ functionality.
   - **Key Libraries**:
     - `boost::asio` (networking and I/O).
     - `boost::filesystem` (file system operations).
     - `boost::regex` (regular expressions).
     - `boost::thread` (multithreading).
     - `boost::spirit` (parsing).
   - **Website**: [Boost](https://www.boost.org/)

### 2. **Qt**
   - A cross-platform framework for GUI development and application building.
   - **Key Features**:
     - GUI widgets.
     - Networking, multithreading, and SQL databases.
     - Signal-slot mechanism for event handling.
   - **Website**: [Qt](https://www.qt.io/)

### 3. **OpenCV**
   - A library for computer vision and image processing.
   - **Key Features**:
     - Image and video processing.
     - Object detection and tracking.
     - Machine learning integration.
   - **Website**: [OpenCV](https://opencv.org/)

### 4. **Eigen**
   - A template library for linear algebra.
   - **Key Features**:
     - Matrix and vector operations.
     - Solvers for linear systems.
     - Geometry transformations.
   - **Website**: [Eigen](https://eigen.tuxfamily.org/)

### 5. **SFML (Simple and Fast Multimedia Library)**
   - A library for multimedia applications like games.
   - **Key Features**:
     - Graphics rendering.
     - Audio playback.
     - Window and input management.
   - **Website**: [SFML](https://www.sfml-dev.org/)

### 6. **Catch2**
   - A modern, header-only testing framework for C++.
   - **Key Features**:
     - Simple syntax for writing tests.
     - Supports BDD (Behavior-Driven Development).
   - **Website**: [Catch2](https://github.com/catchorg/Catch2)

### 7. **Google Test (gtest)**
   - A testing framework for C++.
   - **Key Features**:
     - Unit testing.
     - Test fixtures and assertions.
   - **Website**: [Google Test](https://github.com/google/googletest)

### 8. **nlohmann/json**
   - A header-only library for JSON parsing and serialization.
   - **Key Features**:
     - Easy-to-use API.
     - Supports modern C++ features.
   - **Website**: [nlohmann/json](https://github.com/nlohmann/json)

### 9. **spdlog**
   - A fast and header-only logging library.
   - **Key Features**:
     - Asynchronous logging.
     - Multiple log sinks (file, console, etc.).
   - **Website**: [spdlog](https://github.com/gabime/spdlog)

### 10. **fmt**
   - A modern formatting library for C++.
   - **Key Features**:
     - Type-safe formatting.
     - Compatible with C++20 `std::format`.
   - **Website**: [fmt](https://github.com/fmtlib/fmt)

### 11. **POCO**
   - A cross-platform C++ library for building network and internet-based applications.
   - **Key Features**:
     - Networking, HTTP, and FTP.
     - Database access.
     - File system utilities.
   - **Website**: [POCO](https://pocoproject.org/)

### 12. **Abseil**
   - A collection of C++ library code designed to augment the C++ standard library.
   - **Key Features**:
     - Containers, strings, and utilities.
     - High-performance abstractions.
   - **Website**: [Abseil](https://abseil.io/)

### 13. **Cereal**
   - A header-only C++ library for serialization.
   - **Key Features**:
     - Serialization to JSON, XML, and binary formats.
     - Easy integration with custom types.
   - **Website**: [Cereal](https://github.com/USCiLab/cereal)

### 14. **GLM (OpenGL Mathematics)**
   - A mathematics library for graphics programming.
   - **Key Features**:
     - Vector and matrix operations.
     - Compatible with OpenGL and GLSL.
   - **Website**: [GLM](https://github.com/g-truc/glm)

### 15. **Dear ImGui**
   - A bloat-free graphical user interface library for C++.
   - **Key Features**:
     - Immediate-mode GUI.
     - Lightweight and easy to integrate.
   - **Website**: [Dear ImGui](https://github.com/ocornut/imgui)

---

## **How to Choose a Library?**
- **For Standard Tasks**: Use the **C++ Standard Library** (STL, I/O, threading, etc.).
- **For Specialized Tasks**: Use **community libraries** like Boost, OpenCV, or Qt.
- **For Performance**: Consider libraries like **Eigen** (linear algebra) or **spdlog** (logging).
- **For Testing**: Use **Catch2** or **Google Test**.

---

Let me know if you need more details about any specific library! 🚀
