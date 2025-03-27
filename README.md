# Surveying and Preserving the Digital Crime Scene
## Name : Syed Huzaif
## Registor number : 212224240166
## **Aim:**
Data recovery from unallocated space, using forensic tools(Autospy) to extract and analyze data.

## **Implementation steps:**

### **1. Copy Files to the Virtual Disk**  
- Open **File Explorer** → Go to the new drive (`C: or D:`), where the folder created in the New Virtual Disk
- Create a new folder (`Autospy`) and copy **images or files** into it.  

### **2. Delete the Files**  
- Select any one or two images → Press **Delete**.  
- Empty the **Recycle Bin** to permanently delete them.  

### **3. Recover Deleted Files Using Autopsy**  
### **Open Autopsy & Create a New Case** 

- Launch **Autopsy** and **Run as a administrator**  
- Click **Create New Case**.  

![](./images/a1.png)

- Enter a **Case Name** (e.g., `Autopsy1`).  
- Choose a **Case Folder** location.  
- Click **Next** → Click **Finish**.  

![](./images/a2.png)

### **Add the Virtual Disk as an Evidence Source**  
- Click **Add Data Source**  → **Select Host**

![](./images/a3.png)

- Select **Local Disk** → **next** 

![Screenshot 2025-03-27 142113](https://github.com/user-attachments/assets/fc3dc81c-f0f2-4dfa-95e6-7a6ed5b40457)


- Select Disk → **Choose the VHD drive (`Drive1`)**

![](./images/a5.png)

- Click **Next** → Keep default settings → Click **Finish**.  
- Wait for Autopsy to process the disk.  

### **Recover Deleted Files**  
- Go to **File Views** (left panel).  

![](./images/a6.png)

![](./images/a7.png)

- Click **Deleted Files** → Find your deleted images.  
- Right-click an image → Click **Extract File**.  

![Screenshot 2025-03-27 141103](https://github.com/user-attachments/assets/99bd4907-12f6-475b-a4d6-deb0992dd315)


- Select a folder to see the recovered files (e.g., `C:\forensic`).  
- Image is recovered successfully.


## Output :
### Folder before deleting the files
![](./images/f1.png)

### Folder after deleting the files
![Screenshot 2025-03-27 140525](https://github.com/user-attachments/assets/d08eb5cb-27ca-4b76-b84f-b3a0bb50ba57)


### Folder after extracting the deleted images using autopsy

![Screenshot 2025-03-27 140048](https://github.com/user-attachments/assets/02baf109-72d7-4578-a502-b6a235c027b4)

## Result:
Successfully extracted the deleted files from unallocated space using the Autospy tool.
