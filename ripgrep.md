```
alias rg_clean_files='rg --files -g "!**/artifacts" -g "!**/target" -g "!**/node_modules" | rg'

alias rg_clean='rg -g "!**/artifacts/" -g "!**/target/" -g "!**/node_modules/"'

# rg_clean help
alias rg_clean_help='
echo -e "Commands:"
echo -e "rg_clean <SEARCH_TERM>"
echo -e "Searches all files in the current dir for <SEARCH_TERM> ignoring fat directories like node_modules and artifacts"
echo -e "---"
echo -e "rg_clean_files <SEARCH_TERM>"
echo -e "Searches current dir for file names containing <SEARCH_TERM> ignoring fat directories"'
```
