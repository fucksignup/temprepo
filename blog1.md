# Markdown Complete Test File

A complete Markdown file for testing a Markdown renderer.

---

## 1. Headings

# Heading 1

## Heading 2

### Heading 3

#### Heading 4

##### Heading 5

###### Heading 6

---

## 2. Paragraphs

This is a normal paragraph.

This is another paragraph separated by an empty line.

You can also have a very long paragraph containing **bold text**, *italic text*, `inline code`, and [a link](https://example.com).

---

## 3. Text Formatting

**Bold text**

**Bold text**

*Italic text*

*Italic text*

***Bold and italic***

***Bold and italic***

~~Strikethrough~~

`Inline code`

<u>Underline using HTML</u>

H~2~O

X^2^

---

## 4. Line Breaks

This line ends with two spaces.
This line starts after a Markdown line break.

This is another paragraph.

---

## 5. Horizontal Rules

---

---

---

---

## 6. Unordered Lists

* Item one
* Item two
* Item three

### Nested unordered list

* Fruits

  * Apple
  * Banana
  * Orange
* Vegetables

  * Potato
  * Tomato
  * Carrot

---

## 7. Ordered Lists

1. First item
2. Second item
3. Third item

### Nested ordered list

1. First

   1. First nested
   2. Second nested
2. Second

   1. Another nested item
   2. Another nested item

---

## 8. Mixed Lists

1. First item

   * Nested item
   * Another nested item
2. Second item

   * Nested item

     1. Deeply nested item
     2. Another item

---

## 9. Task Lists

* [ ] Uncompleted task
* [x] Completed task
* [ ] Another task
* [x] Another completed task

---

## 10. Links

[Normal link](https://example.com)

[Google](https://google.com)

https://example.com

[hello@example.com](mailto:hello@example.com)

---

## 11. Links with Titles

[Example website](https://example.com "Example Website")

---

## 12. Images

![A beautiful mountain](https://images.unsplash.com/photo-1500534623283-312aade485b7)

![Placeholder image](https://via.placeholder.com/600x300)

---

## 13. Blockquotes

> This is a blockquote.

> This is a longer blockquote
> spanning multiple lines.

### Nested blockquote

> Outer quote
>
> > Inner quote
> >
> > This is a nested quote.
>
> Back to the outer quote.

---

## 14. Blockquote with Formatting

> **Important:** This is a bold statement.
>
> You can also use `inline code` inside quotes.
>
> * List inside a quote
> * Another item

---

## 15. Code

Inline code:

`const x = 10;`

### JavaScript

```javascript
function hello(name) {
    console.log(`Hello, ${name}!`);
}

hello("World");
```

### C++

```cpp
#include <bits/stdc++.h>
using namespace std;

int main() {
    int n;
    cin >> n;

    cout << n * n << '\n';

    return 0;
}
```

### Python

```python
def fibonacci(n):
    if n <= 1:
        return n

    return fibonacci(n - 1) + fibonacci(n - 2)

print(fibonacci(10))
```

### Bash

```bash
#!/bin/bash

echo "Hello World"
ls -la
cd ~/Documents
```

### JSON

```json
{
  "name": "PaperMint",
  "version": "1.0.0",
  "features": [
    "markdown",
    "math",
    "code"
  ]
}
```

### HTML

```html
<!DOCTYPE html>
<html>
  <body>
    <h1>Hello World</h1>
  </body>
</html>
```

### CSS

```css
body {
    background: #111;
    color: white;
    font-family: sans-serif;
}
```

### SQL

```sql
SELECT name, age
FROM users
WHERE age >= 18
ORDER BY name;
```

### No language specified

```
This is a plain code block.
No syntax highlighting should be applied.
```

---

## 16. Tables

| Name    | Age | Country |
| ------- | --: | ------- |
| Alice   |  21 | USA     |
| Bob     |  25 | India   |
| Charlie |  30 | UK      |

### Table Alignment

| Left | Center | Right |
| :--- | :----: | ----: |
| A    |    B   |     C |
| 10   |   20   |    30 |
| Left | Center | Right |

---

## 17. Table with Formatting

| Feature      | Status | Description     |
| ------------ | ------ | --------------- |
| **Markdown** | ✅      | Supported       |
| *Math*       | ✅      | Supported       |
| `Code`       | ✅      | Supported       |
| Tables       | ✅      | Supported       |
| ~~Old~~      | ❌      | Not recommended |

---

## 18. Escaping Markdown Characters

*This is not italic*

_This is not italic_

# This is not a heading

[This is not a link]

`This is not code`

Characters:

* _ # + - . ! [ ] ( ) { }

---

## 19. Special Characters

©

®

™

 

<

>

&

---

## 20. Mathematical Inline Equations

This is an inline equation: $a^2 + b^2 = c^2$.

Another equation: $\frac{x^2 + 3x - 4}{x - 1}$.

A more complex equation:

$\sum_{i=1}^{n} \frac{i^2 + 2i + 1}{i(i+1)}$

Another:

$\sqrt{x^2 + y^2} = \sqrt{r^2}$

---

## 21. Display Math

$$
a^2 + b^2 = c^2
$$

---

## 22. Complex Display Math

$$
\frac{-b \pm \sqrt{b^2 - 4ac}}{2a}
$$

---

## 23. Summation

$$
\sum_{i=1}^{n} i^2
==================

\frac{n(n+1)(2n+1)}{6}
$$

---

## 24. Integral

$$
\int_0^\infty e^{-x^2},dx
=========================

\frac{\sqrt{\pi}}{2}
$$

---

## 25. Matrix

$$
A =
\begin{bmatrix}
1 & 2 & 3 \
4 & 5 & 6 \
7 & 8 & 9
\end{bmatrix}
$$

---

## 26. System of Equations

$$
\begin{cases}
2x + y = 5 \
x - y = 1
\end{cases}
$$

---

## 27. Aligned Equations

$$
\begin{aligned}
f(x) &= x^2 + 2x + 1 \
&= (x+1)^2
\end{aligned}
$$

---

## 28. Greek Letters

Inline:

$\alpha, \beta, \gamma, \delta, \epsilon, \theta, \lambda, \mu, \pi, \sigma, \phi, \omega$

Display:

$$
\alpha + \beta + \gamma = \pi
$$

---

## 29. Superscripts and Subscripts

$x^2$

$x^{10}$

$x_i$

$x_{i+1}$

$x_i^2$

$$
a_{ij} = b_{ij} + c_{ij}
$$

---

## 30. Fractions

$\frac{1}{2}$

$\frac{x+1}{x-1}$

$$
\frac{\frac{a}{b}}{\frac{c}{d}}
$$

---

## 31. Square Roots

$\sqrt{x}$

$\sqrt{x^2 + y^2}$

$$
\sqrt[n]{x}
$$

---

## 32. Big Operators

$$
\sum_{i=1}^{n} i
$$

$$
\prod_{i=1}^{n} i
$$

$$
\lim_{x \to \infty} \frac{1}{x} = 0
$$

---

## 33. Callouts / Admonitions

> [!NOTE]
> This is a note.

> [!TIP]
> This is a useful tip.

> [!WARNING]
> Be careful with this operation.

> [!IMPORTANT]
> This information is important.

> [!CAUTION]
> This action may have consequences.

> [!DANGER]
> This is dangerous.

> [!INFO]
> Additional information goes here.

> [!SUCCESS]
> Operation completed successfully.

> [!QUESTION]
> Why does this happen?

---

## 34. Footnotes

Here is a sentence with a footnote.[^1]

Here is another sentence with a longer footnote.[^note]

[^1]: This is the first footnote.

[^note]: This is a named footnote.

---

## 35. Definition Lists

Term
: Definition of the term.

Markdown
: A lightweight markup language.

---

## 36. Abbreviations

HTML

*[HTML]: HyperText Markup Language

---

## 37. Automatic Links

https://example.com

https://github.com

---

## 38. Email

[test@example.com](mailto:test@example.com)

---

## 39. HTML

<div>
  <strong>This is HTML inside Markdown.</strong>
</div>

<br>

<p>This is an HTML paragraph.</p>

---

## 40. HTML Details / Collapsible Section

<details>
<summary>Click to expand</summary>

This content is hidden until expanded.

You can put **Markdown-like content** here.

</details>

---

## 41. Keyboard Keys

Press <kbd>Ctrl</kbd> + <kbd>C</kbd> to copy.

Press <kbd>Ctrl</kbd> + <kbd>Shift</kbd> + <kbd>P</kbd> to open the command palette.

---

## 42. Highlight

==This text is highlighted==

---

## 43. Comments

<!--
This is a Markdown/HTML comment.
It should not be visible when rendered.
-->

---

## 44. Escaped Dollar Signs

This should display a literal dollar sign:

$100

This is not math:

$x^2$

This is math:

$x^2$

---

## 45. Inline Math vs Display Math

Inline math stays inside the paragraph: $E = mc^2$.

Display math gets its own block:

$$
E = mc^2
$$

Another inline equation: $\sum_{i=1}^{n} i$.

Another display equation:

$$
\sum_{i=1}^{n} i
================

\frac{n(n+1)}{2}
$$

---

## 46. Markdown Inside Lists

* **Bold item**
* *Italic item*
* `Code item`
* [Link item](https://example.com)

1. **First**
2. *Second*
3. `Third`

---

## 47. Code Inside Lists

1. Install dependencies:

   ```bash
   npm install
   ```

2. Start the application:

   ```bash
   npm run dev
   ```

---

## 48. Image with Link

[![Example Image](https://via.placeholder.com/300x150)](https://example.com)

---

## 49. Long Text

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum vitae
justo at ipsum consequat tincidunt. Integer posuere, lorem vitae facilisis
mattis, sapien neque tincidunt magna, sed feugiat ligula justo vitae mauris.

---

## 50. Unicode

Hello 👋

🚀 Rocket

🔥 Fire

💻 Computer

🧠 Brain

⚡ Lightning

→ Arrow

← Arrow

↑ Arrow

↓ Arrow

✓ Check

✗ Cross

© Copyright

™ Trademark

∞ Infinity

π Pi

---

## 51. Mixed Everything

> [!TIP]
> You can combine **bold**, *italic*, `code`, [links](https://example.com),
> and math like $x^2 + y^2 = z^2$ inside content.

### Example algorithm

```cpp
int sum = 0;

for (int i = 1; i <= n; i++) {
    sum += i;
}
```

The mathematical result is:

$$
\sum_{i=1}^{n} i = \frac{n(n+1)}{2}
$$

| Input | Output |
| ----: | -----: |
|     1 |      1 |
|     2 |      3 |
|     3 |      6 |
|     4 |     10 |

* [x] Write algorithm
* [x] Test algorithm
* [ ] Optimize algorithm

---

# End of Markdown Test

If your renderer can correctly display everything above, it has very good Markdown support.
