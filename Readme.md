# Cadence: Algorithmic Music Composition Engine in C++20

**Cadence** is a lightweight, modular C++20 library and CLI tool designed for procedural music generation, harmonic analysis, and standard MIDI (SMF) synthesis. Built with zero external dependencies, it provides audio engineers, composers, and game developers with an extensible system for rule-based and stochastic musical composition.

---

## Features

- **Harmonic & Scale Quantization:** Pre-configured modes (Ionian, Dorian, Aeolian, Harmonic Minor, Pentatonic, Whole Tone) with automatic pitch-class rounding.
- **Probabilistic & Stochastic Generation:** Markov-chain melodic steps, Gaussian rhythm distribution, and customizable voice-leading constraints.
- **Zero-Dependency MIDI Serialization:** Direct byte-level encoding of Standard MIDI File (SMF Format 0/1) tracks without third-party libraries.
- **Multi-Voice Counterpoint:** Independent track sequencing for basslines, chordal arpeggios, and melodic lead lines.
- **Modern C++20 Design:** Clean abstractions using `std::span`, `enum class`, strongly-typed ticks/pitches, and compile-time interval lookups.

---

## Project Architecture
