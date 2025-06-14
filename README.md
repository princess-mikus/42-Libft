<h1>📚 Libft 📚</h1>
Libft is a custom C static-linked library developed at  <a href="https://www.42network.org/"></a>42 School, featuring reimplementations of standard functions and additional utilities.

<h2>📒 Function List 📒</h2>
<a href="/FUNCTIONS.md">Full function list and description</a>

<h2>✅ Features ✅</h2>
<ul>
  <li><b>POSIX Compliant</b> - Should run in any Unix like system (originally made for MacOS)</li>
  <li><b>Feature rich</b> - Not only contains LibC standard function not available in all systems (for example all the functions with l in Linux like strlcpy) but also list management functions and additional features (like split)</li>
  <li><b>Easy to read</b> - Easily readable, clean code using the internal 42's Norminette code etiquette</li>
  <li><b>Memory safe</b> - Does not contain leaks and does not crash (unless the original LibC function crashes too)</li>
</ul>

<h2>🛠️ Compilation and usage 🛠️</h2>
<h3>Build</h3>
Clone the repository

```Bash
git clone https://github.com/princess-mikus/42-Libft.git libft
```
And then call the Makefile inside it to create the .a file

```Bash
make -C libft
```
<h3>Usage</h3>
First include the header

```C
#include "libft.h"

```
and then don't forget to compile against the library
```Bash
gcc *your files* libft/libft.a -Ilibft
```
