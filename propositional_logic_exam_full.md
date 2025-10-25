# Exam: Chapter 2.1 — Propositional Logic (100 points total)

---

1. (2 pts) Define a **proposition** and give one example that *is* a proposition and one that is *not*.
2. (2 pts) Explain the difference between a **propositional variable** and a **compound proposition**.
3. (3 pts) State the meaning of each logical operator: ¬, ∧, ∨.
4. (2 pts) Describe the purpose of **truth tables** in propositional logic.
5. (3 pts) Write the **precedence order** of the logical operators ¬, ∧, ∨, →, ↔, ⊕.
6. (3 pts) Define the terms **tautology**, **contradiction**, and **contingency**.
7. (3 pts) What does it mean for two propositions P and Q to be **logically equivalent**? Give one example.
8. (4 pts) Construct a truth table for the compound proposition ¬p ∨ (q ∧ p). Identify its classification.
9. (4 pts) Construct a truth table for (p → q) → ¬p and ¬q → ¬p. Are they logically equivalent?
10. (3 pts) How many unique truth tables exist for formulas containing two propositional variables? Explain.
11. (3 pts) Using a truth table, verify that (p ∧ q) ∧ r ≡ p ∧ (q ∧ r).
12. (4 pts) Show that p ↔ q ≡ (p → q) ∧ (q → p) using truth tables.
13. (3 pts) Translate the sentence: “If you are good, Sinterklaas brings you toys” into propositional logic.
14. (4 pts) Write the **converse**, **inverse**, and **contrapositive** of p → q. Identify which are equivalent.
15. (4 pts) Translate: “If the system crashes, then either the database is corrupted or the power failed.”
16. (4 pts) Express “Either you study logic or you pass the exam (but not both)” symbolically.
17. (3 pts) Translate “If I am in Delft, then I am in the Netherlands” and give its contrapositive.
18. (4 pts) Identify whether the statement “p ∨ ¬p” is a tautology, contradiction, or contingency.
19. (3 pts) Explain why ¬(¬p) ≡ p holds. Use a truth table to confirm.
20. (3 pts) Show that p ∧ q ≡ ¬(¬p ∨ ¬q) using Boolean algebra.
21. (4 pts) Demonstrate that p → q is equivalent to ¬p ∨ q.
22. (3 pts) Determine whether → is associative, i.e., is (p → q) → r equivalent to p → (q → r)? Justify.
23. (4 pts) Define the **exclusive or** (⊕) operator and provide its truth table.
24. (3 pts) Explain the difference between **inclusive** and **exclusive** or, with an example in English.
25. (5 pts) Define **functional completeness** and show that {¬, ∨} is functionally complete.
26. (4 pts) Express p ∧ q using only ¬ and ∨.
27. (4 pts) Define the **NOR** operator ↓ by p ↓ q ≡ ¬(p ∨ q). Express ¬p, p ∨ q, and p ∧ q using ↓ only.
28. (4 pts) Express p → q, p ↔ q, and p ⊕ q using only the NOR operator.
29. (3 pts) Define the **main connective** in a compound proposition and provide an example.
30. (4 pts) Explain why a truth table with n variables has 2ⁿ rows, and prove it by reasoning or induction.

---

# Solutions

1. A **proposition** is a statement that is either true or false. Example: “2 + 2 = 4” (is), “Close the door!” (is not).
2. A **propositional variable** represents an unknown proposition (p, q), while a **compound proposition** combines them with logical operators.
3. ¬p: not p; p ∧ q: p and q; p ∨ q: p or q.
4. Truth tables show how truth values of variables determine the truth of compound propositions.
5. Precedence: ¬, ∧, ∨, ⊕, →, ↔.
6. Tautology: always true; Contradiction: always false; Contingency: sometimes true.
7. P and Q are logically equivalent if P ↔ Q is a tautology. Example: p → q ≡ ¬p ∨ q.
8. Contingency (some true, some false rows).
9. Equivalent; both simplify to ¬q → ¬p.
10. 16 (2⁴) possible truth tables.
11. Equivalent; conjunction is associative.
12. Equivalent; truth table columns match.
13. p → q, where p = “You are good”, q = “Sinterklaas brings toys.”
14. Converse: q → p; Inverse: ¬p → ¬q; Contrapositive: ¬q → ¬p. Equivalent: original ↔ contrapositive.
15. p → (q ∨ r); p = “System crashes”, q = “Database corrupted”, r = “Power failed.”
16. p ⊕ q.
17. p → q; contrapositive: ¬q → ¬p.
18. Tautology (law of excluded middle).
19. Truth table shows identical truth values for p and ¬(¬p).
20. By De Morgan’s law: p ∧ q ≡ ¬(¬p ∨ ¬q).
21. Truth table verification shows identical results for p → q and ¬p ∨ q.
22. Not associative; truth tables differ.
23. p ⊕ q true when exactly one of p, q is true.
24. Inclusive or = at least one true; exclusive or = exactly one true.
25. A set is functionally complete if all logical expressions can be built from it; {¬, ∨} can express ∧, →, ↔.
26. p ∧ q ≡ ¬(¬p ∨ ¬q).
27. ¬p = p ↓ p; p ∨ q = (p ↓ q) ↓ (p ↓ q); p ∧ q = (p ↓ p) ↓ (q ↓ q).
28. p → q = (p ↓ p) ↓ q; p ↔ q = ((p ↓ p) ↓ q) ↓ ((q ↓ q) ↓ p); p ⊕ q = (p ↔ q) ↓ (p ↔ q).
29. The **main connective** is the last operator applied. Example: in ¬(p ∨ q), main connective is ¬.
30. Because each variable has 2 possible values; 2 × 2 × ... (n times) = 2ⁿ combinations.