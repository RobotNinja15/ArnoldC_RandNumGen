## The Worst Random Number Generator made in ArnoldC

ArnoldC is a programming language based on the one liners of **Arnold Schwarzenegger**.

I randomly decided to make the worst pseudo-random number generator in arnoldC, I could've used some other language like C or C++, but nope I just wanted to punish myself lol.

I am the least smartest person out there so there is probably a better way to make something better. The goal was not to make the best pseudo-random number generator, just something that works and I think I have accomplished that.

This is one of the most interesting projects I have personally worked on.

I have provided the `.class` file so you that you can run it immediately by just doing:

```bash
java test
```

Or you can just straight up compile and run it again

```bash
java -jar ArnoldC.jar test.arnoldc
java test
```
There is a fun thing you can try, you can create audible output, it's not really good. (If you are expecting some beautiful Arnold Schwarzenegger text-to-speech goodness, you will not find it here.)

```bash
java -jar ArnoldC.jar -declaim test.arnoldc
```

Do this and you will get a `.wav` file, with the audio output. I have already provided mine so you may not really need one.

This has taught me about how programs are able to generate pseudo-random numbers, especially how `rand()` and `srand()` work in C/C++.

if you are interested, check out of the language here:
https://lhartikk.github.io/ArnoldC/

Thank you,

Kenneth.
