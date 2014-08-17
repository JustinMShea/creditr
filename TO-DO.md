CDS TO-DO List
========================================================

* Understand what all the slots in the CDS class mean and why they matter. I may quiz you about this on Monday.

* Consider simply removing slots that we never use. For example, if everywhere in the package, the value of stubCDS is "F" then it doesn't need to be a slot. We can just hard code it as "F" everywhere it is used, which is probably only in getting passed to the C functions. Note that I think that a bunch of slots can be removed in this way.

* Remove functions that are too small or too little used from internals and just put them in the place they are used. Remove large/important functions from internals and make them full scale functions: no leading .; separate file; a test case or two.