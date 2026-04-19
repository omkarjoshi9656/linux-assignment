# Linux Commands - Practical Assignment
**Submitted by:** Omkar Joshi

---

## Task 1: Creating and Renaming Files/Directories

```bash
mkdir test_dir
touch test_dir/example.txt
mv test_dir/example.txt test_dir/renamed_example.txt
```
**Explanation:** `mkdir` creates a new directory. `touch` creates an empty file inside it. `mv` renames the file from `example.txt` to `renamed_example.txt`.

---

## Task 2: Viewing File Contents

```bash
cat /etc/passwd
head -5 /etc/passwd
tail -5 /etc/passwd
```
**Explanation:** `cat` displays the full file content. `head -5` shows the first 5 lines. `tail -5` shows the last 5 lines of `/etc/passwd`.

---

## Task 3: Searching for Patterns

```bash
grep "root" /etc/passwd
```
**Explanation:** `grep` searches for the word "root" in `/etc/passwd` and prints all matching lines.

---

## Task 4: Zipping and Unzipping

```bash
zip -r test_dir.zip test_dir
unzip test_dir.zip -d unzipped_dir
```
**Explanation:** `zip -r` compresses the `test_dir` directory into `test_dir.zip`. `unzip -d` extracts it into a new directory called `unzipped_dir`.

---

## Task 5: Downloading Files

```bash
wget https://example.com/sample.txt
```
**Explanation:** `wget` downloads a file from the given URL and saves it in the current directory.

---

## Task 6: Changing Permissions

```bash
touch secure.txt
chmod 444 secure.txt
ls -l secure.txt
```
**Explanation:** `touch` creates the file. `chmod 444` sets read-only permission (`r--r--r--`) for owner, group, and others. `ls -l` verifies the permissions.

---

## Task 7: Working with Environment Variables

```bash
export MY_VAR="Hello, Linux!"
echo $MY_VAR
```
**Explanation:** `export` sets the environment variable `MY_VAR` with the value `Hello, Linux!`. `echo $MY_VAR` prints the value to confirm it is set correctly.
