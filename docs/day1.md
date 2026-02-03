# Day 1: Mastering the Linux Environment

Welcome to the first session. Today we move from the Mouse to the Keyboard.

## 1. Why Linux? (0:00 - 0:30)
Linux is the standard for Bioinformatics because:
* **Stability:** Can run for months without rebooting.
* **Performance:** Handles 100GB+ genomic files easily.
* **Automation:** Write once, run a thousand times.

## 2. Linux Architecture
Linux consists of:
1. **The Kernel:** The brain managing hardware.
2. **The Shell (Bash):** Your translator.
3. **The Terminal:** Your window to the shell.



## 3. Navigating the "Library" (0:30 - 1:30)
Everything in Linux starts from the **Root (/)**.

### Essential Commands
| Command | Action | Example |
| :--- | :--- | :--- |
| `pwd` | Where am I? | `/home/harsha` |
| `ls -lh` | List files (human readable) | `ls -lh data.fastq` |
| `cd` | Change directory | `cd Documents` |
| `mkdir` | Create folder | `mkdir my_project` |



## 4. File Operations (1:30 - 2:30)
Managing data without a mouse.

* **Copying:** `cp source.txt destination.txt`
* **Moving/Renaming:** `mv old_name.txt new_name.txt`
* **Deleting:** `rm file.txt` (Careful! No recycle bin).
* **Reading:** `head -n 10 file.txt` (See first 10 lines).

## 5. Practical Exercise (2:30 - 3:00)
1. Open your terminal.
2. Create a folder named `workshop_test`.
3. Inside that folder, create a file named `hello.txt`.
4. Write your name inside it using `echo "Your Name" > hello.txt`.
5. Check the content using `cat hello.txt`.
