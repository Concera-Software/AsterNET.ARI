# Concera.AsterNET.ARI

A .NET client library for developing applications using the
Asterisk REST Interface (ARI) and Stasis.

## About this fork

Concera.AsterNET.ARI is an independently maintained fork of
[AsterNET.ARI](https://github.com/skrusty/AsterNET.ARI).

This fork aims to:

- Support current Asterisk ARI versions.
- Keep actions, events and models synchronized with Asterisk.
- Maintain the existing `AsterNET.ARI` namespaces for compatibility.
- Modernize the library and its dependencies.
- Fix defects discovered while using ARI in production.

This project is maintained by
[Concera Software](https://github.com/Concera-Software).
It is not an official Asterisk or AsterNET project.

## Migration from AsterNET.ARI

Concera.AsterNET.ARI retains the existing `AsterNET.ARI` namespaces.
Replace the package reference; existing using directives should generally
not require changes.

## Attribution

This project is based on AsterNET.ARI, originally created by Ben Merrills and its contributors.
