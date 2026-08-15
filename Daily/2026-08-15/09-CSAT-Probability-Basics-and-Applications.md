# CSAT: Probability – Basics and Applications

## Introduction to Probability

Probability is a measure of the likelihood of an event occurring. It is expressed as a number between 0 and 1, where 0 indicates impossibility and 1 indicates certainty. In CSAT, probability questions test the ability to analyse situations involving chance, often in combination with counting techniques (permutations and combinations).

## Basic Terminology

- **Experiment**: A process that leads to one or more outcomes (e.g., tossing a coin, drawing a card).
- **Outcome**: A possible result of an experiment.
- **Sample Space (S)**: The set of all possible outcomes.
- **Event**: A subset of the sample space; a collection of outcomes of interest.
- **Favourable Outcomes**: Outcomes that constitute the event of interest.

## Classical Definition of Probability

If all outcomes of an experiment are equally likely, the probability of an event A is:

P(A) = Number of favourable outcomes / Total number of possible outcomes

This definition applies when the sample space is finite and outcomes are equally likely.

## Axioms and Basic Rules

- 0 ≤ P(A) ≤ 1 for any event A.
- P(S) = 1 (probability of the entire sample space is 1).
- P(impossible event) = 0.
- For mutually exclusive events A and B (no common outcomes), P(A or B) = P(A) + P(B).
- P(not A) = 1 − P(A).

## Addition and Multiplication Rules

**Addition Rule (General)**

P(A ∪ B) = P(A) + P(B) − P(A ∩ B)

When A and B are mutually exclusive, P(A ∩ B) = 0, so the formula simplifies.

**Multiplication Rule**

For independent events, P(A and B) = P(A) × P(B).

For dependent events, P(A and B) = P(A) × P(B|A), where P(B|A) is the conditional probability of B given A.

## Conditional Probability

Conditional probability of A given B is:

P(A|B) = P(A ∩ B) / P(B), provided P(B) ≠ 0.

It represents the probability of A occurring given that B has already occurred.

## Independent and Dependent Events

Two events are independent if the occurrence of one does not affect the probability of the other. Otherwise they are dependent. Drawing cards without replacement creates dependence; with replacement (or successive coin tosses) usually creates independence.

## Complementary Counting and “At Least” Problems

Problems asking for the probability of “at least one” occurrence are often solved more easily by calculating the complementary probability (none) and subtracting from 1:

P(at least one) = 1 − P(none)

This technique is frequently useful in CSAT questions involving multiple trials.

## Applications and Typical Question Types

- Coins, dice and cards: standard sample spaces with equally likely outcomes.
- Balls of different colours drawn from bags (with or without replacement).
- Selection of people or objects with certain characteristics.
- Problems combining probability with permutations and combinations (e.g., probability that a randomly formed committee has a certain composition).
- Sequential events and conditional probability.

## Problem-Solving Approach

1. Clearly identify the experiment and the sample space.
2. Determine whether outcomes are equally likely.
3. Define the event of interest carefully.
4. Count favourable and total outcomes (using combinations or permutations as needed).
5. Apply the appropriate formula.
6. For complex events, consider complementary counting or breaking into mutually exclusive cases.
7. Check whether independence or dependence applies when multiple events are involved.

## Key Formulas to Remember

- P(A) = n(A) / n(S)
- P(A') = 1 − P(A)
- P(A ∪ B) = P(A) + P(B) − P(A ∩ B)
- P(A ∩ B) = P(A) × P(B) for independent events
- P(A|B) = P(A ∩ B) / P(B)
- P(at least one) = 1 − P(none)

## Summary

Probability in CSAT rests on a clear understanding of sample spaces, events and the classical definition, together with the addition and multiplication rules and the concept of conditional probability. Mastery of complementary counting and careful distinction between independent and dependent situations enables efficient solution of the majority of questions. Consistent practice with structured counting and formula application builds both accuracy and speed.