# diff and patch Cheat Sheet
* **diff**
    diff is used to find differences between two files. On its own, it’s a bit hard to use; instead, use it with diff -u to find lines which differ in two files:

* **diff -u**
    diff -u is used to compare two files, line by line, and have the differing lines compared side-by-side in the same outpu

* **Patch**
    Patch is useful for applying file differences. See the below example, which compares two files. The comparison is saved as a .diff file, which is then patched to the original file!