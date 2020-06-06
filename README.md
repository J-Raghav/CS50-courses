# Project 0

Web Programming with Python and JavaScript

In these project I tried to create replica's of CS50 course pages on EdX.

## Project structure
- project0 ( main directory )
  - __SCSS__  ( contains __SCSS__ files )
  - CSS   ( contains CSS files)
    - _master.css_ ( CSS file containing base style and imported by other styles using __SASS__ )
    - _home.css_   ( CSS file containing style for home page )
    - _course.css_ ( CSS file containing style for course pages )
    - _mentor.css_ ( CSS file containing style for mentor pages )
  - courses
    - ( contains __HTML__ files of each course page )
  - mentors
    - ( contains __HTML__ files of each mentor page )
  - imgs
    - ( contains image files required )
  - _index.html_   ( main __HTML__ file home page )
  - _connect.html_ ( connect with cs50 __HTML__ file )
  - __README.md__

  
## Relationships In Project

  ### Internal links

  - ***project0/index.html*** contains link to
    - _Courses_  ( ***project0/courses/ \*.html*** ) pages  
    - _Connect_  ( ***project0.connect.html*** )
  - ***project0/courses/\*.html*** contains link to
    - _Home_    ( ***project0/index.html*** )
    - _Mentors_  ( ***project0/mentors/\*.html*** )
    - _Connect_  ( ***project0.connect.html*** )
  - ***project0/mentors/\*.html*** contains link to
    - _Courses_  ( ***project0/courses/ \*.html*** )
    - _Home__     ( ***project0/index.html*** )
    - _Connect_  ( ***project0.connect.html*** )
  - ***project0/connect.html*** contains link to
    - _Home_     ( ***project0/index.html*** )


## Bootstrap

I mostly used bootstrap classes and components for this project for style and layout structure for responsive pages. <br>
List of some __Bootstrap__ features used in project:- <br>
  1. Bootstrap Cards
  2. Bootstrap Grid system ( breakpoints-row, col-* classes )
  3. Bootstrap Tables
  4. Bootstrap Collapse content button

## SASS

List of some __SASS__ features used in project:- <br>
  1. SASS Variables ( only 2 for colors )
  2. SASS Nesting
  3. SASS Inheritance
  4. SASS Modules  ( _master.css_ )

## Media Query

List of some __Media Query__ applications in project:- <br>
  1. In _master.css_ for changing font size for mobile devices.
  2. In _course.css_ for changing order of rendering 2 main columns of page.   
  3. In _home.css_ for making iframe responsive.
