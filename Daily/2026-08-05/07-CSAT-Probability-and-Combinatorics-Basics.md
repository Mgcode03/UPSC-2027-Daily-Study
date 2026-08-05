# CSAT: Probability and Combinatorics Basics

## Introduction to Counting Principles

Many problems in quantitative aptitude and logical reasoning require systematic counting of possibilities. The two fundamental principles are the Addition Principle and the Multiplication Principle.

**Addition Principle**: If an event can occur in m ways and another mutually exclusive event can occur in n ways, then either of the two events can occur in m + n ways.

**Multiplication Principle**: If an operation can be performed in m ways and after it is completed another operation can be performed in n ways, then the two operations can be performed in m × n ways.

These principles form the foundation of permutations and combinations.

## Factorial Notation

The product of the first n natural numbers is denoted by n! (n factorial).

n! = n × (n−1) × (n−2) × … × 2 × 1

By definition, 0! = 1.

Factorials grow very rapidly. They appear in the formulae for permutations and combinations.

## Permutations

A permutation is an arrangement of objects in a definite order.

The number of permutations of n distinct objects taken r at a time is denoted by P(n, r) or ⁿPᵣ:

P(n, r) = n! / (n − r)!

When r = n, P(n, n) = n! (all objects are arranged).

If the objects are not all distinct – for example, if there are n objects of which p are of one kind, q of another kind, etc. – then the number of distinct permutations is n! / (p! q! …).

### Circular Permutations

When objects are arranged in a circle, rotations of the same arrangement are considered identical. The number of ways of arranging n distinct objects in a circle is (n − 1)!.

If clockwise and anticlockwise arrangements are considered the same (as in a necklace that can be flipped), the number becomes (n − 1)! / 2.

## Combinations

A combination is a selection of objects without regard to order.

The number of combinations of n distinct objects taken r at a time is denoted by C(n, r) or ⁿCᵣ:

C(n, r) = n! / [r! (n − r)!]

Important identities:
- C(n, r) = C(n, n − r)
- C(n, 0) = C(n, n) = 1
- C(n, 1) = n
- C(n, r) + C(n, r − 1) = C(n + 1, r) (Pascal’s identity)

Permutations and combinations are related by:
P(n, r) = C(n, r) × r!

## Basic Probability

Probability measures the likelihood of an event occurring. In the classical definition, if a random experiment has n equally likely outcomes and an event A consists of m of those outcomes, then:

P(A) = m / n

Probability always lies between 0 and 1 inclusive.
- P(impossible event) = 0
- P(certain event) = 1

### Complementary Events

If A is an event, its complement A′ (or Aᶜ) consists of all outcomes not in A.

P(A) + P(A′) = 1

### Addition Rule

For any two events A and B:

P(A ∪ B) = P(A) + P(B) − P(A ∩ B)

If A and B are mutually exclusive (cannot occur together), then P(A ∩ B) = 0 and P(A ∪ B) = P(A) + P(B).

### Independent Events

Two events A and B are independent if the occurrence of one does not affect the probability of the other. In that case:

P(A ∩ B) = P(A) × P(B)

### Conditional Probability

The probability of A given that B has occurred is:

P(A | B) = P(A ∩ B) / P(B)   (provided P(B) ≠ 0)

## Simple Applications Useful for CSAT

1. **Cards**: A standard deck has 52 cards, 4 suits, 13 ranks. Probability problems often involve drawing cards with or without replacement.

2. **Dice**: A fair six-sided die has outcomes 1 through 6, each with probability 1/6. Problems may involve sum, product, or specific faces when two or more dice are thrown.

3. **Coins**: A fair coin has P(Heads) = P(Tails) = 1/2. Multiple tosses produce sequences whose probabilities can be calculated using independence.

4. **Selection problems**: Choosing committees, forming teams, or distributing identical/distinct objects often require combinations, sometimes with restrictions (for example, at least one woman, consecutive seats, etc.).

5. **Arrangement with restrictions**: People sitting with certain individuals always together (treat them as a single unit) or never together (total arrangements minus arrangements where they are together).

## Problem-Solving Approach

- Identify whether order matters (permutation) or not (combination).
- Check whether objects are distinct or identical.
- Look for restrictions and handle them by treating restricted items as a single unit or by complementary counting.
- For probability, first count the total number of equally likely outcomes, then count the favourable outcomes.
- When dealing with “at least” or “at most”, complementary counting is often simpler.
- Draw a tree diagram or make a systematic list for small cases to avoid missing outcomes.

## Key Formulae Summary

- n! = n × (n−1) × … × 1; 0! = 1
- P(n, r) = n! / (n − r)!
- C(n, r) = n! / [r! (n − r)!]
- Circular arrangements of n distinct objects: (n − 1)!
- P(A ∪ B) = P(A) + P(B) − P(A ∩ B)
- For independent events: P(A ∩ B) = P(A) P(B)
- P(A | B) = P(A ∩ B) / P(B)

Mastery of these elementary counting and probability ideas enables quick and accurate solution of a large class of CSAT quantitative and logical reasoning questions. Regular practice with varied restrictions and wordings builds the necessary speed and confidence.
