# m2sharp-tests
A rough testing system for my work on m2sf-m2sharp

A few changes have been made, which are not permanent, but simply practical for testing.
TokenSet.PrintLiteral has been altered to return a string and no longer uses ITokenSet, which was extraneous.

This is the source of the data which is passed into the First and Follow sets. It is based off of gen_first_sets.c and gen_follow_sets.c from the C compiler we are basing this compiler off.

The strange capitalization in Program.cs and resultingly in Output.txt is a remnant of a number of find & replaces I did on the code.
