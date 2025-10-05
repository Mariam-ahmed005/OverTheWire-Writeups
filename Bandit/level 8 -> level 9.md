Level Goal

The password for the next level is stored in the file data.txt and is the only line of text that occurs only once


Commands used:
<pre>
  ls
  cat
  sort
  uniq
</pre>

Steps:
- method 1: count the number of occurance of each line then manually find "1"
<pre>
  ls
  cat
  sort data.txt | uniq -c
</pre>
- method 2: show only the unique line
<pre>
  ls
  cat
  sort data.txt | uniq -u
</pre>

Photo Evidence Of Access:

<img width="597" height="419" alt="image" src="https://github.com/user-attachments/assets/c427b764-7dca-47f6-a1ee-d89ea3a991e0" />

Key learnings:
- Learning the differences between -c (count) and -u (unique lines) when using uniq command
