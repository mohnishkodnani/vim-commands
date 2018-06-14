# vim-commands

1. Block Text Folding like json or code. 

    - ```:setlocal foldmethod=marker``` <-- we will set marker of what to foldmethod

    - Go to the brace that needs to foldmethod
  
    - zfa} <-- fold till the next }

    - zd <-- unfold

    - za <-- toggle fold

2. Get all registers information 

    - ```:reg```

    - Paste from a register ```"<register num>p```
