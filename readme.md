# aliasrc

Aliases are pain.  
If you want to use same alias name for different projects on the same machine it'll become even more pain.  
That's why with some help from guys from [pro.bash](https://t.me/pro_bash) telegram chat this script was born.  

In short:
- You can now declare aliases **per project** basis. Just create in their root directory `.aliasrc` file with key=value alias. That's it!
- You can still use global aliases, they will be reloaded if you go to some directory in console. Create `.aliasrc` in your user root folder (like `~/.aliasrc`) and fill it with key=value aliases.

To use this script:
1. Copy code from [.aliasrc.source](.aliasrc.source) file to your `.bashrc` or `.zshrc` file.
2. Create `.aliasrc` file in the root folder. It can be empty, but make sure there's at least one empty line in the end of the file
3. THAT'S IT.
Now if you want to add global alias just put it in `~/.aliasrc` file, if you want to use local alias create `.aliasrc` in the folder where you want to use it.

>NOTE: every `.aliasrc` file must have empty last line. It won't work without it. 
