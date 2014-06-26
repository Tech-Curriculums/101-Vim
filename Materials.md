* installing vim
  * sudo apt-get install
  * homebrew
* Doing stuff
  * press `i` to go into editing mode
  * press `<ESC>` alot, alot alot
  * to save press `<ESC>:wq`
  * to just save type `:w` from normal mode

creating a crontab
  * create a morning wake up call (epseak/say)
  * create an evening note (say -- remember the chicken)
  * scary picture @ midnight
  * rick-roll the next class (or your sibling)

* command-mode
  * doing things on the command line
  * reading in things from the command line
  * reading in other files
  L00k1n9 hax
  * vsplit
  * tabedit
  Keeping the history (never leave vim)
  * shell-ing out
* registering
  * introduction to registers
  * more copy-pasta (see if the kids would like some pasta -- include vegetarian and vegan options)
  * how much copy-pasta? as many letters there are on the keyboard (no numbers, capital letters)
  * you'll want more of these eventually.
  * how to store in a register
  * `"u y` to yank into a letter-register
  * how to paste from a register?
  * `"u p` pastes from a letter-register
* macros
  * macros are great for fast and custom, well, macros
  * macros are a bunch a keys triggered (usually) by a single key, or two keys
  * vim has default macro button to be the `@` key
  * we'll practice putting things into the shelf, and then inspecting them and putting them back
  * putting into shelf
    * Normal: q then "register" (I like to use "u" for this, easy to reach),
    * type your macro
    * go back to normal mode, then press q to complete
    * to 
    * type @u in normal mode to execute the any command
  * what if you want to keep your dynamic macros dynamic?
* leaderkeys
  * hooray for vimscript!
  * record with macros -> bind with leader keys
  * do big things quickly
  * example, code journal
    * noremap <leader>d :!
    * imap
  
