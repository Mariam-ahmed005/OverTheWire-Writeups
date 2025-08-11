**Level Goal**
- The password for the next level is stored in a file somewhere under the inhere directory and has all of the following properties:

---

**Commands used:** 
- ```bash
  ls
  cd
  find
  cat 
**Steps**:
- ```bash
  ls
  cd inhere
  find -size 1033c ! -executable
  cat ./maybehere07/.file2


***Photo Evidence Of Access:***
###

##
###
***Key learnings:***
- Finidng files with specific sizes (c for bytes, K for Kilobytes M for Megabyte
- Finding executable and non executable files
- Filtering results using multiple conditions (size, permission)
