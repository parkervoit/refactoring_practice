# Refactoring: Creating Clean Code
The purpose of refractoring is to fight technical debt. It turns messy code that is hard to understand and slow to run into clean code.
## Why is it important?
- Clean code is readable and obious for other programmers
    - makes it easier for collaboration 
- Clean code doesnt contain duplication
    - duplicates make updates more difficult and make processes slower
- Clean code contains a minimal number of classes and other moving parts
    - less code means less bugs, less things to remember, easier to work with. simple is easy
- Clean code passes all tests 
    - simple code that works 100% of the time is the ideal 
- Clean code is easy to mantain
    - clean, simple, and readable code is easier to parse and make edits to
## What is Technical Debt?
Building full functional programs or pipelines are like building a house. You need a strong foundation to build the rest of your house off of. Technical debt is when you build off of a shoddy foundation, and just add things on whether or not they are stable. 

Tech debt is the accumulation of inefficient processes over time. 

### Causes of Tech Debt
- Business Pressure
    - sometimes your company wants you to roll out features before theyre completely finished. Patches will appear to hide the unfinished code
- Ignorance of the consequence
    - employers may not understand how tech debt accumlulates, or why refactoring for scalability is important
- Failing to combat the strict coherence of components
    - This is when a project is one whole chunk, rather than the product of individual modules. 
    - Break it down into parts for the sake of isolation
- Lack of tests
    - Test constantly for feedback. You need to know what your code is doing. 
- Lack of documentation
    - slows down the introduciton of new people to the project. Can also cripple a project if people leave
- Lack of interaction between team members
    - You need good communication to distribute project knowledge
    - Your team needs to know how the project works. They cant work on it if they dont even know what it is
- Long term simultaneous development in several branches
    - basically, if you have 4 versions of a project accumulating tech debt and then try to merge them, you'll get 4 times as much tech debt
- Delayed refactoring
    - if you wait to refacotr code to be more efficent, it'll be harder to fix
- Lack of compliance monitoring
    - You need to ensure that everyone is following the same design methodology and variable nomenclatures
- Incompetence
    - Someone just doesnt know how to write good code. 
## When to Refractor
### Rule of Three
1. When youre doing something for the first time, just get 'er done
2. Do it again and start criticizing your code on how to improve
3. Refractor your code to a more efficient approach
### When adding a feature
- Refactoring can help you understand someone *else's* code
- Simple code means its simpler to add features
### When fixing a bug
- Dirty code is like a dirty room. It collects bugs. Clean it up and you'll figure out why you're getting bugs
- It helps prevent the need for refactoring in the future. Makes your boss nice and happy. Solve problems before they occur
### During a code review
- Make your code look clean and tidy before you present tit to people
- get a second pair of eyes before you present and work with someone to help clean it up
