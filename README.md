# Using Mill To Build Kotlin Projects

This is a simple example of how to use [mill](https://github.com/com-lihaoyi/mill) to build Kotlin projects.

## Kotlin 2.1.0 issue

There seems to be an issue with mill 0.12.5 and Kotlin 2.1.0.

Run the following to see that Kotlin 2.0.x projects work fine:

```bash
./miil k20.compile
```

And then run the following to see that Kotlin 2.1.0 projects do not work:

```bash
./miil k21.compile
```
