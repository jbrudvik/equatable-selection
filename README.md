[![Build status](https://img.shields.io/travis/jbrudvik/equatable-selection.svg)](https://travis-ci.org/jbrudvik/equatable-selection)
[![Bower version](http://img.shields.io/bower/v/equatable-selection.svg)](https://github.com/jbrudvik/equatable-selection)

  - [EquatableSelection()](#equatableselection)
  - [EquatableSelection.isEqual()](#equatableselectionisequalotherequatableselection)

## EquatableSelection()

  An object for observing and comparing current text selections.
  
  When instantiated, captures the current selection and computes a count
  of words and characters selected.
  
  May be compared for equality against other EquatableSelection instances.
  
  Should be treated as immutable.

## EquatableSelection.isEqual(other:EquatableSelection)

  Return true if two EquatableSelection objects are equal, false otherwise

# Generating documentation

    $ npm install -g dox
    $ ./generate-docs > README.md
