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
  - DAY OFF - 24 Feb. Sunday
  - DAY OFF - 03 Mar. Sunday
  - DAY OFF - 17 Mar. Sunday
  - DAY OFF - 24 Mar. Sunday
  ---------------------------
  Total: 6

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
  - [weather-node-app](https://github.com/dantesolis/weather-app-node)

<hr />

### Day 17: 22 Feb. Friday

- Continued working on Section 4 of The Complete NodeJs Developer Course 2 Udemy Course.
  - [x] Chaining Callbacks

**Thoughts:** None

**Link to work:**
  - [weather-node-app](https://github.com/dantesolis/weather-app-node)

<hr />

### Day 18: 23 Feb. Saturday

- Worked on a friend's site/business.
  - [x] Created Business Card on Sketch. 

**Thoughts:** First time using sketch app and getting my feet wet with the tool. Need to practice more.

**Link to work:**
  - Once it's finished and approved. Design will go to the sketch cloud.

<hr />

### Day 19: 24 Feb. Sunday

- DAY OFF

**Thoughts:** DAY OFF

**Link to work:** DAY OFF

<hr />

### Day 20: 25 Feb. Monday

- Continued working on Section 4 of The Complete NodeJs Developer Course 2 Udemy Course.
  - [x] ES6 Promises

- Read 4pg YDKJS Book 3 (pg22 - 26) 
  - [x] Everything in order: Rules of `this`

**Thoughts:** None

**Link to work:**
  - [weather-node-app](https://github.com/dantesolis/weather-app-node)

<hr />

### Day 21: 26 Feb. Tuesday

- Read 3pgs YDKJS Book 3 (26 - 29) 
  - [x] Determining `this`: Rules of `this`
  ```js
    // order of priority for determining what `this` refers to on  
    // call-site
    new binding => explicit binding => implicit binding => default binding
  ```
  - [x] Binding exceptions

**Thoughts:** None

**Link to work:**
  - None

<hr />

### Day 22: 27 Feb. Wednesday

- Continued working on Section 4 of The Complete NodeJs Developer Course 2 Udemy Course.
  - [x] Advanced Promises

**Thoughts:** None

**Link to work:**
  - [weather-node-app](https://github.com/dantesolis/weather-app-node)

<hr />

### Day 23: 28 Feb. Thursday

- Continued working on Section 4 of The Complete NodeJs Developer Course 2 Udemy Course.
  - [x] Weather App With Promises
  - [x] Extra Features

**Thoughts:** None

**Link to work:**
  - [weather-node-app](https://github.com/dantesolis/weather-app-node)
<hr />

### Day 24: 01 Mar. Friday

- Started working on Section 5 of The Complete NodeJs Developer Course 2 Udemy Course. 💪
  - [x] Section Intro
  - [x] Hello Express

**Thoughts:** Loving the course

**Link to work:**
  - [node-web-server](https://github.com/dantesolis/node-web-server)

<hr />

### Day 25: 02 Mar. Saturday

- Started and finished Section 1 and started Section 2 of The Complete NodeJs Developer Course 3rd Edition Udemy Course. 💪
  - [x] Section 1
  - [x] First 2 videos on Section 2 *See note*

  **_Note_:** The Course content got updated and I "lost" all previously watched tracks. 😢 Don't know if to be upset or excited 🤔. Could I be both ? 😀 Previously started **Section 5** got bumped to **Section 7** on this new edition. Will most probably continue to **Section 7** and then move backwards.

- Worked on a friend's site/business.
  - [x] Worked on Business Card on Sketch. 


**Thoughts:** None

**Link to work:**
  - Business card Design: Once it's finished, design will go to the sketch cloud and will be shared.
  - [node-web-server](https://github.com/dantesolis/node-web-server)

<hr />

### Day 26: 03 Mar. Sunday

- DAY OFF

**Thoughts:** None

**Link to work:**
  - DAY OFF

<hr />

### Day 27: 04 Mar. Monday

- Started Section 7 of The Complete NodeJs Developer Course 3rd Edition Udemy Course.
  - [x] Section Intro: Web Servers
  - [x] Hello Express

- Read **3** page YDKJS Book 3 (29 - 31) 
  - [x] Indirection
  - [x] Softening Binding

**Thoughts:** Started Section 7 (this was Section 5 on the 2nd Edition). Gonna continue working from this section and then move backwards.

**Link to work:**
  - [node-web-server](https://github.com/dantesolis/node-web-server)

<hr />

### Day 28: 05 Mar. Tuesday

- Read **3** page YDKJS Book 3 (31 - 33) 
  - [x] Lexical this

**Thoughts:** Need to review & write a blog post about the rules of binding `this` with `bind()` binding vs. lexically binding `this` with either arrow functions or with `var self = this`. Which basically enforces me to scape from undersating the `this` binding, when I want to embrace 🤗 and 🧡 it.

**Link to work:**
  - None

<hr />

### Day 29: 06 Mar. Wednesday

- Read **2** page YDKJS Book 3 (33 - 34) 
  - [x] Review of `this` binding rules

- Continue working on Section 7 of The Complete NodeJs Developer Course 3rd Edition Udemy Course.
  - [x] Serving up HTML and JSON

- Started working on a `create-necessary-files-cli` in node for setting files on newly created repo.

- Worked on a friend's site/business.
  - [x] Finished on Business Card on Sketch.


**Thoughts:**

**Link to work:**
  - [node-web-server](https://github.com/dantesolis/node-web-server)
  - [scripts](https://github.com/dantesolis/scripts)

<hr />

### Day 30: 07 Mar. Thursday

- Read **6** pages from YDKJS Book 3 (35 - 41)
  - [x] Chapter 3
    - [x] Syntax
    - [x] Type
    - [x] Built-in Objects
    - [x] Content
    - [x] Computed Property Names

**Thoughts:** ❤❤❤❤ this series

**Link to work:**
  - None

<hr />

### Day 31: 08 Mar. Friday

- Continue working on Section 7 of The Complete NodeJs Developer Course 3rd Edition Udemy Course.
  - [x] Serving up Static Assets (`html`)

**Thoughts:** None

**Link to work:**
  - [node-web-server](https://github.com/dantesolis/node-web-server)

<hr />

### Day 32: 09 Mar. Saturday

- Continue working on Section 7 of The Complete NodeJs Developer Course 3rd Edition Udemy Course.
  - [x] Serving up CSS, JS, Images and more.
  - Learnt about how to create an "easteregg" on the `console` with react and typescript.

- Read **3** pages from YDKJS Book 3 (41 - 43)
  - [x] Chapter 3
    - [x] ...
    - [x] Property vs. Method

**Thoughts:** None

**Link to work:**
  - [node-web-server](https://github.com/dantesolis/node-web-server)

<hr />

### Day 33: 10 Mar. Sunday

- Worked on Framer X prototype for a wallpaper for future framer-x brussel design meetup.

**Thoughts:** None yet.

**Link to work:**
  - None yet.

<hr />

### Day 34: 11 Mar. Monday

- Continued on Framer X prototype for a wallpaper for future framer-x brussel design meetup.

- Read **8** pages from YDKJS Book 3 (43 - 51)
  - [x] Chapter 3
    - [x] Arrays
    - [x] Duplicating Obj.
    - [x] Property Descriptors
    - [x] Immutability

**Thoughts:** None yet.

**Link to work:**
  - None yet.  

<hr />


### Day 35: 12 Mar. Tuesday

- Finished Framer X prototype wallpaper for the [Brussels Framer-X  meetup](https://www.meetup.com/Brussels-FramerX/events/259701919/?isFirstPublish=true).
- Started another prototype for the Meetup. 1 of 4. 
  - [ ] 1. Simple wallpaper with 2 components
    - [x] Created Heading SubHeading components in `typescript` and converted those into `functional components
  - [ ] 2. Activy Bar (icons + animations)
  - [ ] 3. Mini Picture app 

**Thoughts:** None yet.

**Link to work:**
  - None yet.  

<hr />

### Day 36: 13 Mar. Wednesday

- Read **5** pages from YDKJS Book 3 (52 - 56)
  - [x] Chapter 3
    - [x] ...
    - [x] Immutability
    - [x] [[Get]]
    - [x] [[Put]]
    - [x] Getters && Setters
    - [x] Existence

**Thoughts:** None

**Link to work:**
  - None

<hr />

### Day 37: 14 Mar. Thursday

- Read **2** pages from YDKJS Book 3 (57 - 59)
  - [x] Chapter 3
    - [x] ...
    - [x] Existence
      - [x] Enumeration

**Thoughts:** None yet.

**Link to work:**
  - None

<hr />

### Day 38: 15 Mar. Friday

- Read **4** pages from YDKJS Book 3 (59 - 62)
  - [x] Chapter 3
    - [x] ...
    - [x] Iteration

**Thoughts:** None.

**Link to work:**
  - None.

<hr />

### Day 39: 16 Mar. Saturday

- Read **4** pages from YDKJS Book 3 (63 - 67)
  - [x] Chapter 3
    - [x] Review
  - [x] Chapter 4: Mixing (Up) "Class" Objcts
    - [x] Class Theory

**Thoughts:** None.

**Link to work:**
  - None.

<hr />

### Day 40: 17 Mar. Sunday

-  DAY OFF

**Thoughts:** DAY OFF

**Link to work:**
  - DAY OFF

<hr />

### Day 41: 18 Mar. Monday

- Continue working on Section 7 of The Complete NodeJs Developer Course 3rd Edition Udemy Course.
  - [x] Dynamic Pages with Templating
- Read **1** page from YDKJS Book 3 (67 - 68)
  - [x] Chapter 4: Mixing (Up) "Class" Objcts
    - [x] Class Design Pattern
    - [x] Javascript "Classes"

- Did *2** videos of freecodecamp "css-grids"

- Worked on a typeform for the up coming Framer X event.

**Thoughts:** None

**Link to work:**
  - [node-web-server](https://github.com/dantesolis/node-web-server)

<hr />

### Day 42: 19 Mar. Tuesday

- Continue working on Section 7 of The Complete NodeJs Developer Course 3rd Edition Udemy Course.
  - [x] Customizing the Views Directory.

- Did *2** videos of freecodecamp "css-grids"

- Read **2** page from YDKJS Book 3 (68 - 70)
  - [x] Chapter 4: Mixing (Up) "Class" Objcts
    - [x] Class Mechanics

**Thoughts:** None

**Link to work:**
  - [node-web-server](https://github.com/dantesolis/node-web-server)

<hr />

### Day 43: 20 Mar. Wednesday

- Read **1** page from YDKJS Book 3 (70 - 71)
  - [x] Chapter 4: Mixing (Up) "Class" Objcts
    - [x] Constructor

**Thoughts:** None

**Link to work:**
  - None

<hr />

### Day 44: 21 Mar. Thursday

- Did **3** exercises of freecodecamp "css-grids"
- Busy day today 😢. Will probably read some `YDKJS` on the 🚌

**Thoughts:** None

**Link to work:**
  - None

<hr />

### Day 45: 22 Mar. Friday

- Did **3** exercises of freecodecamp "css-grids".

- Did 1 page of `GraphQL.js` tutorial
  - [x] Getting started with [graphql]((https://graphql.org/graphql-js/).)

- Cleaned 10 outdated `gh-repos` on my github.

**Thoughts:** None

**Link to work:**
  - None

<hr />

### Day 46: 23 Mar. Saturday

- Did **2** exercises of freecodecamp "css-grids".
- Did 1 page of `GraphQL.js` tutorial
  - [x] Running an Express [graphql server](https://graphql.github.io/graphql-js/running-an-express-graphql-server/))
- Read **4** pages from YDKJS Book 3 (71 - 75)
  - [x] Chapter 4: Mixing (Up) "Class" Objcts
    - [x] Class Inheritance
    - [x] Polymorphism

**Thoughts:** None

**Link to work:**
  - None

<hr />

### Day 47: 24 Mar. Sunday

- DAY OFF 🏡❤️😍 also  🍟🛋 😍

**Thoughts:** DAY OFF

**Link to work:**
  - DAY OFF

<hr />

### Day 48: 25 Mar. Monday

- Did **2** exercises of freecodecamp "css-grids".
- Did 1 page of `GraphQL.js` tutorial
  - [x] [GraphQl Client](https://graphql.github.io/graphql-js/graphql-clients/)
- Read **1** page from YDKJS Book 3 (75 - 76)
  - [x] Chapter 4: Mixing (Up) "Class" Objs
    - [x] Multiple Inheritance

**Thoughts:** None

**Link to work:**
  - None

<hr />

### Day 49: 26 Mar. Tuesday

- Worked on a `mdx-deck` presentation for the framer-x meetup group. Falling more in :heart_eyes:with this library.
- Created some small components in `Framer X` for the demo

**Thoughts:** deck-yourself ?

**Link to work:**
  - None

<hr />


### Day 50: 27 Mar. Wednesday

- Did 1 page of `GraphQL.js` tutorial
  - [x] [Basic Types](https://graphql.github.io/graphql-js/basic-types/)

**Thoughts:** None

**Link to work:**
  - None

<hr />


### Day 51: 28 Mar. Thursday

- Did **2** exercises of freecodecamp "css-grids".

**Thoughts:** Easy day today, this weekend will tackle more stuff.

**Link to work:**
  - Easy day today.

<hr />


### Day 52: 29 Mar. Friday

- Read **8** pages from YDKJS Book 3 (76 - 84)
  - [x] Finished Chapter 4: Mixing (Up) "Class" Objs
    - [x] Mixins: `Explicit` vs `Implicit`


**Thoughts:** I ❤️ JS more and more man.

**Link to work:**
  - None

<hr />

### Day 53: 30 Mar. Saturday

- ...

**Thoughts:** ...

**Link to work:**
  - ...

<hr />

### Day 54: 31 Mar. Sunday

- ...

**Thoughts:** ...

**Link to work:**
  - ...

<hr />

Made with ❤️ &copy; 2019 D/S 💯