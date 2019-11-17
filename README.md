### bashcolors to use in bash/shell scripts
colors and formatting ANSI/VT100 to easy use in bash scripts

Easy to use in bash/shell scripts in between 'echo' outputs
use
``` bash
echo "${var}  "
```

example1
``` bash
echo -e "${red} Cauntion info text... ${bla,whi} black text in whit background"
```

example2: 
``` bash
echo -e "${gre} Good news text... ${coloroff} normal text..."
```

you can use rgb codes as well, 
eg.
``` shell
echo -e "${rgb001} blue color text...${c0}"
```

---
you can use various kind of schortcuts easy to remember:
3 letter short;   rgb triplet;    1 letter short;   full name;

eg. 
bla - for black
gre - for green
rgb001 - for blue
1c - for (1 letter) cyan
etc.
