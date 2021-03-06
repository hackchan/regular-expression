# REGULAR EXPRESSION

regular-expression is a repository of regex reference

## Starting π

# Basic Matches

```sh
 .    Any Character, except new line
\d    Any Digits (0-9)
\D    it is not a digit (0-9)
\w    Word Character (a-z, A-Z, 0-9, _)
\W    Not a Word Character.
\s    Spaces of any kind. (space, tab, newline)
\S    It is not a Space, Tab or new line.
```

# Limits

```sh
\b Word Limit
\B Not a Word Limit
^  Beginning of a text string
$  End of a text string
```

# Quantifiers

```sh
*     0 or More
+     1 or More
?     0 or One
{3}   Exact Number
{3,4} Number Range (Minimum, Maximum)
```

# Character Sets

```sh
[]  Characters within brackets
[^] Characters that ARE NOT inside the brackets
```

# Groups

```sh
( )  Group
|    One or another
```

## practicing

practice one: [`ip valid`](https://regexr.com/6c9h8) regular expression.

```sh

/^(\d{1,3}\.){3,3}(\d{1,3})$/gm
```

## Built withπ οΈ

- [Nodejs](https://nodejs.org/es/) - is a runtime environment for JavaScript built with V8

## Wiki π

You can find much more about how to use this project in our [Wiki](https://github.com/hackchan/regular-expression/wiki)

## Versioned π

We use [SemVer](http://semver.org/) for versioning. for all available versions see the [tags in this repository](https://github.com/hackchan/regular-expression/-/tags).

## Authors βοΈ

- **Fabio Rojas** - Fullstack Development - [hackchan](https://gitlab.com/hackchan)

## license π

This project is under the MIT License - see the [LICENSE.md] (LICENSE) file for details

## Expressions of Gratitude π

- Tell others about this project π’
- Invite someone from the team to have a beer πΊ or a coffee β.
- Give thanks publicly π€.
- etc.

---

β¨οΈ with β€οΈ by [hackchan] (https://gitlab.com/hackchan) π
