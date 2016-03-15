# Clean Assets source folder

My very own setup for most of front-end/designy stuff I work on.

Latest version: See changelog  
License: What? If it helped, you're welcome. Use what you want.

## The story

We started this repository with [Matej](http://hrescak.com/) some time in 2012, because of the very same reasons why it exists right now, but then it kind of died, because we moved on to other languages and other jobs as well.

I then rewrote it completely to Gulp.js, added image optimization and javascript requiring, shell commands to link modules.

And then I rewrote it again. Everything about Gulping the source is gone; now it's just the source folder of my assets, with default tree, styles and scripts.

## Changelog

**25-03-2016**
- Completely changed this repo;
  - no `Gulp`, `src`, `dest`, nothing
  - just my default source tree with styles and scripts
  - updated readme

**17-04-2015**
- fixed some stuff in the readme
- added `.gitignore` and removed all the stupid `.DS_Store` files
- put back `src/styles/libs` folder, which mysteriously disappeared (I deleted it)

**03-03-2015**
- moved this project over from StarterKit (since that is abandoned at this point)
- split `scripts` into `scripts:build` and `scripts:lint` (linting separate files)

**24-02-2015**
- Removed Bourbon/Neat
- replaced it with the Include Media
- stole Clearfix from Bourbon
- Simplified screen.css (added Category headings for future references).
- Removed unneeded `lib/_libs.scss` (four library files used, remember?).
  - This probably also removed `libs` folder. I am an idiot.

**11-05-2014**
- Finally, removed all old shit, and replaced it with my new shiny Gulpfile! Woohoo.
- Gulp

## Notes

This is for myself, mostly.

#### When starting new project
1. This is included elsewhere, so whatever.