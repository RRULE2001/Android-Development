# Setting Up

## Downloads
1. Download visual studio code community
      - [Visual Studio Community](https://visualstudio.microsoft.com/vs/community/)
      - During the donwload, select these Workloads:
        - Mobile devlopment with C++
        - Mobile development with .NET 
2. Download these extensions:
      - To download extensions in visual studio go to the **Extensions tab**, then select **Manage Extensions**, the search for the extensions called:
        - [Java Tools for Android Projects (Visual Studio 2019)](https://marketplace.visualstudio.com/items?itemName=VisualCPPTeam.JavaToolsForAndroidProjVS2019)

## Creating a Project
1. Creating a Hello World application
      - With visual studio still open do this
        - File -> New -> Project -> Basic Application (Android, Ant) -> Next -> Create
        - If you are having trouble finding the applicatoon you can filter by using C++, Android, and Mobile

2. Connecting android device:
      - Enable Debugging on your device
      - Enable USB Debugging
        - These steps are different for Android version so use [this](https://docs.microsoft.com/en-us/xamarin/android/get-started/installation/set-up-device-for-development)
      - Download the Windows USB driver for your phone
        -  [This is what I used for galaxy S8+](https://developer.samsung.com/mobile/android-usb-driver.html)
      - Connect your phone to PC via USB Cable.
      - In the complier for my S8+ use **Debug**, **ARM64**, **samsung SM-G955U** then deploy the build by pressing the green arrow next to samsung SM-G955U

3. Creating an Emulator
      - https://docs.microsoft.com/en-us/xamarin/android/get-started/installation/android-emulator/hardware-acceleration?tabs=vswin&pivots=windows#hyper-v




      - Connect your phone to PC using USB Cable. If succesfully connected, you will find your device in emulators list. Select your device and Run. Application will launch on your device.
      - Other way is to manually create a .apk and and copy that file on to device and install it. This method is lot time consuming and not suitable for development purpose. Details at : http://developer.xamarin.com/guides/android/deployment,_testing,_and_metrics/publishing_an_application/part_1_-_preparing_an_application_for_release/

