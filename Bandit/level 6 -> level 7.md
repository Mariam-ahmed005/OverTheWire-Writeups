**Level Goal**
- The password for the next level is stored somewhere on the server and has all of the following properties:

owned by user bandit7
owned by group bandit6
33 bytes in size

---

**Commands used:** 
- ```bash
  ls
  cat
  find
  cd
  
**Steps**:
- Redirecting errors to filter the list of the files that match our description
- ```bash
  cd ..
  ls
  find / -user bandit7 -group bandit6 -size 33c  2>/dev/null
  cat ./var/lib/dpkg/info/bandit7.password

***Photo Evidence Of Access:***
###
<img width="500" height="400" alt="image" src="https://github.com/user-attachments/assets/af385897-c06e-4e75-9729-958bac190d07" />

##
###
***Key learnings:***
- Finding files uowned by specific users and groups 
- Redirecting errors into a "nothing" file to filter the list of files 
  
