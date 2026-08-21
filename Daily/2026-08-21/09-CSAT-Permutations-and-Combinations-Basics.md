# Permutations and Combinations: Fundamental Concepts for CSAT

Permutations and combinations form a core part of the quantitative aptitude and logical reasoning sections of the CSAT paper. They deal with counting the number of ways in which objects can be arranged or selected under given conditions.

## Fundamental Principle of Counting

If an event can occur in m different ways and another independent event can occur in n different ways, then the two events together can occur in m × n ways. This is the multiplication principle. The addition principle applies when the events are mutually exclusive: if one event can occur in m ways and another in n ways, and the two cannot occur simultaneously, then either event can occur in m + n ways.

## Factorial Notation

The product of the first n natural numbers is called n factorial and is written as n!.  
n! = n × (n − 1) × (n − 2) × … × 3 × 2 × 1  
By definition, 0! = 1.  
Factorials grow rapidly: 5! = 120, 6! = 720, 7! = 5040, 10! = 3,628,800.

## Permutations

A permutation is an arrangement of objects in a definite order. The number of permutations of n distinct objects taken r at a time is denoted by P(n, r) or nPr.

Formula:  
nPr = n! / (n − r)!   for 0 ≤ r ≤ n

When r = n, nPn = n!. This is the number of ways of arranging n distinct objects among themselves.

### Important Cases

1. **Permutations of n distinct objects**  
   Number of ways = n!.

2. **Permutations of n objects of which p are identical of one kind, q identical of another kind, etc.**  
   Number of distinct arrangements = n! / (p! × q! × …).

3. **Circular Permutations**  
   Arrangements of n distinct objects in a circle. Since rotations of the same arrangement look identical, the number of distinct circular permutations is (n − 1)!.  
   If clockwise and anticlockwise arrangements are considered the same (for example, a necklace that can be flipped), the number becomes (n − 1)! / 2.

4. **Permutations with Restrictions**  
   - When two particular objects must always be together: treat the two objects as a single unit, so the number of units becomes n − 1; arrange them in (n − 1)! ways and the two objects within the unit in 2! ways. Total = 2 × (n − 1)!.  
   - When two particular objects must never be together: total permutations minus permutations in which they are together = n! − 2(n − 1)!.

## Combinations

A combination is a selection of objects without regard to order. The number of combinations of n distinct objects taken r at a time is denoted by C(n, r) or nCr.

Formula:  
nCr = n! / [r! × (n − r)!]   for 0 ≤ r ≤ n

Note that nCr = nC(n − r). This symmetry is often useful.

Also, nPr = nCr × r!. That is, the number of permutations equals the number of combinations multiplied by the number of ways of arranging the selected objects.

### Important Identities

- nC0 = nCn = 1
- nC1 = nCn − 1 = n
- nCr + nC(r − 1) = (n + 1)Cr   (Pascal’s identity)

## Relationship and Distinctions

- Permutation → order matters (arrangement).  
- Combination → order does not matter (selection).

Example: Selecting a committee of 3 people from 10 is a combination (10C3). Assigning three distinct positions (president, secretary, treasurer) to 3 people selected from 10 is a permutation (10P3).

## Applications in CSAT-Type Problems

1. **Formation of numbers**  
   How many 3-digit numbers can be formed from the digits 1, 2, 3, 4, 5 without repetition? Answer: 5P3 = 60.

2. **Committees and teams**  
   In how many ways can a committee of 4 be chosen from 7 men and 5 women with at least 2 women? Calculate total ways minus invalid cases, or sum the valid cases (2 women + 2 men, 3 women + 1 man, 4 women).

3. **Words and letters**  
   Number of distinct arrangements of the letters of the word “ASSASSINATION”. Count the frequency of each letter and apply the formula for identical objects.

4. **Circular arrangements with conditions**  
   Seating of people around a round table with certain persons always together or always separated.

5. **Distribution of distinct or identical objects**  
   Care must be taken to distinguish whether objects are distinct and whether the boxes or groups are distinct.

## Useful Techniques

- Break complex problems into mutually exclusive cases and add the results.
- Use complementary counting: total ways minus unwanted ways.
- When dealing with “at least” or “at most”, sum the relevant combinations.
- For problems involving identical objects, adjust the factorial formula accordingly.
- Draw a simple diagram or list small cases when the numbers are small to verify the logic.

## Key Formulas at a Glance

- nPr = n! / (n − r)!
- nCr = n! / [r! (n − r)!]
- nPr = nCr × r!
- Circular permutations of n distinct objects = (n − 1)!
- Arrangements of n objects with p identical of one type = n! / p!

Mastery of these concepts comes from repeated practice of varied problems. Focus on understanding whether order matters in a given situation and whether any objects are identical or subject to restrictions. Accurate identification of the type of problem is more important than memorising a large number of special formulae.
