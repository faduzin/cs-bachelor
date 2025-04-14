# Formal Languages and Automata

## 2025-1

### 📘 Introduction to Formal Languages

- **Alphabet (Σ):** A finite set of symbols. Every language is built from an alphabet. The serial sum symbol (Σ) represents this set.
- **String:** A finite sequence of symbols from an alphabet.
- **Kleene Star (Σ\***): Denotes the set of all possible strings (including the empty string ε) formed from an alphabet Σ.
- **Language (L):** A language is a subset of Σ\*, i.e., it consists of valid strings formed from the alphabet.

---

### 🤖 Deterministic Finite Automata (DFA)

- A **DFA** is a theoretical machine used to recognize regular languages.
- It processes input strings **from left to right**, symbol by symbol.

#### **Definition Components:**

A DFA is defined as a 5-tuple:
**M = (Q, Σ, δ, q₀, F)**

Where:
- **Q**: A finite set of states.
- **Σ**: The input alphabet (symbols).
- **δ**: The transition function, which maps `δ: Q × Σ → Q`.
- **q₀**: The initial state (`q₀ ∈ Q`).
- **F**: The set of accepting/final states (`F ⊆ Q`).

#### **Key Concepts:**
- The automaton is **deterministic**, meaning from any given state and input symbol, there is exactly **one possible next state**.
- **Visual Representation:**
  - A triangle points to the **initial state**.
  - **Double circles** represent **accepting (final) states**.
- **Acceptance Condition:**
  - If, after reading the entire input string, the DFA ends in a state that belongs to **F**, then the string is **accepted** and belongs to the language.
  - Otherwise, it is **rejected**.

#### **Example Notation:**
- `δ(q₀, a) = q₁` means that from the initial state `q₀`, upon reading symbol `a ∈ Σ`, the automaton transitions to state `q₁`.

---

