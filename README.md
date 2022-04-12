# genshinjumpfixer2

**Moved to [another repo](https://github.com/khang06/misc/tree/master/reversing/genshin)!!!**

This is an IDAPython script for cleaning up obfuscated branches seen in Genshin Impact's UnityPlayer.dll. It's only been tested on the 1.5 dev build leak, but I doubt much has changed since then.

To use this, simply execute the script while selecting a specific block of code. The script will automatically calculate the jump targets and simplify the code.

Examples of what to select can be seen below. If you're able to reverse enough code to get to this point, you can probably figure out the rest.


![](https://files.catbox.moe/xeitlv.png)
![](https://files.catbox.moe/nojqhd.png)
![](https://files.catbox.moe/dylvp9.png)
