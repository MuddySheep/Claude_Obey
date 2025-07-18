# Claude_Obey
# UNIVERSAL HARD RULES & CONSTRAINTS

## CRITICAL: These rules are **ABSOLUTE** and must **NEVER** be violated

---

## 1. Data Handling

- **NEVER** assume fixed counts, sizes, or structures—**always** process data dynamically.
- **ALWAYS** use actual, live data structures at runtime; no hardcoding or “magic numbers.”
- **MUST** process **all** relevant data; no silent truncation, sampling, or filtering unless explicitly specified.
- **NO** assumptions about where special cases, patterns, or exceptions may exist—**let the data reveal it**.

---

## 2. Analysis & Logic

- **ALWAYS** treat all cases, states, and positions equally until the data or logic justifies otherwise.
- **NO** pre-set logic based on previous projects, expectations, or legacy code—**start fresh**.
- **NO** imposing patterns, shortcuts, or thresholds unless *proven* in the current context.

---

## 3. Documentation & Tracking

- **UPDATE** project logs and todos after **every** meaningful task or change.
- **NEVER** defer documentation or changelog updates—**do it now**, not later.
- **NO** code, logic, or state change is complete until it’s tracked.

---

## 4. Validation

- **EVERY** output, change, or feature **must** be validated against *all* required cases before continuing.
- **NO** “good enough” or “works on my machine”—validation must be exhaustive across the defined scope.
- If **any** test fails or any required data is missing, the process is **not valid**—**fix it before proceeding**.

---

## 5. Implementation

- Code must support **dynamic data** and variable structure—**never** fixed sizes or hard limits.
- Use dynamic, language-native methods for sizing, iteration, and checks.
- **Test** on both smallest and largest observed inputs, and **anticipate future growth**.

---

## 6. Feature Design

- Features must be generic and support all relevant inputs or states.
- Use **relative logic** (e.g., ratios, dynamic indexing), **never** “if index > N”-style hardcoding.
- **NO** static or position-based constraints without explicit, current justification.

---

## 7. Testing

- **Test all cases**: full data range, all user states, all UI paths, all endpoints.
- **NO** “sample-only” or “partial” testing—**completeness required**.
- **ALWAYS** include edge cases, including smallest and largest input sizes and most unusual user behaviors.

---

## 8. Success Criteria

- **Define success concretely** (e.g., page load time under X ms, 0 errors in QA, 100% passing tests).
- **NO** vague “it’s better” or “seems faster”—**quantify** every claim.
- Solution must meet **ALL** success criteria for **ALL** cases in scope—**no exceptions**.

---

## 9. Communication

- **Communicate explicitly**: what you did, what you’re testing, what changed—never vague statements.
- **Report exact numbers** (items processed, tests run, failures found)—not just percentages or summaries.
- **Raise questions or blockers** immediately if anything is unclear.

---

## 10. Forbidden Practices

- ❌ Never hardcode array sizes, indexes, or business logic without dynamic checks.
- ❌ Never skip documentation, testing, or validation—even for “quick fixes.”
- ❌ Never advance stages/phases without prior phase signoff.
- ❌ Never make assumptions about user data, environment, or usage.
- ❌ Never hide, ignore, or workaround errors—**address and track every issue**.

---

## 11. Enforcement

If any rule is violated:
1. **Stop** and correct immediately.
2. Log the violation and its fix in the changelog.
3. **Revalidate** any affected work.
4. **Explicitly acknowledge** what went wrong and how it was fixed.

---

**REMEMBER:**  
Assumptions break software. Rigor, transparency, and real data are the only path to robust, maintainable code—**in any project, on any platform**.
