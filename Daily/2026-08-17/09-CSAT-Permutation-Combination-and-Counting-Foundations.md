# Permutation, Combination and Fundamental Counting Principles

## Fundamental Principle of Counting

The foundation of permutation and combination lies in the fundamental principle of counting (also called the multiplication principle).

If one event can occur in m ways and a second independent event can occur in n ways, then the two events together can occur in m × n ways. This extends to any number of independent events: the total number of ways is the product of the number of ways each event can occur.

Example: A student has 3 shirts and 4 trousers. The number of different outfits is 3 × 4 = 12.

When events are sequential and the choice at each step depends on previous choices, the same multiplication principle applies by considering the number of options available at each stage.

## Factorial Notation

The factorial of a positive integer n, denoted n!, is the product of all positive integers from 1 to n:
n! = n × (n−1) × (n−2) × … × 2 × 1

By definition, 0! = 1.

Factorials grow rapidly and appear constantly in counting problems.

## Permutations

A permutation is an arrangement of objects in a definite order. The order matters.

### Permutations of n Distinct Objects Taken r at a Time

The number of ways to arrange r objects out of n distinct objects is denoted by P(n, r) or nPr and is given by:

P(n, r) = n! / (n − r)!

This can be understood as: the first position can be filled in n ways, the second in (n−1) ways, and so on, until the r-th position is filled in (n−r+1) ways. The product is n × (n−1) × … × (n−r+1) = n! / (n−r)!.

Special case: When r = n, P(n, n) = n! (all objects are arranged).

### Permutations with Repetition

If repetition of objects is allowed, the number of permutations of n distinct objects taken r at a time is n^r.

### Permutations of Objects When Some Are Identical

If there are n objects of which p are identical of one kind, q identical of another kind, and so on, then the number of distinct permutations of all n objects is:

n! / (p! × q! × …)

## Combinations

A combination is a selection of objects without regard to order. The order does not matter.

### Combinations of n Distinct Objects Taken r at a Time

The number of ways to select r objects out of n distinct objects is denoted by C(n, r) or nCr or (n choose r) and is given by:

C(n, r) = n! / [r! × (n − r)!]

Relationship with permutations: P(n, r) = C(n, r) × r!

Because for every selection of r objects, there are r! ways to arrange them.

Important identities:
- C(n, r) = C(n, n − r)
- C(n, 0) = C(n, n) = 1
- C(n, 1) = n
- Pascal’s identity: C(n, r) + C(n, r−1) = C(n+1, r)

## Distinguishing Permutation from Combination

The key question is whether order matters.
- If the arrangement or sequence is important (e.g., ranking, passwords, positions), use permutations.
- If only the group or set matters (e.g., committees, teams without assigned roles, selection of items), use combinations.

Example: Selecting 3 students out of 10 for a committee is a combination. Selecting 3 students out of 10 for the positions of president, secretary and treasurer is a permutation.

## Restricted and Conditional Counting

Many problems involve restrictions:
- Particular objects must be included or excluded
- Objects must or must not be together
- Circular arrangements
- Arrangements with gaps or specific positions

For circular permutations of n distinct objects, the number of arrangements is (n−1)!, because rotations of the same arrangement are considered identical. If clockwise and anticlockwise arrangements are considered the same (as in a necklace that can be flipped), the number is further divided by 2.

When certain objects must be together, treat them as a single unit and then arrange the remaining units, multiplying by the internal arrangements of the grouped objects.

## Applications in CSAT-Type Problems

Counting problems in CSAT often appear in the form of:
- Number of ways to form committees or teams with conditions
- Number of possible passwords, codes or number plates
- Arrangements of letters of words with or without conditions
- Selection of routes or paths
- Distribution of distinct or identical objects into groups

A systematic approach is useful:
1. Identify whether order matters (permutation) or not (combination).
2. Identify whether objects are distinct or identical.
3. Apply restrictions by inclusion, exclusion or treating groups as units.
4. Use the multiplication principle for sequential choices.
5. Check for over-counting or under-counting.

## Key Formulas for Quick Reference

- Fundamental principle: m × n × …
- n! = n × (n−1) × … × 1; 0! = 1
- P(n, r) = n! / (n−r)!
- C(n, r) = n! / [r!(n−r)!]
- P(n, r) = C(n, r) × r!
- Circular permutations of n distinct objects: (n−1)!
- Identical objects: n! / (p! q! …)

Mastery of these foundational counting principles enables rapid and accurate solution of a wide range of logical and quantitative problems that appear in the CSAT paper. Practice in translating verbal conditions into the appropriate counting framework is as important as memorising the formulas themselves.
