# Security policy

## Reporting a vulnerability

Please do not open a public issue. Use GitHub's private reporting instead: go to the **Security** tab of the affected repository and choose **Report a vulnerability**. Include the version or commit, a minimal program or steps to reproduce, and what you expect to happen.

We will acknowledge a report within a few days and keep you informed until it is fixed.

## What counts

Pelago is an early-stage language. Reports we especially want:

- the compiler producing code that violates memory safety or the overflow-trap guarantee for a program that type checks;
- the compiler, formatter or language server crashing, hanging or running out of memory on untrusted input;
- the language server or editor extensions running or exposing anything unexpected;
- problems in our release workflows or published packages.

## Supported versions

The project is pre-1.0. Only the latest commit on `main` and the latest release are supported.
