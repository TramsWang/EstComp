# EstComp
Estimation-based Optimizations for the Semantic Compression of RDF Knowledge Bases

## 1. Source Code
Source code in **Java** and **C++** are included in `src.7z`. Decompress the file first.

### 1.1 Java
In directory `java/`, package the code and select `src/main/java/sinc2/Main.java` as the main class.
Suppose the JAR package is `sinc.jar`, use the following command to preview the options of this program:
```
java -jar sinc.jar -h
```
The option `-o` (for the "selection ratio") or `-N` (for negative sampling) should be used.

### 1.2 C++
C++ version is in directory `c++/`.
Use **CMake** to compile targets in `c++/CMakeLists.txt`.
The target `sinc` is the program.
Use the following command to preview the options of this program:
```
./sinc -help
```
The option `-o` (for the "selection ratio") or `-N` (for negative sampling) should be used.

### 1.3 Generators for negative samples
The correlated sampler introduced in Alg.3 is included in `java/src/main/java/sinc2/kb/gen_neg_con_rel.py`

## 2. Datasets
Datasets used in this project are included in `datasets.7z`.
