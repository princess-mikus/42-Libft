<h1>LibFT function list</h1>
<h2>🔧 Standard C Functions 🔧</h2>
<h3>🧠 Memory Functions 🧠</h3>
<table>
  <tr>
    <td> Function </td>
    <td> Description </td>
  </tr>
  <tr>
    <td> ft_memset </td>
    <td> fill memory with a constant byte </td>
  </tr>
  <tr>
    <td> ft_bzero </td>
    <td> fill memory with zeros </td>
  </tr>
  <tr>
    <td> ft_memcpy </td>
    <td> copies n bytes from memory area src to memory area dest. The memory areas can't overlap </td>
  </tr>
  <tr>
    <td> ft_memmove </td>
    <td> copies n bytes from memory area src to memory area dest. The memory areas may overlap </td>
  </tr>
  <tr>
    <td> ft_memchr </td>
    <td> Searches for a byte in memory </td>
  </tr>
  <tr>
    <td> ft_memcmp </td>
    <td> Compares two memory blocks </td>
  </tr>
  <tr>
    <td> ft_calloc </td>
    <td> Allocates memory (using malloc) and then zeroes it </td>
  </tr>
</table>

<h3>🧵 String Functions 🧵</h3>
<table>
  <tr>
    <td> Function </td>
    <td> Description </td>
  </tr>
  <tr>
    <td> ft_strlen </td>
    <td> Returns string length </td>
  </tr>
  <tr>
    <td> ft_strlcpy </td>
    <td> Safe string copy </td>
  </tr>
  <tr>
    <td> ft_strlcat </td>
    <td> Safe string concatenation </td>
  </tr>
  <tr>
    <td> ft_strchr </td>
    <td> Finds first occurrence of a char in a string </td>
  </tr>
  <tr>
    <td> ft_strrchr </td>
    <td> Finds last occurrence of a char in a string </td>
  </tr>
  <tr>
    <td> ft_strnstr </td>
    <td> Locates a string inside another string </td>
  </tr>
  <tr>
    <td> ft_strncmp </td>
    <td> Compares two strings (up to n chars) </td>
  </tr>
  <tr>
    <td> ft_strdup </td>
    <td> Duplicates a string </td>
  </tr>
</table>


<h3>🔠 Character Functions 🔠</h3>
<table>
  <tr>
    <td> Function </td>
    <td> Description </td>
  </tr>
  <tr>
    <td> ft_isalpha </td>
    <td> Checks if a character is alphabetic </td>
  </tr>
  <tr>
    <td> ft_isdigit </td>
    <td> Checks if a character is a digit </td>
  </tr>
  <tr>
    <td> ft_isalnum </td>
    <td> Checks if a character is alphanumeric </td>
  </tr>
  <tr>
    <td> ft_isascii </td>
    <td> Checks if a character is ASCII </td>
  </tr>
  <tr>
    <td> ft_isprint </td>
    <td> Checks if a character is printable </td>
  </tr>
  <tr>
    <td> ft_toupper </td>
    <td> Converts character to uppercase </td>
  </tr>
  <tr>
    <td> ft_tolower </td>
    <td> Converts character to lowercase </td>
  </tr>
</table>

<h3>📝 I/O Functions 📝</h3>
<table>
  <tr>
    <td> Function </td>
    <td> Description </td>
  </tr>
  <tr>
    <td> ft_putchar_fd </td>
    <td> Writes a character to a file descriptor </td>
  </tr>
  <tr>
    <td> ft_putstr_fd </td>
    <td> Writes a string to a file descriptor </td>
  </tr>
  <tr>
    <td> ft_putendl_fd </td>
    <td> Writes a string + newline to a file descriptor </td>
  </tr>
  <tr>
    <td> ft_putnbr_fd </td>
    <td> Writes a number to a file descriptor </td>
  </tr>
</table>

<h3>♻️ Type Conversion Functions ♻️</h3>
<table>
  <tr>
    <td> Function </td>
    <td> Description </td>
  </tr>
  <tr>
    <td> ft_atoi </td>
    <td> Converts a string to an integer </td>
  </tr>
  <tr>
    <td> ft_itoa </td>
    <td> Converts an integer to a string </td>
  </tr>
</table>

<h2>🧰 Additional Utility Functions 🧰</h2>
<h3>🧵 String Functions 🧵</h3>
<table>
  <tr>
    <td> Function </td>
    <td> Description </td>
  </tr>
  <tr>
    <td> ft_substr </td>
    <td> Extracts a substring from a larger string </td>
  </tr>
  <tr>
    <td> ft_strlcpy </td>
    <td> Safe string copy </td>
  </tr>
  <tr>
    <td> ft_strjoin </td>
    <td> Concatenates two strings </td>
  </tr>
  <tr>
    <td> ft_strtrim </td>
    <td> Trims characters from the start and end of a string </td>
  </tr>
  <tr>
    <td> ft_split </td>
    <td> Splits a string into multiple ones by a delimiter </td>
  </tr>
  <tr>
    <td> ft_strmapi </td>
    <td> Applies a function to each character of a string </td>
  </tr>
  <tr>
    <td> ft_striteri </td>
    <td> Applies a function to each character (with index) </td>
  </tr>
</table>

<h3>🔜 Linked List Functions 🔜</h3>
<table>
  <tr>
    <td> Function </td>
    <td> Description </td>
  </tr>
  <tr>
    <td> ft_lstnew </td>
    <td> Creates a new list node </td>
  </tr>
  <tr>
    <td> ft_lstadd_front </td>
    <td> Adds a node to the front of a list </td>
  </tr>
  <tr>
    <td> ft_lstadd_back </td>
    <td> Adds a node to the end of a list </td>
  </tr>
  <tr>
    <td> ft_lstsize </td>
    <td> Counts nodes in a list </td>
  </tr>
  <tr>
    <td> ft_lstlast </td>
    <td> 	Returns the last node </td>
  </tr>
  <tr>
    <td> ft_lstdelone </td>
    <td> Deletes a single node </td>
  </tr>
  <tr>
    <td> ft_lstclear </td>
    <td> Deletes an entire list </td>
  </tr>
  <tr>
    <td> ft_lstiter </td>
    <td> Applies a function to each node </td>
  </tr>
  <tr>
    <td> ft_lstmap </td>
    <td> Creates a new list by applying a function to each node </td>
  </tr>

</table>
