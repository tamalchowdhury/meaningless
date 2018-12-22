# Meaningless

Write meaningful JavaScript by using real life words like yes/no, on/off instead of booleans.

Install:

`npm install meaningless`

Include:

`require('meaningless');`

Use:

`let lampStatus = off;`

It's a really small library which turns some common words into boolean true and false so your code can read and sound much more meaningful.

**yes -- true**

**no -- false**

**on -- true**

**off -- false**

**right -- true**

**wrong -- false**

Example code:

```let lampStatus = off;

function toggleSwitch() {
  lampStatus = lampStatus === on ? off : on;

  if (lampStatus === on) {
    // Do something
  }
}
```
