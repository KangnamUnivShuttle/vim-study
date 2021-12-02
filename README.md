# vim-study


## cursor 

- h : left
- j : down
- k : up
- l : right

- w : jump to next word 
- b : jump to previous words
- e : jump to end of word
- W : jump to next word (space)
- B : jump to previous words (space)
- E : jump to end of word

- 0 : jump to start of line 
- ^ : jump to start of sentence
- $ : jump to end of sentence 
- f`char` : jump to first `char` position
- f`char` -> ; : jump to next `char` position
- f`char` -> , : jump to previous `char` position
- t`char` : jump to first `char` position - 1
- t`char` -> ; : jump to next `char` position - 1
- t`char` -> , : jump to previous `char` position - 1

If f or t is upper character then search negative direction (right -> left)

```
This is test sentence!! with some speci@l characters...
	if (test == 1) {
		console.log('test')
	}
```

## search

- `/world` : search all `world`
- n : move cursor to next found `world`
- N : move cursor to previously found `world`
- `*` : hilight all found `world`
- `#` : highlight and move negative direction

## scroll

- ctrl + e : line scroll down
- ctrl + y : line scroll up
- ctrl + u : half page up
- ctrl + d : half page down
- gg : move to first page
- G : move to last page
- `:number` : move to number of line

## select

- V : select line

## vim modes

- normal : move cursor, screen ... etc
- input : type text
- command : run some command order

## input

- a : append
- i : insert
- o : open line
- r : replace
- A : append text at end of line
- I : insert text at start of line
- O : open line at previous line
- ctrl + [ or esc : exit input mode
- ctrl + h or backspace : remove character

## Delete

_Always delete string should be stored at tmp memory_

- x : delete current position's character
- dd : delete current line
- D : delete string from cursor to end of line
- J : attach next line to end of this line

## Paste

- p : paste tmp string upper line
- P : paste tmp string lower line

## Yrank

- yy : copy line
 
## Undo, redo

- u : undo
- ctrl + r : redo

## Repeat

- . : repeat last command

sasdfasdfasdfasdfasdfasdfaadfadsfasdfasdfasdf asdfasdfasdfasdfasdfasdfasdfasdfasdfaasdfasdfasdfaaa
sasdfasdfasdfasdfasdfasdfaadfadsfasdfasdfasdf asdfasdfasdfasdfasdfasdfasdfasdfasdfaasdfasdfasdfaaa
	aaasdfasdf
asdfasdf
sdfasdf
asdfasdf
sdfasdf
asdfasdfasdfasdfasdfasdfaa
