# Courses

* Markdown-based
* Auto-generated TOC

Course player: Navigate student through a course, in sequence.

* Keep track of progress
* Award achievements
* Keep track of exercises and results


## Lessons

### Slide based lesson player with:

* [Markdown-based source](https://github.com/gnab/remark)
* Video embeds (YouTube, Vimeo)
* Interactive code embeds (JSBin?)
* Embeddable exercises


### Exercises

Dynamically generate exercises based on a knowledge graph.

```js
{
  term: ``,
  definition: ``
  doc: ``,
  examples: [
    ``,
    ``,
    `...`
  ],
  counterExamples: [
    ``,
    ``,
    `...`
  ]
}
```

This supports explainers, where a term, definition, and supporting documentation are displayed, matching games where the student matches terms with the correct definitions, multiple choice questions where the student picks correct examples from a list of examples and counter-examples, etc...
