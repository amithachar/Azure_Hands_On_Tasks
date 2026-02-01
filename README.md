Task 1: Create a storage account using Azure Portal. Enable secure transfer, add tags, create a container, and upload a sample file. Share the container link with limited access.

Create a storage account

<img width="856" height="666" alt="image" src="https://github.com/user-attachments/assets/6e41285c-0639-4490-8a94-965cf208d6c1" />

Enable Secure Transfer

<img width="864" height="525" alt="image" src="https://github.com/user-attachments/assets/aba9d38d-2128-4bcf-a39a-19fe5cfab362" />

Add tags

<img width="918" height="359" alt="image" src="https://github.com/user-attachments/assets/3ce1732b-cfd7-44ee-9726-f9b8b8e1b195" />

AFTER CREATING STORAGE ACCOUNT CREATE BLOB STORAGE

Create a Blob Container { Container}

<img width="919" height="172" alt="image" src="https://github.com/user-attachments/assets/166c0728-4dc0-4840-abab-2a21129f85de" />

Upload a Sample File

<img width="913" height="214" alt="image" src="https://github.com/user-attachments/assets/9468b759-6b7a-4466-a423-4c6a8886946c" />

Click Generate SAS

<img width="891" height="405" alt="image" src="https://github.com/user-attachments/assets/4387c718-cd7e-4ee3-a888-5d2df8000a8c" />

<img width="891" height="1042" alt="image" src="https://github.com/user-attachments/assets/d00d377c-7a19-41e6-bad1-3f9ed70d4c93" />

<img width="899" height="305" alt="image" src="https://github.com/user-attachments/assets/75ea0ed4-92e9-4800-92ba-efe1fa730d45" />

Anyone with this link can read the file

<img width="940" height="276" alt="image" src="https://github.com/user-attachments/assets/64132cf7-43ee-42bf-80bb-a0f3cf1aa7c2" />


Task 2: Create a VM (use existing if needed), set up Azure Monitor to track CPU usage, and configure an alert to notify via email if CPU exceeds 80% over a 5-minute period 

<img width="940" height="701" alt="image" src="https://github.com/user-attachments/assets/d98b4578-39ea-4837-b9b4-47670d7e1c1d" />

<img width="940" height="699" alt="image" src="https://github.com/user-attachments/assets/c33366ce-fb7c-46f4-a9f9-0d7242f512cd" />

<img width="940" height="623" alt="image" src="https://github.com/user-attachments/assets/182e3cb1-765c-45fa-94c3-f43929a6fda3" />

<img width="940" height="431" alt="image" src="https://github.com/user-attachments/assets/127b455d-4665-4968-ad8b-bc583c9421a6" />

<img width="940" height="513" alt="image" src="https://github.com/user-attachments/assets/7526c7ff-8523-4e50-b742-58667e63dfde" />

Connected to linux VM

<img width="940" height="249" alt="image" src="https://github.com/user-attachments/assets/70ae9b4e-9a74-411e-a6b2-946a99b975d1" />

Go to CPU Usage Metric

<img width="940" height="384" alt="image" src="https://github.com/user-attachments/assets/2b32c34f-d911-4942-82a8-058df8c42dc1" />

Configure Alert Condition

<img width="940" height="671" alt="image" src="https://github.com/user-attachments/assets/55b32542-03fd-4b97-9974-000f6c3d3e2c" />

<img width="940" height="483" alt="image" src="https://github.com/user-attachments/assets/ac964367-ebc5-4e36-a787-d6c84ae05ee4" />

<img width="940" height="206" alt="image" src="https://github.com/user-attachments/assets/e5fca095-c883-4e18-9de6-7bf40ccbf163" />

Alert rule created.

<img width="940" height="148" alt="image" src="https://github.com/user-attachments/assets/a8312f1d-72b2-4db2-803a-722e0d34238f" />

email setup is verfied in mail

<img width="829" height="479" alt="image" src="https://github.com/user-attachments/assets/11b6605b-1fc1-4687-99f5-9da0e8ded71f" />

Installing stress command for testing.

```
sudo apt update
sudo apt install stress -y
stress --cpu 2 --timeout 300

```

VM is 80% cpu consumed.

<img width="940" height="369" alt="image" src="https://github.com/user-attachments/assets/8d54ec2c-c90b-41a7-ba38-125c968d423b" />

Email is triggered to mail.

<img width="940" height="444" alt="image" src="https://github.com/user-attachments/assets/f079479a-ce65-4082-8de8-f98b6b2d1e80" />


















