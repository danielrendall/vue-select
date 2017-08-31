# vue-select 

> A native Vue.js select component that provides similar functionality to Select2 without the overhead of jQuery.

You do not want this version; get the original from https://github.com/sagalbot/vue-select

This includes a couple of changes I made for a client:

* When selecting multiple items with the closeOnSelect option, it can be overridden by holding Ctrl (to make it a little
more like the normal boring browser multiple select)
* You can select a range of items by holding Shift when clicking, which will select everything from the last selection 
made during its current period of openness to the current. Hold Ctrl-Shift to select a range and keep it open.
* A not-fully-tested change to maintain the list of selected options in the same order as the available options (i.e. if 
available options are 'a', 'b', 'c', 'd', 'e' and you select 'e', 'c', 'a' in that order, the value will be 'a', 'c', 'e')

It is unlikely that I will have time to write tests for these things.