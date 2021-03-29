Monday 03/29/2021
Afternoon Link: https://github.com/Toppedyk/zoo-keeper

What problem does using exports solve?
This allows us to organize our JS better in multiple files without having to write a script tag in the body for each file.

How does export differ from export default?
You can have multiple named exports per module but only one default export. default can be imported with any name. 

What is a benefit of using the Module System?
Code can be split into smaller files of self-contained functionality.
Multiple scripts can be concatenated thereby increasing performance.
Debugging becomes easier.
Any code referencing a module understands it is a dependency. If the module file is changed or moved, the problem is immediately obvious.