# Recruitment test

## About the input

The input is made of three sections.

The first one has a number *n* with the number of lines that the first section will have.

Then comes *n* lines, each one with a number *i* and a string *s* in the following format: *i*-*s*. The number is just an identifier that you are going to use later to link each career position in order to build a path. The string is the name of the career position.

A number *e* comes and *e* lines follows it, containing two numbers, *j* and *k*, that represents the identifier of the career position.

Then comes a number *a* and the following *a* lines must be answered with a possible career path.

Example:
```
3
1-High School Graduate
2-Bachelor of Computer Science
3-Software Engineer
2
1 2
2 3
John is a High School Graduate and wants to become a Software Engineer
```

Can be answered with:
`High School Graduate - Bachelor of Computer Science - Software Engineer`

There's no required format for the answer. There might be multiple answers and it's up to you to choose one.

## More info

* You can use any language.
* The idea is more important than the correctness of the answers.
* Test your code.
