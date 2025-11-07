# Frontend Mentor - Social links profile solution

This is a solution to the [Social links profile challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-links-profile-UG32l9m6dQ). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

### Built with

- Semantic HTML5 markup
- CSS custom properties and nested selectors
- Flexbox
- Mobile-first workflow


### What I learned
- CSS nested selectors are not mainstream yet, expected full baseline support from mid 2026.
- Transition with delay timers were fun to know, Check them below
```text
  - hover/focus state: transition: color 90ms ease-out, background-color 90ms ease-out;
  - resting state (default rule): transition: color 350ms ease-in 60ms, background-color 350ms ease-in 60ms;

  Hover enter (fast, no delay)
  time →  0ms          90ms
          |------------>|
          start        finish
          (ease-out: quick snap then slow settle)

  Hover leave (pause + slow fade)
  time →  0ms     60ms                      410ms
          | delay |----------- 350ms -------->|
          leave   transition start           finish
          (ease-in: gentle ramp from zero back to base)

```
