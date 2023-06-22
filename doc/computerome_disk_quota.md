# Disk quota exceeded

Computerome allocates 10 Gb disk quota for each user's home (`~`). If you exceed this quota, you will not be able to write to your home directory. A lot of commands will fail with strange error messages. 

It is always a good practice to store data in your group data folder (/home/projects/<your_group_id>/data) or your personal folder in your group (/home/projects/<your_group_id>/people/<your_user_id>).

Sometimes it could be tricky to find out which files are taking up the space in your home folder (`~`).


Find the 10 largest files in your home folder:

```bash
du -aBm ~ 2>/dev/null | sort -nr | head -n 10
```

