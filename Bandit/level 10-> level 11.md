Level Goal
The password for the next level is stored in the file data.txt, which contains base64 encoded data

Commands used:
<pre>
  ls
  cat
  echo
</pre>

Steps:
<pre>
  ls
  cat data.txt
  echo "encoded_file"|base64  --decode
</pre>

Photo Evidence Of Access:
<img width="1416" height="886" alt="image" src="https://github.com/user-attachments/assets/c857e689-57e2-47b3-942d-77b551f45cb4" />

Key learnings:
- What are base64 encoded data
- How to decode base64 file
  
