# Mini Library Management System
**Prepared for:** Person A
**Generated on:** 2025-10-29 17:38 UTC

## Overview
This project implements a lightweight Mini Library Management System in Python. It demonstrates core concepts such as CRUD operations for books and members, role-based access, borrowing/return logic, and simple in-memory data storage (no external DB required). The codebase is split into three main modules: `operations.py`, `Demo.py`, and `tests.py`.

## Files
- `operations.py` - Core logic: book/member management, borrow/return flows, search and authentication.
- `Demo.py` - Interactive command-line interface (menus for Admin / Staff / Student).
- `tests.py` - Basic assert-based tests covering add, borrow, return, delete flows.

## Features
- Add / Update / Delete books and members.
- Borrow and return books with borrow limits and due dates.
- Role-based menus for admin, staff, and students.
- Simple in-memory borrow history tracking.
- Defensive checks: prevent deletion of currently borrowed books/members.
- Easy to extend (e.g., swap in a database or a web UI).

## How to run
1. Ensure you have Python 3.8+ installed.
2. From the project folder run:
```bash
python Demo.py
```
3. To run the tests:
```bash
python tests.py
```

## Notes for Person A
- Designed for clarity and teachability — ideal for classroom demos or small prototypes.
- The borrow policy is configurable via constants in `operations.py` (`BORROW_LIMIT`, `BORROW_DAYS`).

---
*If you want a tailored README with your real name and contact details, tell me the exact info and I'll update these files.*
