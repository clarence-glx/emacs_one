# emacs_one
# Move Screen
C-v :move forward one screenful.  
M-v :move backward one screenful.  
C-l :move the text around the cursor to the center of the screen.  
C-u 0 C-l : move curse position to 0 line.  

# Move curse
C-p :move to previous line.  
C-n :move to next line.  
C-b :move backward a charcter.  
C-f :move forward a charcter.  

C-a :move to beginning of a line.  
C-e :move to end of a line.  
C-a :move back to beginning of sentence.  
M-e :move forward to end of sentence.  

M-b :move backward a word.  
M-f :move forward a words.  
M-< :move to the beginning of the whole text.  
M-> :move to the end of the whole text.  

C-u : prefix argument,repeat-count.  
C-u C-f :moves forward eight characters.  

# Edit
C-d :delete next character.  
M-d :kill next word.  
C-k :kill to end of line.  
M-k :kill to end of sentence.  
C-spc :mark set.  
C-w :kill set.
M-w :copy set.
C-y :yank set.  
M-y :brings in earlier kills.  
C-/ :undo  
C-_ :undo  
C-x u :undo  

C-x C-f :find-file.  
C-x C-s :save file.
C-x s :save all buffer to file.
C-g :stop a command.  
C-h k C-f :key help  

# Windows
C-x 1 :one windows (i.e., kill all other windows).  

# Buffers
C-x C-b :list bufers.  
C-x b :switch buffer.  
C-x C-f foo :create foo file.  
C-x b TUTORIAL :come back to a buffer.  
C-x s :save changed files.  

C-x C-c :end emacs session.  
C-z :suspend. you can come back with "fg".  
M-x repl s<TAB> :replace-string.  
M-x recover-this-file :recover file.  
M-x text-mode :change mode.  

# Searching
C-r :backward search.  
C-s :forward search. <DEL> moves the cursor back to an earlier occurrence.

# Miltiple windows
C-x 2 :new bottom window.  
C-x 1 :only one window.  
C-x o :other, swith between windows.
C-x 4 C-f :new file in bottom window.  
C-M-v :scroll other window.

# Multiple frames
C-x 5 2 :new frame appear on your screen.
C-x 5 0 :removes the slected frame.

# Recursive editing levels
<ESC><ESC><ESC> :getting out of the minibuffer.

# Getting more help
C-h c C-p :
M-` :activate menubar.
C-h a : Command Apropos.
C-h i : Read included Manuals.



