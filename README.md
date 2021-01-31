Persian Wordifier converts simple numbers to words.
for example you can use this:

```
import { wordifyfa, wordifyRials, wordifyRialsInTomans } from "react-wordifyfa";
var a = 235000;
var b = wordifyfa(a);
console.log(b); // دویست و سی و پنج هزار
var c = wordifyRials(a); // دویست و سی و پنج هزار ریال
var d = wordifyRialsInTomans(a); // بیست و سه هزار و پانصد تومان
```
