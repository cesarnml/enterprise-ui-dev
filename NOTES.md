# Enterprise UI Development

- [Enterprise UI Development](#enterprise-ui-development)
  - [Lessons](#lessons)
  - [Notes](#notes)

## Lessons

- [X] ~~*Lesson 01: Introduction*~~ [2023-06-22]
- [X] ~~*Lesson 02: What is Enterprise UI Development*~~ [2023-06-22]
- [X] ~~*Lesson 03: Tools for the Course*~~ [2023-06-22]
- [X] ~~*Lesson 04: Types of Tests*~~ [2023-06-22]
- [X] ~~*Lesson 05: Setup Unit Testing with Vitest*~~ [2023-06-22]
- [ ] Lesson 06: Vitest UI
- [ ] Lesson 07: Unit Testing Exercise
- [ ] Lesson 08: Unit Testing Solution
- [ ] Lesson 09: Async & Asymmetric Tests
- [ ] Lesson 10: Asymmetric Matching Exercise
- [ ] Lesson 11: Asymmetric Matching Solution

## Notes

- To make `test, it, expect` global

```ts
// vitest.config.jts
import { defineConfig } from 'vitest/config';

export default defineConfig({
  test: {
    globals: true,
  },
});
```

and 

```json
// tsconfig.json
{
  "compilerOptions": {
    "types": ["vitest/globals"]
  }
}
```