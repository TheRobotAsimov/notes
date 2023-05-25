# GUIDE STEP-BY-STEP TO PERSONALIZE TERMINAL

Windows terminal (or Tilix in Linux) -> zsh -> oh my zsh -> powerlevel 10k -> (`p10k configure`) -> `~/.p10k.zsh`:

````
# The right end of left prompt.
typeset -g POWERLEVEL9K_LEFT_PROMPT_LAST_SEGMENT_END_SYMBOL='%K{#1E1E1E} %K{#121212} %K{#060606} %k'
# The left end of right prompt.
typeset -g POWERLEVEL9K_RIGHT_PROMPT_FIRST_SEGMENT_START_SYMBOL='%K{#060606} %K{#121212} %K{#1E1E1E} %k'

(
print -P '%K{#303030} %B%F{39}~%f%b %K{#1E1E1E} %K{#121212} %K{#060606} %K{#000000} %k'
)
````