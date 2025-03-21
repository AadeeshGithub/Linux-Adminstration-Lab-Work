# **Experiment - 3 & 4**  

*View the gedit man page. Use the `man -k ext4` command to find the command to tune ext4 file-system parameters. Brace expansion is used to generate discretionary strings of characters. Braces contain a comma-separated list of strings, or a sequence expression. The result includes the text that precedes or follows the brace definition.*  
#
### **Approach**  
Use the `man` command to view manual pages and search for commands related to `ext4`. Utilize brace expansion to generate sequences efficiently.  
### **Syntax**  

**`man [command]`**  
   Displays the manual page for the specified command.  

**`man -k [keyword]`**  
   Searches for the keyword in the manual pages and lists all matching entries.  

**`echo [pattern]`**  
   Outputs the result of a pattern or variable expansion.  

**`echo {start..end}`**  
   Expands a range of values from `start` to `end` and outputs the result.  

### **Example**
```
man gedit

```

```
man -k ext4

```

```
echo file{1,2,3}.txt

```

```
echo {a..e}

```
![Screenshot 2025-03-20 101243](https://github.com/user-attachments/assets/9de6d81f-650f-4262-b975-c93dd8f31f50)
