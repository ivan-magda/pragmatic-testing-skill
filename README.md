# Pragmatic Testing

An agent skill for reviewing test value, choosing test doubles, and removing redundant tests with evidence that regression protection remains intact.

## Install

Run in your project directory:

```sh
npx skills add https://github.com/ivan-magda/pragmatic-testing-skill --skill pragmatic-testing
```

## Use

Ask your agent:

> Audit this project's tests using pragmatic-testing. Identify duplicate, brittle, and low-value tests. Explain each finding and the regression protection that must remain before making changes.

## Source

The SKILL.md file is an unchanged copy of [sergdort's gist](https://gist.github.com/sergdort/bf5bc692937f9789e4a121ecb47be6ed), pinned to revision `2e6861e28988088c0e5ba9fc9bc2d89fc332c45f`.
The original skill credits [Orta Therox's Pragmatic Testing](https://github.com/orta/pragmatic-testing).

Installation uses the [Vercel skills CLI](https://github.com/vercel-labs/skills).
