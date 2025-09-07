# LLM Study Mode Prompt

[English](README.md) | [简体中文](README.zh.md)

A comprehensive tutoring prompt system designed specifically for Large Language Models, transforming AI into an effective and personalized learning tutor.

[>>> Get the prompt <<<](./study_mode.md)

## Overview

This project provides a complete prompt framework that helps Large Language Models assume the role of excellent learning tutors. Through carefully designed pedagogical principles and strict rule systems, AI can:

- 🎯 Inspire active learning instead of passive consumption
- 🧠 Foster deep thinking and metacognitive abilities
- 📚 Provide personalized learning experiences
- 🔍 Guide discovery through Socratic questioning
- 📋 Create and maintain structured learning roadmaps

This prompt is inspired by: [LearnLM Partner Prompt Guide](https://services.google.com/fh/files/misc/learnlm_prompt_guide.pdf)

## Core Features

### Teaching Philosophy

- **Inspire Active Learning**: Transform from passive recipient to active participant
- **Manage Cognitive Load**: Break down complex concepts into digestible steps
- **Deepen Metacognition**: Help learners understand their own learning process
- **Stimulate Curiosity**: Spark motivation through open-ended questions and real-world examples
- **Adapt to the Learner**: Dynamically adjust teaching strategies based on learner feedback

### Core Rules

- **Guided Teaching**: Never give direct answers, but guide discovery through questions
- **One Question at a Time**: Ask only one question at a time and wait for response
- **Learning Roadmaps**: Create and maintain structured learning plans for complex topics
- **Mastery Tracking**: Use `[m]` and `[~]` markers to track learning progress

### Example Conversation Starter

```
User: I want to learn about Python list comprehensions

AI: Excellent! List comprehensions are a fantastic and powerful feature in Python. They can feel a bit like a superpower once you get the hang of them.

To make sure I tailor this perfectly for you, could you tell me a little about your experience with Python? Are you a complete beginner, or are you already comfortable with the basics, like `for` loops and creating lists?

No matter your level, we'll get you writing clean and efficient list comprehensions in no time
```

## Teaching Method Examples

### Traditional Approach (Incorrect)

> List comprehension syntax is `[expression for item in iterable if condition]`...

### Study Mode Approach (Correct)

> Great question! Let's start with the basics. Are you already familiar with for loops? If you wanted to create a list of squares from 1 to 5 using a traditional for loop, how would you write that?

## License

This project is licensed under [GPL-3.0](LICENSE).

## Related Links

- [LearnLM Partner Prompt Guide](https://services.google.com/fh/files/misc/learnlm_prompt_guide.pdf)
- [Socratic Method](https://en.wikipedia.org/wiki/Socratic_method)
- [Metacognition](https://en.wikipedia.org/wiki/Metacognition)
