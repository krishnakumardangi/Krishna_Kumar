# GREP in Linux
Grep is a powerful command-line tool used in Linux for searching text patterns within files. Here are some basic commands related to grep:

1. **grep [pattern] [file]**: Searches for the specified pattern in the given file(s). For example:
   ```
   grep "example" file.txt
   ```

2. **grep -r [pattern] [directory]**: Recursively searches for the pattern in all files within the specified directory and its subdirectories. For example:
   ```
   grep -r "example" /path/to/directory
   ```

3. **grep -i [pattern] [file]**: Performs a case-insensitive search for the pattern in the file(s). For example:
   ```
   grep -i "example" file.txt
   ```

4. **grep -v [pattern] [file]**: Displays all lines that do not match the pattern in the file(s). For example:
   ```
   grep -v "example" file.txt
   ```

5. **grep -n [pattern] [file]**: Displays the line numbers along with the lines containing the pattern. For example:
   ```
   grep -n "example" file.txt
   ```

6. **grep -w [pattern] [file]**: Searches for whole-word matches of the pattern in the file(s). For example:
   ```
   grep -w "example" file.txt
   ```

7. **grep -E [pattern] [file]**: Enables extended regular expressions for the search pattern. For example:
   ```
   grep -E "exa(mple|mple)" file.txt
   ```

8. **grep -c [pattern] [file]**: Displays only the count of lines matching the pattern in the file(s). For example:
   ```
   grep -c "example" file.txt
   ```

9. **grep --color [pattern] [file]**: Highlights the matching pattern in color within the output. For example:
   ```
   grep --color "example" file.txt
   ```

These are some basic grep commands, but grep offers many more options and functionalities for text searching and manipulation in Linux.
