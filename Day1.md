![image](https://github.com/pavankumar0077/Devops-SRE/assets/40380941/a1ad27e1-09de-4a5f-856f-d95b1101a031)

Collaboration -- JIRA
DevOps - Dev Team | Operation team -- we are bridge btw them

![image](https://github.com/pavankumar0077/Devops-SRE/assets/40380941/89491f40-6810-4bd5-a135-a4508fc63db2)

![image](https://github.com/pavankumar0077/Devops-SRE/assets/40380941/62f356d8-483a-4e11-8716-933e21e8026a)

![image](https://github.com/pavankumar0077/Devops-SRE/assets/40380941/a286f393-7674-45fa-8227-dd47e8d59768)

![image](https://github.com/pavankumar0077/Devops-SRE/assets/40380941/13dfa323-5aa1-4c3c-b4ee-daa58312fdaf)

.git == local repo (Maintained by us)
GITHUB == central repo (Maintained by github)

/mnt -- increase the disk space
/proc -- process, cpu usage and etc
/bin -- installed software's will contains here
/opt -- To stores the user applications
/lib -- Use to main OS (Kernel)
/etc -- to stores programble files


![image](https://github.com/pavankumar0077/Devops-SRE/assets/40380941/d250efd1-9f3c-4b74-aa55-8380420fc09a)

- (-) means files
- (d) means dir

- user group all -- (-rw-r--r--) --user having read and write, group having -- read, all having -- read

1EC2 WILL HAVE 1EBS 
3 ecs instance and disk attach we use EFS (3ECS -- 1 EFS)

EBS - harddisk (Elastic block store)
EFS - Shared Disk 

S3 -- Storing static objects like fiels/zip/tar and etc

Services
---
1) EC2
2) EBS
3) EFS
4) S3

AMI
--
1) Convert machine into Image
2) Like backup (Ex)

=======================================================
=======================================================


![image](https://github.com/pavankumar0077/Devops-SRE/assets/40380941/e50bfed5-10ef-4fbe-ab4a-4a5850d28973)

```

1. **Amazon EBS (Elastic Block Store)**:
   - **What it is**: Think of EBS as a virtual hard drive that you can attach to your virtual servers (EC2 instances) on Amazon Web Services (AWS).
   - **Use case**: It's best for applications that need fast and reliable storage directly connected to a single server, like a computer's hard drive.
   - **Example**: Storing the operating system and important software on your computer's hard drive.

2. **Amazon EFS (Elastic File System)**:
   - **What it is**: EFS is like a shared network drive that multiple servers (EC2 instances) can access simultaneously. It's good for sharing files across multiple instances.
   - **Use case**: Ideal for situations where you need to collaborate or share data between multiple servers, such as web applications that run on multiple servers.

3. **Amazon S3 (Simple Storage Service)**:
   - **What it is**: S3 is like a big, organized storage space in the cloud. It's designed for storing and retrieving large amounts of data, like files, images, and backups.
   - **Use case**: Great for storing files, backups, and data you want to access from anywhere on the internet, like photos on your phone that you back up to the cloud.

In summary:
- **EBS** is like your computer's hard drive, directly connected to one server for fast and reliable storage.
- **EFS** is a shared network drive that multiple servers can access, ideal for collaboration and sharing files.
- **S3** is a versatile cloud storage service for storing and accessing large amounts of data, accessible from anywhere on the internet.

Remember that each of these services has its own pricing model and specific use cases, so choosing the right one depends on your particular needs.
```
![image](https://github.com/pavankumar0077/Devops-SRE/assets/40380941/0594f737-9412-4982-860d-f401411015ca)




