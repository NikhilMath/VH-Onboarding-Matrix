
# Onboarding Documentation

This documents onboarding provisions for all roles in the company.

## How to Find Provisions for a Role

Follow these steps to see what provisions are required for a new employee:

1. Go to the [`roles`](/roles/) folder in this repository.
2. Look for the file that matches the new employee’s job title.
3. Open that file to view all the provisions and resources needed for the role.

## Working with Variables

Variables in this system behave like variables in typical programming languages. When conflicts arise, the variable listed **last** takes priority and "wins" over earlier ones.

### Example:

- You can only assign **one HB1 license** per user.
- `const-base` assigns an HB1 *Teams* license.
- `const-dir` assigns an HB1 *Activity* license.

For a **Director of Construction**, the variable list might look like:

1. `const-base`
2. `const-dir`

Since `const-dir` appears last, its HB1 license (*Activity*) will override the earlier assignment (*Teams*) from `const-base`.
