Level Goal
The password for the next level is stored in the file data.txt in one of the few human-readable strings, preceded by several ‘=’ characters.

Commands used:
<pre>
  ls
  cat
  grep
  strings
</pre>

Steps:
<pre>
  ls
  cat data.txt
  strings data.txt | grep "^="
</pre>

Photo Evidence Of Access:

<img width="596" height="417" alt="Screenshot 2025-10-10 at 1 06 03 AM" src="https://github.com/user-attachments/assets/83ccbc51-8680-4820-ab76-9940dd7a2876" />


Key learnings:
- Using strings command
- Finding strings with specific criteria
