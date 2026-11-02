# Bug Report: Product sort dropdown is unresponsive (problem_user)

**Website:** https://www.saucedemo.com
**Date found:** 2026-11-02
**Account used:** problem_user
**Environment:** Chrome on Windows 11
**Severity:** Medium
**Priority:** Medium

## Steps to reproduce
1. Go to https://www.saucedemo.com
2. Log in with username `problem_user` and the standard password
3. On the Products page, locate the sort dropdown (default: "Name (A to Z)")
4. Select a different option, e.g. "Price (low to high)"
5. Observe the product list order

## Expected behavior
Selecting a sort option should reorder the product list according to the chosen criteria (e.g. price ascending).

## Actual behavior
The dropdown doesn't update and remains frozen on "Name (A to Z)" and the product list order does not change.

## Evidence
go to the screenshots folder and click on 001-sort-dropdown.png

## Notes
- Login with `problem_user` works as expected; the issue is isolated to product sorting/filtering.
- Tested against the same flow with a 'standard_user' to confirm the sort works there, meaning that the sort not working in 'problem_user' is a bug.
