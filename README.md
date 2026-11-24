# Bank System: C++ Console Application

An educational console banking simulation built with C++ and object-oriented classes. It uses local text files for persistence rather than a database or external banking service.

## Features represented in the source

- Client lookup, creation, updates, and deletion.
- User management and permission checks.
- Deposits, withdrawals, balance views, and transfers.
- Transfer and login records.
- Currency lists, exchange-rate updates, and conversion calculations.
- Shared validation, string, and date helpers.

## Structure

The application source is in `Project 3 Bank System  UI  Main Menu/`. Screen classes separate console menus from client, user, and currency models. The entry point is the C++ file with the same project name.

## Run locally

1. Use Windows and Visual Studio 2022 with the Desktop development with C++ workload and the v143 toolset.
2. Open the root `.sln` file.
3. Build the C++ project.
4. Set the working directory to the source-project folder containing the text data files before running. Check that required headers resolve in your local toolchain.

The project includes text files for users, clients, currencies, and activity logs. Treat them as demonstration data only. Do not enter real customer details or reuse real passwords.

## Scope and limitations

This project demonstrates console workflows, OOP, and file handling. It is not a real banking system, and its local-file authentication/storage should not be used for sensitive data. Automated tests are not included. A successful build or runtime test is not claimed by this documentation.
