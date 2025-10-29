
# Reviewing-Unallocated-Space-Extracting-Data-with-Tools-Digital-Investigation-Processes
# name:thenmozhi(212223100059)

## AIM:
To review unallocated space in a disk image, extract data using forensic tools, and understand the digital investigation process.

## DESIGN STEPS:
### Step 1:
Use tools like Autopsy or Sleuth Kit (blkls, icat) to identify and analyze unallocated space.

### Step 2:
Extract data from unallocated space and examine for hidden or deleted content.

### Step 3:
Document and interpret findings as part of the digital investigation process.

## PROGRAM:
Data Extraction and Investigation Tool Usage
```bash
lsblk
```

```bash
sudo dd if=/dev/sda of=/home/kali/disk.img bs=512
```

```bash
mmls ~/disk.img
```
```bash
sudo ls -lh disk.img
```
```bash
strings disk.img | less

```

## OUTPUT:
![image](https://github.com/user-attachments/assets/83a427da-d372-4b72-8e54-c874c8e31f37)
![image](https://github.com/user-attachments/assets/4ed4a4a3-542d-42b8-af06-9c1eedaec949)

![image](https://github.com/user-attachments/assets/1fc8e81f-12c1-4927-92ca-a4a0a500950e)

![image](https://github.com/user-attachments/assets/d2beee48-5fee-4476-84fd-ab24954f077d)
![image](https://github.com/user-attachments/assets/4aff8fc4-e59c-475e-bdb2-658f15c67c50)

## RESULT:
The unallocated space was successfully analyzed, data was extracted, and the digital investigation process was followed effectively.


