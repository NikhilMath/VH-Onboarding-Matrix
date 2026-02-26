
# Onboarding Documentation

This documents onboarding provisions for all roles in the company.

## How To Use This Repo

### Finding provisions for roles/titles
- Open the [`roles`](/roles/) folder
- Open the file that corrisponds to the title of new employee to view provisions needed

### Working with Variables

Variables in this system behave like variables in typical programming languages. When conflicts arise, the variable listed **last** takes priority and "wins" over earlier ones.

#### Example:

- You can only assign **one HB1 license** per user.
- `const-base` assigns an HB1 *Teams* license.
- `const-dir` assigns an HB1 *Activity* license.

For a **Director of Construction**, the variable list might look like:

1. `const-base`
2. `const-dir`

Since `const-dir` appears last, its HB1 license (*Activity*) will override the earlier assignment from `const-base`.
