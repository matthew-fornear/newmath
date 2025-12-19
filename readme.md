# Modern Math Notation: The Complete Reference

## Core Principle

Every symbol and term must be immediately understandable to someone who speaks English. No exceptions.

---

## 1. Basic Operators

| Old | New |
|-----|-----|
| × | * |
| ÷ | / |
| − | - |
| + | + |
| = | = |
| ≠ | != |
| ≤ | <= |
| ≥ | >= |
| ≈ | ~= |
| ± | +/- |
| ∞ | inf |

---

## 2. Greek Letters → Plain English

Every Greek letter replaced with what it actually means:

| Old | New | What It Means |
|-----|-----|---------------|
| α, β, γ | angle_a, angle_b, angle_c | angles (when measuring rotation) |
| α, β, γ | variable_a, variable_b, variable_c | numbers you can choose to control behavior |
| α, β, γ | multiplier_a, multiplier_b, multiplier_c | numbers that multiply other values |
| θ | angle | a rotation measurement |
| φ | horizontal_angle | left-right rotation |
| ψ | vertical_angle | up-down rotation |
| π | (pi) circle_constant | the circle constant ≈3.14159 |
| τ | full_circle | one complete rotation ≈6.28318 |
| e | growth_constant | natural continuous growth ≈2.71828 |
| σ | spread | how scattered data is |
| Σ | (becomes sum function) | add things up |
| μ | average | the middle value |
| λ | stretch_amount | how much something stretches |
| Δ | change | difference between values |
| δ | tiny_change | extremely small difference |
| ∂ | change_one_var | change in one direction only |
| ∇ | uphill_direction | which way slopes upward most |
| ε | tiny_value | very small number |
| ρ | density | amount of stuff per space |
| ω | spin_speed | how fast something rotates |
| ∅ | nothing | empty collection |

---

## 3. Functions: What They Actually Do

### Understanding Change (Calculus)

| Old | New | What It Actually Does |
|-----|-----|----------------------|
| f'(x) | steepness_at(f, x) | how tilted the curve is at point x |
| f''(x) | steepness_at(f, x, 2) | how fast the tilt is changing |
| df/dx | steepness_at(f, x) | same as above (different notation) |
| d²f/dx² | steepness_at(f, x, 2) | same as above (different notation) |
| ∂f/∂x | steepness_in_x(f, x) | tilt in x direction (ignoring other directions) |
| ∂²f/∂x² | steepness_in_x(f, x, 2) | how fast x-tilt changes |
| ∫ f(x) dx | total_area_under(f(x), x) | area trapped under the curve |
| ∫ᵃᵇ f(x) dx | total_area_under(f(x), x, a, b) | area under curve from a to b |
| lim_{x→a} f(x) | gets_close_to(f(x), when x -> a) | value f approaches as x nears a |
| lim_{x→∞} f(x) | settles_at(f(x), when x -> inf) | value f approaches as x grows forever |

### Understanding Flow (Vector Calculus)

| Old | New | What It Actually Does |
|-----|-----|----------------------|
| ∇f | steepest_uphill(f) | if f is a hill, which direction climbs fastest |
| ∇·F | spreading_rate(F) | how much F flows outward from a point |
| ∇×F | swirl_rate(F) | how much F spirals around a point |
| ∇²f | diffusion_rate(f) | how fast f spreads through space |

### Adding and Multiplying Lists

| Old | New | What It Does |
|-----|-----|-------------|
| ∑ᵢ₌₁ⁿ xᵢ | add_all(x[i], i from 1 to n) | add up all x values from position 1 to n |
| ∏ᵢ₌₁ⁿ xᵢ | multiply_all(x[i], i from 1 to n) | multiply all x values together |
| ∑ᵢ xᵢ | add_all(x[i], i) | add all x values |

### Circle and Triangle Math

| Old | New | What It Does |
|-----|-----|-------------|
| sin(x) | height_on_circle(x) | for angle x, height of point on circle with radius 1 |
| cos(x) | width_on_circle(x) | for angle x, horizontal distance on circle with radius 1 |
| tan(x) | slope_of_angle(x) | slope of line at angle x |
| arcsin(x) | angle_for_height(x) | what angle gives you height x |
| arccos(x) | angle_for_width(x) | what angle gives you width x |
| arctan(x) | angle_for_slope(x) | what angle gives you slope x |

### Powers and Roots

| Old | New | What It Does |
|-----|-----|-------------|
| log(x) | power_needed(x) | what power gives you x (base depends on context) |
| ln(x) | power_of_growth(x) | what power of growth_constant gives you x |
| log₂(x) | power_of_two(x) | what power of 2 gives you x |
| log₁₀(x) | power_of_ten(x) | what power of 10 gives you x |
| √x | square_root(x) | what number times itself equals x |
| ⁿ√x | nth_root(x, n) | what number raised to power n equals x |
| \|x\| | distance_from_zero(x) | how far x is from 0 (always positive) |
| ⌊x⌋ | round_down(x) | nearest whole number ≤ x |
| ⌈x⌉ | round_up(x) | nearest whole number ≥ x |
| n! | multiply_descending(n) | n × (n-1) × (n-2) × ... × 1 |

### Counting Arrangements

| Old | New | What It Does |
|-----|-----|-------------|
| ⁿCᵣ | ways_to_choose(n, r) | how many ways to pick r items from n items (order doesn't matter) |
| ⁿPᵣ | ways_to_arrange(n, r) | how many ways to arrange r items from n items (order matters) |

---

## 4. Collections (Sets)

| Old | New | What It Means |
|-----|-----|---------------|
| ∈ | is_in | element belongs to collection |
| ∉ | not_in | element doesn't belong |
| ⊆ | is_subset_of | every element of A is also in B |
| ⊂ | is_smaller_subset_of | A is subset of B but not equal to B |
| ∪ | combined_with | all elements from both collections |
| ∩ | shared_between | only elements in both collections |
| ∖ | remove_from | elements in first but not second |
| × | all_pairs_of | every possible pair from two collections |
| ∅ | empty_collection | collection with nothing in it |
| {x : condition} | {x : condition} | all x where condition is true |

---

## 5. Logic

| Old | New | What It Means |
|-----|-----|---------------|
| ∧ | and | both must be true |
| ∨ | or | at least one must be true |
| ¬ | not | opposite truth value |
| → | if_then | if first is true, second must be true |
| ↔ | same_truth_as | both true or both false |
| ⊕ | exactly_one_of | one true, one false |
| ∀ | for_every | true for all possible values |
| ∃ | there_exists | true for at least one value |
| ∄ | none_exist | not true for any value |

---

## 6. Grids of Numbers (Matrices)

| Old | New | What It Does |
|-----|-----|-------------|
| Aᵀ | flipped(A) | swap rows and columns |
| A⁻¹ | undo_transform(A) | reverses what A does |
| det(A) | volume_scaling(A) | how much A stretches/shrinks space |
| tr(A) | diagonal_sum(A) | sum of diagonal entries |
| rank(A) | dimensions_kept(A) | how many dimensions survive the transformation |
| dim(V) | dimensions_of(V) | number of directions in space V |

### Special Stretching Properties

| Old | New | What It Means |
|-----|-----|---------------|
| eigenvalue | stretch_amount | how much a transformation stretches in a special direction |
| eigenvector | stretch_direction | the direction that only gets stretched, not rotated |

**Example**: If transformation A makes vector v twice as long but doesn't rotate it, then v is a stretch_direction and 2 is the stretch_amount.

---

## 7. Terms Renamed for Clarity

| Old Term | New Term | What It Means |
|----------|----------|---------------|
| polynomial | power_expression | expression like 5x³ + 2x² - 7x + 3 |
| quadratic | squared_expression | highest power is x² |
| cubic | cubed_expression | highest power is x³ |
| coefficient | multiplier | the number in front (3 in 3x²) |
| exponent | power | how many times to multiply (2 in x²) |
| variable | changing_value | the letter that can be different values (x, y, z) |
| constant | fixed_value | number that doesn't change |
| domain | possible_inputs | all values x can be |
| range | possible_outputs | all values f(x) can be |
| codomain | output_space | where outputs are allowed to land |
| function | input_to_output | rule that turns inputs into outputs |
| inverse | undo_function | reverses what function does |
| composition | chain_functions | output of one becomes input of next |
| rational number | fraction_number | can be written as fraction of whole numbers |
| irrational number | non_fraction_number | cannot be written as fraction (like circle_constant, √2) |
| real numbers | number_line | all numbers on infinite line |
| complex numbers | plane_numbers | numbers with real and imaginary parts (a + bi) |
| imaginary unit (i) | square_root_of_negative_one | the number where i² = -1 |
| integer | whole_number | ..., -2, -1, 0, 1, 2, ... |
| natural number | counting_number | 1, 2, 3, 4, ... |
| prime | only_divisible_by_one_and_itself | 2, 3, 5, 7, 11, ... |
| composite | has_factors | non-prime number greater than 1 |
| factor | divides_evenly | number that divides another with no remainder |
| multiple | repeated_addition | 12 is a multiple of 3 (3+3+3+3) |
| injective | one_to_one | each output comes from exactly one input |
| surjective | covers_all_outputs | every possible output is used |
| bijective | perfect_pairing | one-to-one AND covers all outputs |
| continuous | no_jumps | curve has no gaps or breaks |
| discontinuous | has_jumps | curve breaks somewhere |
| asymptote | line_it_approaches | line the curve gets infinitely close to |
| converge | settles_down | sequence/series approaches a fixed value |
| diverge | grows_forever | sequence/series doesn't settle |
| sequence | ordered_list | list of numbers in specific order |
| series | sum_of_sequence | add all terms in sequence |
| arithmetic sequence | add_same_each_time | 2, 5, 8, 11 (add 3 each time) |
| geometric sequence | multiply_same_each_time | 2, 6, 18, 54 (multiply 3 each time) |
| permutation | arrangement_order_matters | ABC ≠ BAC |
| combination | selection_order_ignored | ABC = BAC |
| probability | chance_of_happening | number between 0 and 1 |
| expected value | average_outcome | what you'd expect on average |
| variance | squared_spread | average squared distance from average |
| standard deviation | typical_distance | typical distance from average |
| correlation | move_together_amount | how much two things change together (-1 to 1) |
| independent | not_related | one doesn't affect the other |
| conditional | given_that | probability when you know something else |
| mutually exclusive | cannot_both_happen | if one happens, other can't |

---

## 8. Number Collections

| Old | New | What It Contains |
|-----|-----|-----------------|
| ℕ | CountingNumbers | 1, 2, 3, 4, ... |
| ℤ | WholeNumbers | ..., -2, -1, 0, 1, 2, ... |
| ℚ | FractionNumbers | all numbers writeable as fractions |
| ℝ | NumberLine | all points on infinite line |
| ℂ | PlaneNumbers | all numbers a + bi |
| ℙ | Primes | 2, 3, 5, 7, 11, 13, ... |

---

## 9. Interval Notation

| Notation | Meaning |
|----------|---------|
| [a, b] | includes both endpoints |
| (a, b) | excludes both endpoints |
| [a, b) | includes a, excludes b |
| (a, b] | excludes a, includes b |

---

## 10. Complex Numbers

| Old | New | What It Means |
|-----|-----|---------------|
| i | sqrt_negative_one | the number where i² = -1 |
| Re(z) | real_part(z) | the "a" in a + bi |
| Im(z) | imaginary_part(z) | the "b" in a + bi |
| \|z\| | distance_from_origin(z) | length from (0,0) to point z |
| arg(z) | angle_from_right(z) | rotation angle from positive x-axis |
| z* or z̄ | mirror_over_real(z) | flip over real axis: a + bi → a - bi |

---

## 11. Chance and Data (Probability & Statistics)

| Old | New | What It Means |
|-----|-----|---------------|
| P(A) | chance(A) | how likely A is (0 to 1) |
| P(A\|B) | chance(A given B) | how likely A is when you know B happened |
| E[X] | average_outcome(X) | expected value if you repeat many times |
| Var(X) | squared_spread(X) | average squared distance from average |
| σ² | squared_spread | same as variance |
| σ | typical_spread | standard deviation (square root of variance) |
| μ | average | average value |
| Cov(X,Y) | move_together(X, Y) | how much X and Y change together |
| ρ | move_together_amount | standardized version of covariance (-1 to 1) |

---

## Examples: Before and After

### Calculus

**Before:**
```
f'(x) = lim_{h→0} [f(x+h) - f(x)]/h

∫₀^∞ e^{-x²} dx = √π/2
```

**After:**
```
steepness_at(f, x) = gets_close_to((f(x+h) - f(x))/h, when h -> 0)

total_area_under(growth_constant^(-x^2), x, 0, inf) = square_root(circle_constant)/2
```

### Linear Algebra

**Before:**
```
Av = λv
det(A) ≠ 0
```

**After:**
```
A * v = stretch_amount * v
volume_scaling(A) != 0
```

### Sets

**Before:**
```
A ∪ B = {x | x ∈ A ∨ x ∈ B}
∀x ∈ ℝ, ∃y ∈ ℝ : y > x
```

**After:**
```
A combined_with B = {x : x is_in A or x is_in B}
for_every x is_in NumberLine, there_exists y is_in NumberLine : y > x
```

### Probability

**Before:**
```
P(A|B) = P(A ∩ B) / P(B)
E[X] = ∫ x f(x) dx
```

**After:**
```
chance(A given B) = chance(A shared_between B) / chance(B)
average_outcome(X) = total_area_under(x * spread_function(x), x)
```

---

## What to Keep

**Keep circle_constant**: The circle constant ≈3.14159, universally recognized

**Keep growth_constant**: The natural growth number ≈2.71828. If you have $1 growing at 100% interest compounded continuously for 1 year, you get growth_constant.

---
