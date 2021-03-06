# TShirts

## Description

Working with user state and varying display sizes is a common occurrence when working with CSS.
Usually responsive designs are simple breakdowns in grid size.
Other times, the design changes more drastically to make the UI easier to use.

## Objectives

### Learning Objectives

After completing this assignment, you should be able to:

* Use Pseudo Selectors (`:first-of-type`, `:last-of-type`, `:hover`, etc.) to style elements
* Use Media Queries

### Review Objectives

After completing this assignment, you should be able to effectively use:

* Use flex-box to create a grid with gutters
* Use flex-box to stack content
* Use `flex-grow` and `min-width` to make a responsive grid
* Organize SASS using variables
* Organize SASS using `@import` statements
* Create SASS code free of linting errors
* Use `position: relative` and `position: absolute` to create tool tips

## Grading Criteria

* Desktop Grid Layout
* Placement of dropdown when user hovers
* Change in layout for tablet
* Optimized Media Queries (Don't Repeat Yourself)

## Details

### Deliverables

* A project started with `sass-broccoli` Yeoman Generator

### Requirements

Recreate the following design using HTML and SASS.

#### Desktop

![Desktop](./tshirt-desktop.gif)

#### Tablet

![Tablet](./tshirt-tablet.gif)

>You should replicate the design as closely as possible (don't take creative liberties with this one).

> You should make sizes and colors configurable with SASS variables

The designer has given you a few things to work with:

* Brand Primary: `#3473b5`
* Brand White: `#fff`

* pink: `#e577aa`
* Blue: `#72bbe9`
* Green: `#7abe93`
* Yellow: `#e5b178`

* Gutter: `1rem`;
* Max Content Width: `60rem`


## Tasks

```
* [ ] Create a new project using `yo sass-broccoli` name the project `06-tshirts`
* [ ] Initialize new folder as git repository
* [ ] Using `hub` create a new repository on github
* [ ] Checkpoint: Commit code from HTML grouping workshop to `master branch`
* [ ] Make one change to project and commit changes
* [ ] Push changes to `origin` `develop` branch
* [ ] Create a pull request using the `hub` CLI
* [ ] **GOAL**: Style Grid Basics
  * [ ] Outer container gutter padding
  * [ ] Inner container max width
  * [ ] Stack Grid Items Horizontally
* [ ] **GOAL**: Style Shop Item
  - [ ] Style: Border around Shop Item
  - [ ] Style: Image Gutter
  - [ ] Style: Button Row
  - [ ] Style: Button Border
  - [ ] Style: Drop Down Position
  - [ ] Style: Drop Down Stack
  - [ ] Style: Drop Down Item Border
  - [ ] Style: Button Hover State
  - [ ] Style: Dropdown Hover State
* [ ] **GOAL**: Style Color Icons
  - [ ] Style: Pink Box
  - [ ] Style: Blue Box
  - [ ] Style: Yellow Box
  - [ ] Style: Green Box
* [ ] **GOAL**: Grid Settings Phone
  - [ ] Style: Grid Wrap
  - [ ] Style: Grid Min Width
* [ ] **GOAL**: Tablet Layout
  - [ ] Style: Full Width
  - [ ] Style: Shop Item Changes
  - [ ] Style: Buttons
  - [ ] Style: Dropdown Position
  - [ ] Style: Dropdown Changes
```

* Todos Gist for following along:
