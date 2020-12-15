# aliasrc

Aliases are pain.  
If you want to use same alias name for different projects on the same machine it'll become even more pain.  
That's why with some help from guys from [pro.bash](https://t.me/pro_bash) telegram chat this script was born.  

In short:
- You can now declare aliases **per project** basis. Just create in their root directory `.aliasrc` file with key=value alias. That's it!
- You can still use global aliases, they will be reloaded if you go to some directory in console. Create `.aliasrc` in your user root folder (like `~/.aliasrc`) and fill it with key=value aliases.

To use this script copy code from [.aliasrc.source](.aliasrc.source) file to your `.bashrc` or `.zshrc` file in you system. THAT'S IT.

>NOTE: Don't forget to add blank line at the end of `.aliasrc` file. It won't work without it. 
