# **Vim Adventures** 🔥😎🎩🥇

Most keymaps copy the vim, so universally it is helpful to learn! 
In the vim terminal, type:

&nbsp;

## **Level 1**

<kbd>h</kbd> ~ Moves left 

<kbd>l</kbd> ~ Moves right

<kbd>j</kbd> ~ Moves down

<kbd>k</kbd> ~ Moves up

Note: Moving up or down to a shorter line moves you to the last column in the
shorter line. But, if you keep moving to a longer line you will end up in the 
same column where you started!

&nbsp;

<kbd>:help</kbd> + <kbd>key_used</kbd> ~ Allows you to learn more about a key
and what it does 😉

<kbd>:w</kbd> [name] saves a new game.

<kbd>:w!</kbd> saves the original game or overwrites the original game.

&nbsp;

## **Level 2**

Note: VIM `words` are a sequence of letters, digits and underscores, or a sequence
of puntuation marks, or an 💎 empty line 💎. Certain keys help you navigate words.

&nbsp;

<kbd>w</kbd> ~ Move [count] words forward, ending at each first character. 
*Position the curser at the beginning of the word.*

Note: [count] means a number could be put in front of the <kbd>w</kbd>, which in 
that case you would move [3] words forward and start on the 4th word. 

&nbsp;

<kbd>e</kbd> ~ Move forward to the end of a word. *Position the curser at the end of
the word.*

Note: [count] <kbd>e</kbd> moves from the begining of a word to the end, then to the
beginning of the next word [2] times. Does not stop in an empty line. 

&nbsp;

<kbd>b</kbd> ~ Move [count] words backwords, ending at each first character. 
*Position the curser at the beginning of the word.*

&nbsp;

## **Level 3**

<kbd>B</kbd> ~ [count] WORDS backwards, ending at the beginning character of the
word. *Position the curser at the beginning of the WORD.

Note: VIM `WORDS` are a sequence of non-blank characters, separated with white
space (spaces, tabs, EOL). An empty line is also considered to be a WORD. Any
sequence of non-blank characters is considered to be a WORD. 

&nbsp;

<kbd>x</kbd> ~ Delete [count] characters under and after the curser in the 
current line [into a register if specified]. Does the same as 'dl'.

<kbd>X</kbd> ~ Delete the character before the curser (Backspace)

&nbsp;

## **Level 4**

<kbd>E</kbd> ~ Moves forward to the end of a WORD [count]. *Position the curser
at the end of the WORD.*

Note: Does not stop in an empty line.

&nbsp;

<kbd>W</kbd> ~ [count] WORDS forward. *Position the curser at the beginning of the
WORD.*

&nbsp;

<kbd>r{char}</kbd> ~ Replace the character under the curser with {char} by typing
the char you want after <kbd>r</kbd>.

Note: If you give a [count] before <kbd>r</kbd>, VIM replaces [count] characters 
with [count] {char}s.

&nbsp;

## **Level 5**

<kbd>d{motion}</kbd> ~ Delete text that {motion} moves over [into a register if
specified].

Note: Motions include <kbd>w or W</kbd>, <kbd>e or E</kbd>, <kbd>b or B</kbd>,
<kbd>h, j, k, l</kbd>.

<kbd>dd</kbd> ~ Delete [count] whole lines [into a register].

<kbd>D</kbd> ~ Delete from the current position until the end of the line.

Note: Regardless of the curser position in the line, the entire line is deleted.

&nbsp;

## **Level 6**

<kbd>~</kbd> ~ Switch case of the character under the curser and move the curser
to the right.

Note: If a [count] is given, do that many characters.

&nbsp;

<kbd>$</kbd> ~ To the end of the line.

Note: When a count is given also go [count -1] lines downward.

&nbsp;

<kbd>0</kbd> ~ To the first character of the line.

&nbsp;

<kbd>^</kbd> ~ To the first non-blank character of the line.

&nbsp;

## **Level 7**

Successfully got to level 7 😎🔥