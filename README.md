# emacs_one
# Move Screen
c-v :move forward one screenful. 
m-v :move backward one screenful. 
c-l :move the text around the cursor to the center of the screen.
c-u 0 c-l : move curse position to 0 line.

# Move curse
c-p :move to previous line.
c-n :move to next line.
c-b :move backward a charcter.
c-f :move forward a charcter.

c-a :move to beginning of a line.
c-e :move to end of a line.
m-a :move back to beginning of sentence.
m-e :move forward to end of sentence.

m-b :move backward a word.
m-f :move forward a words.
m-< :move to the beginning of the whole text.
m-> :move to the end of the whole text.

c-u : prefix argument,repeat-count.
c-u c-f :moves forward eight characters.

# Edit
c-d :delete next character.
m-d :kill next word.
c-k :kill to end of line.
m-k :kill to end of sentence.
c-spc :mark set.
c-w :kill set.
c-y :yank set.
m-y :brings in earlier kills.
c-/ :undo
c-_ :undo
c-x u :undo

c-x c-f :find-file.
c-x c-s :save file.
c-g :stop a command.
c-h k c-f :key help

# Windows
c-x 1 :one windows (i.e., kill all other windows).

# Buffers
c-x c-b :list bufers.
c-x b :switch buffer.
c-x c-f foo :create foo file.
c-x b TUTORIAL :come back to a buffer.
c-x s :save changed files.

c-x c-c :end emacs session.
c-z :suspend. you can come back with "fg".
m-x repl s<TAB> :replace-string.
m-x recover-this-file :recover file.
m-x text-mode :change mode

