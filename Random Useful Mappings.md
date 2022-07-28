* gx in normal mode will open up the link below cursor in browser window
    * vim.g.netrw_browsex_viewer="cmd.exe /C start" -- can now press 'gx' on link and will open in windows browser tab

* :on[ly] to focus on only this buffer

* :bro[wse] oldfiles - will show list for all files with marks in shada

* :echomsg - this will echo to show up in :messages

* :nmap - will list all current set mapping in normal mode
    * :verbose nmap - will also show last set on what line
    * :verbose nmap <leader> - will only show mappings relating to leader

# Tweak macro 'a'
* "ap
    * will paste the a register which is really the recorded macro for a
* "ay$
    * will yank to EOL to the a register which will update the macro for a
* :reg to print all of the registers values
