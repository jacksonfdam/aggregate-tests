# DDD Aggregate tests

This repository has as its porpuse test an implementation of a DDD Aggregate.

## Domain

- In this domain, we can have questions, and each question has possible answers;
- Each question can have a maximum of 10 possible answers;
- A question can be of the following types:
    - SelectOne: In HTML, this could be a radio input for each answer
    - SelectMultiple: In HTML, this could be a checkbox input for each answer
    
## Use cases

So far, the following use cases are implemented:

1. Add question
    - When adding a question, you msut provide:
        1. its type;
        2. its prompt;
        3. if it is required or not;
        4. its answers.
2. Remove question
    - When removing a question, all of its answers are also removed. You must provide:
        1. The question ID.
