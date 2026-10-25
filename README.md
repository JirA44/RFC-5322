# RFC 5322 — format des messages Internet / Internet Message Format

## Français — présentation

RFC 5322 définit le format des messages électroniques Internet, notamment les champs d’en-tête et la structure générale d’un message.

### À quoi ça sert, et pourquoi ?

Il sert de référence lors de la création ou de l’analyse de messages compatibles avec les systèmes de courrier électronique. Le respect de la syntaxe aide les logiciels à interpréter les champs et leur ordre.

### Exemple

Parser un message brut de test pour extraire From, To, Subject, Date et les champs de contenu, puis comparer le résultat aux règles de la RFC.

Ce dépôt ne contient actuellement qu’un titre. Vérifier le texte officiel de la RFC et les bibliothèques utilisées avant d’implémenter un parseur complet.

## English — overview

RFC 5322 defines the Internet Message Format for email, including header fields and the overall structure of a message.

### What is it for, and why use it?

It is a reference for creating or parsing messages that need to interoperate with email systems. Following the syntax helps software interpret fields and their ordering.

### Example

Parse a raw test message to extract From, To, Subject, Date and content fields, then compare the output with the RFC rules.

This repository currently contains only a title. Check the official RFC text and the libraries you use before implementing a complete parser.
