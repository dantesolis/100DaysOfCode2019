# 100 Days of Code Log - 2019 EDITION BABY 🎉 (The Reckoning) 😜

**Inspiration:** Wanted to do continue on the path of learning and improving myself and since I couldn't decide how best to proceed, I asked those more knowlegeable than me - and my peeps 😀 🤗 - see the [tweet](https://twitter.com/dsbrux/status/1092845223414325249?s=20).
This time around I think I will be giving myself 1 day a week OFF, usually Sundays, but let's see where my obsession takes me 😅.

**Trello:** If you don't want to be reading this long log constantly. I'm creating and updating a **PUBLIC** - as in like the internet -  personal trello board. See it [here](https://trello.com/b/uxmRcL5M/roadmap-2019).

**NOTE:** I will be updating this readme as I go along; adding some fiiles, links, etc.., maybe even do some minor design or whatever, but wanted to get things started.

To get the actual count just run the following snippet:

```js
// # Note this is using flow. Remove the typechecking to run it on the console.

/* @flow */
const count = (days: number=0): number|string => {
  if (days) {
    return days;
  }
  return "Code me some ❤️❤️❤️❤️ (*finger snap*)";
}

console.assert(count() === 100, "Wrong"); // <= undefined :)
console.assert(count(100) === 0, "Wrong"); // <= Wrong
```

**Start Date** 06 Feb. 2019

**End Date** ...

**Total Days Done** ...

**Days Xtra to Add:** 1
  - DAY OFF - 10 Feb. Sunday
  - DAY OFF - 16 Feb. Sunday
  ---------------------------
  Total: 2

## Log

### Day 1: 06 Feb. Wednesday

**Today's Progress**:

- Started Section 4 of [The Complete NodeJs Developer Course 2](https://www.udemy.com/the-complete-nodejs-developer-course-2/learn/v4/t/lecture/5525228?start=0) Udemy Course.
  - [x] Setting up.

**Thoughts:** Spent some time setting repos (log + weather-app-node) and getting everything "ready". I have enrolled on this course last year and completed Sections 1 - 3. I had stopped at Section 4. So starting at the beggining of Section 4 again. 💪

**Link to work:**
  - [weather-node-app](https://github.com/dantesolis/weather-app-node)

<hr />

### Day 2: 07 Feb. Thursday

**Today's Progress**:

- Continued working on Section 4 of [The Complete NodeJs Developer Course 2](https://www.udemy.com/the-complete-nodejs-developer-course-2/learn/v4/t/lecture/5525228?start=0) Udemy Course.
  - [x] Async example.

- Read one page of Chapter 2 YDKJS Book 3: "This & Object Prototypes"
  - `this` All Makes Sense Now
    - Nothing but rules
      - [x]  Default Binding

**Thoughts:** Will like to write a blog post after I finish the chapter.

**Link to work:**
  - [weather-node-app](https://github.com/dantesolis/weather-app-node)

<hr />

### Day 3: 08 Feb. Friday

**Today's Progress**:

- Read 3 (pg 14 -17) pages of Chapter 2 YDKJS Book 3: "This & Object Prototypes"
  - `this` All Makes Sense Now
    - Nothing but rules
      - [x] Default Binding
      - [x] Implicit Binding

**Thoughts:** Will like to write a blog post after I finish the chapter or maybe sooner.

**Link to work:**
  - [weather-node-app](https://github.com/dantesolis/weather-app-node)  

<hr />

### Day 4: 09 Feb. Saturday

- Continued working on Section 4 of [The Complete NodeJs Developer Course 2](https://www.udemy.com/the-complete-nodejs-developer-course-2/learn/v4/t/lecture/5525228?start=0) Udemy Course.
  - [x] Call Stack and Event Loop
  
- Read 2 (pg 17 - 18) pages of Chapter 2 YDKJS Book 3: "This & Object Prototypes"
  - `this` All Makes Sense Now
    - Nothing but rules
      - [x] Default Binding
      - [x] Implicit Binding
      - [x] Explicit Binding

**Thoughts:** Learnt about implicit vs explicit binding. Thanks to the Udemy course understanding and because I'm happening to be reading the book and doing the course at the same time - **by coincidence** - I'm actually understanding better when and where to spot the `call-site`, `call-stack` of each `fn`, and how all this relates to the `event-loop` and the `node-apis` in Node.

**Link to work:**
  - [weather-node-app](https://github.com/dantesolis/weather-app-node)

<hr />

### Day 5: 10 Feb. Sunday

- DAY OFF

**Thoughts:** DAY OFF

**Link to work:** DAY OFF

<hr />

### Day 6: 11 Feb. Monday
  
- Read 2 (pg 18 - 19) pages of Chapter 2 YDKJS Book 3: "This & Object Prototypes"
  - `this` All Makes Sense Now
    - Nothing but rules
      - [x] Default Binding
      - [x] Implicit Binding
      - [x] Explicit Binding
        - [x] Hard binding

**Thoughts:** Learnt about explicit binding.

**Link to work:** None

<hr />

### Day 7: 12 Feb. Tuesday

- Continued working on Section 4 of [The Complete NodeJs Developer Course 2](https://www.udemy.com/the-complete-nodejs-developer-course-2/learn/v4/t/lecture/5525228?start=0) Udemy Course.
  - [x] Callback Functions & APIs

**Thoughts:** None

**Link to work:**
  - [weather-node-app](https://github.com/dantesolis/weather-app-node)

<hr />

### Day 8: 13 Feb. Wednesday

- Continued working on Section 4 of [The Complete NodeJs Developer Course 2](https://www.udemy.com/the-complete-nodejs-developer-course-2/learn/v4/t/lecture/5525228?start=0) Udemy Course.
  - [x] Pretty Printing Objects
  - [x] What Makes up an HTTP Request

- Read 1 (pg 19 - 20) page of Chapter 2 YDKJS Book 3: "This & Object Prototypes"
      - [x] ...
      - [x] Explicit Binding
        - [x] Hard binding cont

**Thoughts:** None

**Link to work:**
  - [weather-node-app](https://github.com/dantesolis/weather-app-node)

<hr />

### Day 9: 14 Feb. Thursday

- Install and set `dotenv` pkg to save and handle API keys on `weather-app-node` tryout node project.

- Read 3 (pg 19 - 21) pages of Chapter 2 YDKJS Book 3: "This & Object Prototypes"
      - [x] ...
      - [x] ...
        - [x] Hard binding cont
      - [x] New binding

**Thoughts:** None

**Link to work:**
  - [weather-node-app](https://github.com/dantesolis/weather-app-node)

<hr />

### Day 10: 15 Feb. Friday

- Today consisted on fixing come merge conflicts from the [weather-node-app](https://github.com/dantesolis/weather-app-node) and installing a new api key with MapQuestApi.

- Set my goals for my [Personal Growth Roadmap 2019](https://trello.com/c/WKgio367/2-goals-things-i-would-like-to-accomplish-in-this-period)'s 1st trimester (Feb - Apr)

```md
[ ] 3 Blog Posts
[ ] 2 Open Source contributions
[ ] 2 Books about personal stuff
[ ] 1 Book about programming
[ ] 1 Website/app possible to use frameworks
[ ] 1 Website using only VanillaJS and CSS3 no frameworks
[ ] 1 script | pkg that must be published to npm
[ ] 1 Design | Prototype in FramerX.
[ ] 1 Udemy Course about programming or design.
```

**Thoughts:** Not too much coding today. 

**Link to work:** See today's progress

<hr />

### Day 11: 16 Feb. Saturday

- Continued working on Section 4 of [The Complete NodeJs Developer Course 2](https://www.udemy.com/the-complete-nodejs-developer-course-2/learn/v4/t/lecture/5525228?start=0) Udemy Course.
  - [x] Encoding User Input

**Thoughts:** None

**Link to work:** None

<hr />

### Day 12: 17 Feb. Sunday

- DAY OFF

**Thoughts:** DAY OFF

**Link to work:** DAY OFF

<hr />

### Day 13: 18 Feb. Monday

- Continued working on Section 4 of The Complete NodeJs Developer Course 2 Udemy Course.
  - [x] Callback Errors

**Thoughts:** None

**Link to work:**
  - [weather-node-app](https://github.com/dantesolis/weather-app-node)

<hr />

### Day 14: 19 Feb. Tuesday

- Continued working on Section 4 of The Complete NodeJs Developer Course 2 Udemy Course.
  - [x] Abstracting Callbacks

**Thoughts:** None

**Link to work:**
  - [weather-node-app](https://github.com/dantesolis/weather-app-node)

<hr />

### Day 15: 20 Feb. Wednesday

- Worked on a FramerX styleguide and "Coming Soon" page prototype for a friend's site.
  - [x] Defined and created the Color Palette (Using Google Material Design) as inspiration/ref.

**Thoughts:** None

**Link to work:**
  - Will be publishing to Uplabs and/or Dribble once the StyleGuide is done. Site code to be hosted on gitlab.

<hr />

### Day 16: 21 Feb. Thursday

- Continued working on Section 4 of The Complete NodeJs Developer Course 2 Udemy Course.
  - [x] Abstracting Callbacks

**Thoughts:** None

**Link to work:**
  - ...

<hr />

### Day 17: 22 Feb. Friday

- ...

- ...

**Thoughts:** None

**Link to work:**
  - ...

<hr />

Made with ❤️ &copy; 2019 D/S 💯