# CSE499-MediTrack. 

->A mobile application.                                             
->For patient, aged and sick people.                                
->Notifying a person about their medicine taking time as their given input.                                   
->Keeping track on medicine and notify for taking medicine.                                   
->Reminding about their doctor’s checkup schedule.   

#### Required Platforms & Programming Language: 
->Html                                                    
-> Java                                       
-> MySQL                                 
->Xampp                                                           
->Android Studio    

##   Installing "Android Studio IDE" and "Android SDK"
Installing Android software is probably the most challenging part of this project. It takes times - from 30 minutes to n hours to forever - depending on your luck, your programming knowledge, and your PC. You probably need a fairly decent PC (with 8GB RAM) and 10GB of free disk space to run the Android emulator!!! Running on "actual" Android phone/tablet requires much lesser resources.                                                                

### Step 0: Pre-Installation Check List
Before installing Android SDK, you need to install Java Development Kit (JDK). Read "How to install JDK". Ensure that your JDK is at or above 1.8. You can check your JDK version with command "javac -version" (compiler) and "java -version"(runtime).
Uninstall older version(s) of "Android Studio" and "Android SDK", if any.
The installation and many operations take a LONG time to complete. Do NOT stare at your screen or at the ceiling. Browse through the "Android for Developers" @ https://developer.android.com.
We need to install two HUGE packages:
Android Studio (IDE) (about 1.6 GB), which is an Integrated Development Environment (IDE) based on IntelliJ (a popular Java IDE); and
Android SDK (Software Development Kit) (about 5 GB) for developing and running Android apps.
### Step 1: Install "Android Studio IDE"
Reference: "Install Android Studio" @ https://developer.android.com/studio/install.

(For Windows)
Check that environment variable JAVA_HOME is set to the JDK installation directory via command "set JAVA_HOME". Otherwise, Follow the steps HERE.
Check the system requirements for Android Studio/SDK @ https://developer.android.com/studio#Requirements e.g., For Windows 10, 8GB of RAM, 8GB of disk space, and 1280x800 minimum screen resolution. Take note that you should have enough space on C drive. Insufficient space on C drive will take you many days.
Goto "Android Studio" under "Android Developers" @ https://developer.android.com/studio ⇒ Click "Download Android Studio" (Android Studio Bumblebee 2021.x.x for Windows 64-bit (872MiB)) to download the executable installer "android-studio-2021.x.x.xx-windows.exe".
Run the downloaded installer ⇒ You may watch a short video @ https://developer.android.com/studio/install.
In "Choose Components", select "Android Studio" and "Android Virtual Device" (space required: 2.7GB).
In "Configuration Settings Install Location", accept the default "C:\Program Files\Android\Android Studio".
In "Choose Start Menu Folder", accept the default ⇒ Install.
Launch Android Studio. Continue to Step 2.
by default, the "Android Studio IDE" will be installed in "C:\Program Files\Android\Android Studio", and the "Android SDK" in "c:\Users\username\AppData\Local\Android\Sdk".

Notes (SKIP): You can also use the ZIP version: Download the Windows 64-bit ZIP version (about 1.5GB) ⇒ UNZIP into a folder of your choice ⇒ Run "bin\studio64.exe" to launch the Android Studio ⇒ It will enter the "setup" for the first launch ⇒ "Do not Import Settings" ⇒ In "Welcome", click "Next" ⇒ In "Install Type", choose "Custom" (so that you can see what is going on) ⇒ In "Select Default JDK Location", use default ⇒ In "Select UI Theme", choose one that you like ⇒ In "SDK Components Setup", select "Android Virtual Device (1.05GB) ⇒ Take note of the "Android SDK Location" with default of "C:\Users\username\AppData\Local\Android\Sdk" ⇒ In "Emulator Settings", use default ⇒ In "Verify Settings", check the settings and choose "Finish" ⇒ In "Download Components", click "Details" and check that nothing fails ⇒ Wait ⇒ Wait ⇒ Wait.
 

 
