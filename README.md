![image](https://i.imgur.com/PYyigBm.png)
# Azure - Resoure Groups and Virtual Machines
In this tutorial, we will start off with a simple creation of a resource group. After we complete that, we will create a Virtual machine which will be the jump point for many of our future projects.

## Environments and Technologies Used

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop

- ## Operating System Used

- Windows 10 (21H2)

## Creating A Resource Group

![Image](https://i.imgur.com/zKrXdER.png)
- Inside the Azure portal, either click on "Resource Groups" and then select "Create Resource Group" or search for "Resource Groups" and click on "Create Resource Group".

![Image](https://i.imgur.com/4mLUDcX.png)

- Create

![Image](https://i.imgur.com/43fY5u5.png)

- Name the group: change location (if desired).
- Click "Review + Create"

![Image](https://i.imgur.com/KdLYnY9.png)

- Once Validated, Click Create. Your Resource Group will now show up under "Resources" when you naviagte to home.

---

![Image](https://i.imgur.com/8AA7SSs.png)
## Creating a Virtual Machine

- Click on the "Virtual Machines" icon in the Azure suite, or search for it and then click on it.

![Image](https://i.imgur.com/aYyifHG.png)

- Create -> Azure Virtual Machine (You can actually generate a resource group from this section as well if you did not have one created and wanted to save time).

![Image](https://i.imgur.com/PiRPi8s.png)

- Name the Virtual Machine, change the security type to "Standard," select the "Windows 10 Enterprise" image, leave the zone as pre-selected, set the size to "4 vCPUs" for a stable image, create a username and password, and check the "Licensing" box -> Review + Create -> Create

![Image](https://i.imgur.com/ytULvuV.png)

- Wait for creation of assets, "Go to Resource", copy "Public IP address", open "Remote Desktop Connection" from start, input copied IP address into computer line, "Connect", "More Choices", "Use a different account", enter credentials used upon creation of the virtual machine, "Ok", "Yes"

- After clicking 'OK,' you will be directed to the image you selected and can now proceed to manipulate it as desired.
  ---
![Image](https://i.imgur.com/NNXm3Zo.png)
## Extra: Creating a Storage Account 
  
![Image](https://i.imgur.com/19GwokX.png)

- Click or search "Storage accounts". Create Storage account.

![Image](https://i.imgur.com/tFQaQ2U.png)

- Make sure that RG-01 (or the name of your corresponding resource group) is selected. Input a uniqe name for your "Storage account" to be created. "Review".

![Image](https://i.imgur.com/PEEmhiP.png)

- "Create".

![Image](https://i.imgur.com/pkiW79I.png)

- Wait for Storage account to be completed (It will be quick,) "Go to resource", click "Containers" -> Container -> Name -> Input name (e.g. cclab01). "Create"

![Image](https://i.imgur.com/6P5vQGG.png)
- Create a file through notepad on your desktop and upload it to the Storage account. Click "cclab01" -> "Open" -> Upload cclab01 -> "Upload".

- ![Image](https://i.imgur.com/9TNLD2w.png)
- Edit the File within the Storage Account. Type in document, "Save", "Download".

![image](https://i.imgur.com/0yuhqzw.png)
- Observe changes made to document.


![Image](https://i.imgur.com/e4YRwwz.png)
- Navigate to "Resource groups", select "RG-01" (Or your chosen RG name), "Delete resource group", "Delete", "Delete" (deletion is performed to prevent incurring any costs, whether through free credits or a pay-as-you-go subscription).

---

## After thoughts

Virtual Machines and Remote Desktop Connections are quite useful for many of jobs that involve IT. Originally, I was indifferent to the technologies, but now after bulding and practicing, I have a greater apprectiation for those that utilize these technologies to their highest degree. 

Azure's storage accounts are fascinating feture in the Azure suite. Even though they might not seem like a big deal, especially since we've been using them in a way similar to Google Docs, they actually offer a bunch of useful features. For example, you can create a website, store it in the storage account, and share it on the internet. Plus, you can connect things up using languages like Python, C++, Java, and more.
