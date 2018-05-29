# tech-read-list
A list of great resources (books, blog posts, essays..) about coding, startups and philosophy that deserve to be read. 



## Engineering
- The Twelve Factor App [[original - EN]](https://12factor.net/)/[[FR]](https://12factor.net/fr/)


## Becoming a better codeur
- [Clean code javascript](https://github.com/ryanmcdermott/clean-code-javascript)
- [Javascript Linting: What Developers Need to Know](http://mikecavaliere.com/javascript-linting-what-developers-need-to-know/)


## Essays
- How to become a Hacker - Eric S. Raymond [[original - EN]](http://www.catb.org/esr/faqs/hacker-howto.html)/[[FR]](http://thomasgil.com/hacker.html)

- Rammen profitable - Paul Graham [[original - EN]](http://www.paulgraham.com/ramenprofitable.html)


## Random thoughts
- building a static version [of a React component] requires a lot of typing and no thinking, and adding interactivity requires a lot of thinking and not a lot of typing. (From React docs)

- About Django project structure :  
Does my model contain methods that do more than managing database state? You should extract a command.  
Does my model contain properties that do not map to database fields? You should extract a query.  
Does my model reference infrastructure that is not my database (such as mail)? You should extract a command. 

- In JavaScript, there are six falsy values: false, 0, '' (empty string), null, undefined, and NaN. Everything else is truthy.

- [You aren't gonna need it
](https://en.wikipedia.org/wiki/You_aren%27t_gonna_need_it)

- [Don't Repeat Yourself](https://en.wikipedia.org/wiki/Don%27t_repeat_yourself)

- Good coders code, great coders reuse.

- [Make It Work Make It Right Make It Fast](http://wiki.c2.com/?MakeItWorkMakeItRightMakeItFast)

- Software, at the micro-level, challenges the common belief, "If you can't do it right the first time, when will you have time to do it over?" Experimentation is needed to determine what is "right" whether one does the experimentation in one's mind or by trying different versions of the code. It usually takes longer to get that mental model right and only have to type the code in once, then to try a version of the code and do it over as needed. -- WayneMack

- Test cases should *NEVER* include algorithms. We are trying to test algorithms with hard values, not use algorithms to test algorithms. The expected values used in test cases should be figured out by the programmer *OUTSIDE* of the program and hard-coded into the test. You can pull the hard-coded values into variables if you wish, but there should be no algorithms performed to create the values. If you use an algorithm (math, loops, conditionals) for an expected value in a test, then you'll need a test to test the expected value algorithm in order to trust that it's correct, or else why are you writing tests? When all your expected values are hard-coded then there's no room for programmatic error and that test can be trusted.
