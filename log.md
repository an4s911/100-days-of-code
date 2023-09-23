# 100 Days Of Code - Log

## 2021

### Day 1: 13th October Wednesday

**Today's Progress**: I learned very basic stuff in JavaScript such as variables, comments, operators, conditionals etc.

### Day 2: 14th October Thursday

**Today's Progress**: Learned about the DOM, strategies to handle script loading (async, defer, DOMContendLoaded, etc.). And most importantly: 

"NOT TO USE INLINE JAVASCRIPT HANDLERS"

**Link to a tweet**: [Why you shouldn't use JavaScript Event Handlers?](https://twitter.com/an4s911/status/1448726492767301640)

### Day 3: 15th October Friday

**Today's Progress**: I worked a HTML and CSS project today just to repolish my skills as I am learning JavaScript. 

The project is a Tribute page but unlike others this is a tribute for a programming language, **C**.

**Link to Work**: [an4s911.github.io/tribute-page-c](https://an4s911.github.io/tribute-page-c). It is not responsive, but I am planning on doing that soon.

### Day 4: 16th October Saturday

**Today's Progress**: Learned about the `style` property for DOM objects in JS. And also by following the MDN docs I made a number guessing game with just HTML and JS (No styling).

**Thoughts**: While making the game learned about `Math.floor()` and `Math.random()` functions that are available built-in to browsers I guess.

**Link to Work**: [Number guessing game](https://an4s911.github.io/projects/number-guessing-game)

### Day 5: 17th Ocotober Sunday

**Today's Progress**: Understood the 2 types of errors, syntax errors and logical errors (or bugs as we call it).

**Thoughts**: Syntax errors are quite easy to tackle and fix becuase it provides an error message which can be looked up in a documentation or some online platform for a solution. 

But the logical errors could end up being a bit complicated. It could take some time to debug the problem (might take even hours or days). 

### Day 6: 18th October Monday

**Today's Progress**: Learned a bit more about variables. About `var` and `let` and their difference. And about the `const` keyword to declare constant values that wont change.

**Link to work**: Although I didn't work on any projects I did tweet something that beginners will find useful (hopefully): [Some online code editors for web development](https://twitter.com/an4s911/status/1450145042446827528?s=20https://twitter.com/)

### Day 7: 19th October Tuesday

**Today's Progress**: Covered basics maths in JS, a bit about strings and string methods and arrays and array methods. Covered a lot but didn't work on any project.

**Thoughts**: I thought of working on a project, but I didn't get time. Probably tomorrow. I have to complete an Assessment: the silly story generator, using javascript in MDN. I'll be doing that and work on a project tomorrow.

Although I did not do any projects I did write a blog. 

**Link to blog**: [Don't leave your functions without calling them](https://blog.anasbasheer.tech/dont-leave-your-functions)

### Day 8: 21st October Thursday

**Today's Progress**: Completed the Assessment *Silly Story Generator*.

**Link to work**: [Silly Story Generator](an4s911.github.com/projects/silly-story-generator/)

### Day 9: 31st October Sunday

Umm, I took a gap because life got in the way. 

For some time now I am really confused if I should continue with Web Development or go for some other area of computer science. I don't know because I think I am more interested in learning Python, C, the Assembly Language and get to the fundamentals of computers, and learn about Operating systems, learn how to make one, learn to make a programming language etc. I don't know. I am a bit confused.

But nevertheless I have decided that as I have already started learning JavaScript, I will just finish this then get into whatever else I wanna learn whether it be **C**, **Assembly** or anything else. 

So I will try to be consistent on JS from today hopefully.

**Today's Progress**: I completed my Final project for a CS course I started on June, Introduction to Computer Science by Harvard (*CS50x*) and got a certificate.

**Link to final project**: [CS50 Final Project](https://github.com/an4s911/cs50-final-project)

**Link to the Certificate**: [CS50 Certificate](https://certificates.cs50.io/e2a09a0a-599f-49d3-8f93-2e4240f8fed1)

### Day 10: 2nd November Tuesday

**Today's Progress**: I learned conditionals in JavaScript such as `if...else if...else` statements. The `switch...case...default` statements. And the *ternary or conditional operator* with the `?:` syntax.

I did the first task on conditionals on the MDN site. I have to complete the others.

### Day 11: 3rd November Wednesday

**Today's Progress**: I completed 2 other tasks on conditionals. 

And I completed the Looping code, learnt `for` loops, `while` loops and `do...while` loops.

<!-- **Thoughts:** I really struggled with CSS, but, overall, I feel like I am slowly getting better at it. Canvas is still new for me, but I managed to figure out some basic functionality. -->

## 2023

### Day 12: 21st September Thursday

Basically I'm gonna continue 100daysofcode from here. And I will just log my progress here. Currently I am doing TheOdinProject. And I am doing the Full Stack Javascript path. And I am in the javascript course. The last lesson I completed was the Tic Tac Toe project.

And today I am going through the lesson ***Classes***.

**List of things I learned today**:
- Javascript class getters and setters (property accessors)
    - I can also define setters and getters using `defineProperty`:
    - `Object.defineProperty(obj, 'propName', {get() {...}, set(value){...}});`
- Basic syntac for classes
    - Class expressions - just like functions classes can be defined inside other expression, passed around, returned assigned, etc.
    - Classes can have getters and setters as well
    - Computed names[...], this is weird and pretty cool:
        ```
        class User {
            ['say' + 'Hi']() {
                alert("Hello");
            }
        }
        
        new User().sayHi(); // alerts Hello
        ```
    - Class fields: basically the properties of the object
    - static class fields using the `static keyword`
        - they are accessed on the class not the instances
    - private class members or properties can be created using a hash `#` prefix
        - constructors cannot be private
    - static initialization blocks

### Day 13: 23rd September Saturday

So I didn't get time to do anything yesterday, so I am continuing today from where I left off in the *Classes* lesson.

**Things learned today:**
- Continuation static initialization blocks
- Class methods
- Class inheritance using the `extends` keyword
- The weird thing about `this` in class methods:
    - So in class methods `this` refers to the instance of the class that is used to call the method
    - but if the method is assigned to a variable then `this` will become undefined
    - similar behavior with `static` methods as well.
        - in `static` methods `this` refers to the class itself
        - and similarly, if the method is assigned to a variable then `this` becomes `undefined`
- different ways of using `extends`:
    - extend plain objects
    - built-in objects
    - Extending `Object`
    - Species:
        - using `Symbol.species`
    - ***Mix-ins*** 
- Using composition instead of inheritance
- Finally completed the *Classes* lesson.
