# Clean Assets folder

My very own setup for most of front-end/designy stuff I work on.

Latest version: 05.11.2014
License: What? If it helped, you're welcome. Use what you want.

## The story

We started this repository with [Matej](http://hrescak.com/) some time in 2012, because of the very same reasons why it exists right now, but then it kind of died, because we moved on to other languages and other jobs as well.

I need it again, because my workflow ~~sucks~~ sucked. I just (5.11.2014) finished my first gulpfile and suddenly, life is all unicorns and roses. In the meantime, I fixed my original problem with Hinting, so it's like 45% better now.

## Changelog

**03-03-2015**
Moved this project over from StarterKit, since the StarterKit is mostly abandoned at this point (the Assets were the only used part). Also, I split the scripts build and scripts linting into separate Gulp tasks, so I can lint separate files before they get pulled together into one file.

**24-02-2015**
Removed Bourbon/Neat, replaced it with the Include Media and stole Clearfix from Bourbon. Simplified screen.css (added Category headings for future references). Removed unneeded `lib/_libs.scss` (four library files used, remember?).

**11-05-2014**
Finally, removed all old shit, and replaced it with my new shiny Gulpfile! Woohoo.

## Notes

This is for myself, mostly.

### Assets

1. Install Node.js (brew)
2. Install npm (Node.js)
3. Install all required modules (I should probably automate this part. Oh well)

#### When starting new project
1. Copy to your project
2. Run `sh /Assets/src/npmlinkmodules.sh`. It will link global `npm` modules (ha!)
3. Edit gulp (probably BrowserSync proxy and Build Version File only)
4. Do awesome shit.