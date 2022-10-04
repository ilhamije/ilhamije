---
title: "Editing With VI/VIM"
date: 2022-10-04T09:09:35+07:00
draft: false
---

I've been working on tutorial task for Jarkom Lanjut (Advanced Computer Network) in my Master. It's a hands-on tutorial to improve our understanding about the subject. The lecturer gave us some clear instructions to use Nano to edit the code. Nano is easy to use and more friendly compared to VIM/VI. (Disclaimer: Both of these editors are good). Usually, I'd prefer to use VI in case I need to use editor in Server.


Why? Let me tell you.  
(at least these are the commands I often used.)

---

VI has these functionalities:

I assume you already know how to open a file in terminal
```
$ vi filename.py
```

Write? Sure.
Press "a" to start editing. Or "insert" button.

---

Any command will be run by hitting enter button.

**Jump** to specific line?
```
:<line-number>
```
i.e you want to jump to line 123, then run ":123"

---

**Search/Find** a specific string? Got you.
```
:/<your-search-string>
```
You want to find a function "def main", then run ":/main"

---

**Highlight** all the searched string? Sure.
```
:hlsearch
```

---

**Copy** a line? Sure.
```
:t.
```
Go to your desired line to be copied. Then run ":t.", it will pasted under copied line.

---

**Undo** a saved changed? My favorite one.
```
:u
```

---

Ready to **save** the world?
```
:w
```

---

Oh you want to **quit**?
```
:q
```

---

**Save** and **Quit** at the same time?
```
:wq
```

---

More command?
```
:help
```
or checkout this site https://www.redhat.com/sysadmin/get-started-vi-editor they're awesome!

I hope you enjoy this short writing about using the VI/VIM editor.