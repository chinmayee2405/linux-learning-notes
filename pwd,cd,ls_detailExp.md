## 1. Understanding Your Location – `pwd`

Use `pwd` to **Print the Working Directory** (i.e., show where you are).

```bash
pwd
````
Example:
```bash
/home/sysadmin
```
## 2. Moving Around – cd
Use cd (change directory) to move between folders.

 | Command        |	Description                              |
 |:--------------:|:----------------------------------------:|
 | cd             |  Documents	Go into the Documents folder |
 |  cd /	        |  Go to the root directory                |
 |cd ~            |  Go to your home directory               |
 | cd ..          |  Move up one level (to parent directory) |
 |  cd School/Art |	 Move into nested folders                |

## 3. Absolute vs. Relative Paths
1. Absolute Path: Starts from root /
```bash
cd /home/sysadmin/Documents
```
2. Relative Path: Starts from current directory
```bash
cd Documents
```
## 4. Viewing Files – ls
List files and directories in the current location.

| Command  |   	Description                           |
|:--------:|:----------------------------------------:|
| ls       | 	Basic listing                           |
|ls -l	   |   Long/detailed listing                  |
|ls -lt    |  	Sorted by time (newest first)         |
|ls -lS	   |    Sorted by size                        |
|ls -lr	   |    Reversed order                        |
|ls -ltr   |   	Detailed, time-sorted, reversed       |
## 5. Understanding ls -l Output
```bash
-rw-r--r-- 1 root root 47816 Dec 7 2017 bootstrap.log
```
| Field      | Description                |
|------------|---------------------------:|
| -rw-r--r-- | Permissions                |
| 1          | Number of link             |
| root       | File owner                 |
| root       | Group owner                | 
| 47816      | Size in bytes              |
| Dec 7 2017 | Last modified date         |

