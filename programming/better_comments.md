# Commenting Code ?
> Road to hell is paved with good intentions.

## Favor Explaining Names Over Comments
Comments that simply says what the code already conveys using type and variables names, is not only pointless, but actively harmful.

At best, such comments adds no value, at worst, it’s incorrect and noisy.

They are a common victim of “copy pasta” leading to unnecessary Code Review noise, and are rarely updated when the surrounding code changes.

Comments come with a high maintenance burden; if the code around them changes, they must be updated.

Compilers and IDEs can do little to detect that a comment is no longer accurate and so often forgotten in updates.

The cost of a stale comment and a subsequent incorrect assumption made by a reader new to the code often greatly outweighs the benefit of a low-value comment provides.

Explaining names for variables, fields, methods, classes, etc. can often serve the same purpose, but are less likely to go stale.

Don’t be afraid to extract more variables and methods to break down the functionality into more manageable chunks, each with an explaining name.

> The best comment is one that you don’t have to write.

Moreover, documentation is different thing altogether.