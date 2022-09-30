# MarkText-portable

This is a portable of **MarkText** application, which manages **installation**, **updating** and **creating Menu Icons** of MarkText.

### Installation

No installation needed! **MarkText-portable** is what its name suggests- a **Portable**. Though setup is needed, and a knowledge of what to run when. All of the upcoming portion of this **README** focuses on providing the knwledge for the same.

### Get MarkText-portable

You may get the **MarkText-portable** as a **.zip** file from its [Github Repository](https://github.com/lakshayrohila/marktext-portable). Here are the complete steps (with illustrations) for getting **MarkText-portable**.

1. Visit [Github Repository](https://github.com/lakshayrohila/marktext-portable) in a web-browser.

2. Click on **Code** button that is visible there.
   
   ![Step 2](/root/spot/images/1.png "Step 2")

3. Clicking the **Code** button will open up a drop-down menu (refer to the below image). In the drop-down menu, click **Download ZIP**.
   
   ![Step 3](/home/spot/images/2.png "Step 3")

4. This will download a file named **marktext-portable-master.zip**. Use your favourite utility to extract the **zip** file downloaded.

5. **Step 4** will extract the **zip** file to a folder named **marktext-portable-master** (In case you don't like the name, rename the directory as you would rename any other directory). Open up the directory. It will look something like this-
   
   ![Step 5](/root/spot/images/5.png "Step 5")
   
   Here, there will be 4 executable files. These are-
   
   1. **LAUNCH** - This will launch **MarkText**.
   
   2. **UPDATER** - This is used internally by the portable to check and install any updates, if present. This needs not be run manually by the user.
   
   3. **INSTALL** - This script will create **sym-links** in order to create **Menu Icon** and **marktext** which can be run directly from a terminal.
      
      (Note that if you're having some problems running INSTALL via **ROX** file manager, open up a terminal and then run the script from there.)
   
   4. **UNINSTALL** - It is the reverse of **INSTALL** script, i.e. it will remove already created **sym-links**.

6. Run the **LAUNCH** script firstly. This will ask you to install new update. **DO NOT REFUSE**. **MarkText-portable** doesn't come with executable file of **MarkText** application. Instead it downloads them when a new update is available or when it is the first run of the portable.

7. While downloading executable file of **MarkText**, a terminal screen will keep you updated about the download. After few minutes, your **MarkText**'s application screen would be in front of you.

8. Now you may even run **INSTALL** script to create **Menu Icon** of the application.
