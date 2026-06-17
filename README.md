# Evaluation of Random Variate Generation

An implementation of the exact random variate generation algorithm proposed by Lee and Saad in their paper, *"Random Variate Generation with Formal Guarantees"*. 

While the authors' original reference code is available in Haskell and their benchmark implementation is in C, this repository provides a modern **C++ alternative** to make the algorithm accessible to a wider audience.

### Key Details & Approximations
Because Haskell natively supports lazy evaluation and infinite streams, the original algorithm relies on generating infinite bit sequences. Since C++ manages memory differently, this implementation introduces deterministic approximations to handle bit generation within standard memory limits. 

## 🛠️ Contributing & Bug Reports
This is an active port, and feedback is highly appreciated! If you find any bugs, edge cases where the approximations fail, or opportunities for performance optimization, please feel free to **open an issue** or **submit a pull request**.
