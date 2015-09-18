CSCI 5828 - Fall 2015

Homework 2

Nuha Albadi

1. git init (master)

2. git add README.md (master)

3. git commit -m "commit 0" (master)

4. git add README.md (master)

5. git commit -m "commit 1" (master)

6. 4. git add README.md (master)

5. git commit -m "commit 2" (master)

6. git log (master)

7. git checkout 16c8ff8f49154ef911bcea23c1f65c196ad9973b (commit 0 on master)

8. git checkout -b bug-fix (master)

9. git add README.md (bug-fix)

10. git commit -m "commit 3" (bug-fix)

11. git add README.md (bug-fix)

12. git commit -m "commit 4" (bug-fix)

13. git merge master (bug-fix) //merge conflict 

14. git add README.md (bug-fix)

15. git commit -m "commit 5" (bug-fix)// resolved conflict 

16. git add README.md (bug-fix)

17. git commit -m "commit 6" (bug-fix) 

18. git log (bug-fix)

19. git checkout 2bc94de13877e1c4a05a00302db442ca919be2f7 (commit 4 on bug-fix)

20. git checkout -b bug-fix-experimental (bug-fix)

21. git add README.md (bug-fix-experimental)

22. git commit –m “commit 7” (bug-fix-experimental)

23. git add README.md (bug-fix-experimental)

24. git commit –m “commit 8” (bug-fix-experimental)

25. git add README.md (bug-fix-experimental)

26. git commit –m “commit 9” (bug-fix-experimental)

30. git checkout bug-fix (master)

31. git merge bug-fix-experimental (bug-fix) // merge conflict 

32. git add README.md (bug-fix)

33. git commit -m "commit 11" (bug-fix)
