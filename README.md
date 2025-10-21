# Devices-Manager:

</br>

![Compiler](https://github.com/user-attachments/assets/a916143d-3f1b-4e1f-b1e0-1067ef9e0401) &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;: ![10 Seattle](https://github.com/user-attachments/assets/c70b7f21-688a-4239-87c9-9a03a8ff25ab) ![10 1 Berlin](https://github.com/user-attachments/assets/bdcd48fc-9f09-4830-b82e-d38c20492362) ![10 2 Tokyo](https://github.com/user-attachments/assets/5bdb9f86-7f44-4f7e-aed2-dd08de170bd5) ![10 3 Rio](https://github.com/user-attachments/assets/e7d09817-54b6-4d71-a373-22ee179cd49c)   
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;![10 4 Sydney](https://github.com/user-attachments/assets/e75342ca-1e24-4a7e-8fe3-ce22f307d881) ![11 Alexandria](https://github.com/user-attachments/assets/64f150d0-286a-4edd-acab-9f77f92d68ad) ![12 Athens](https://github.com/user-attachments/assets/59700807-6abf-4e6d-9439-5dc70fc0ceca)  
![Components](https://github.com/user-attachments/assets/d6a7a7a4-f10e-4df1-9c4f-b4a1a8db7f0e) : ![None](https://github.com/user-attachments/assets/30ebe930-c928-4aaf-a8e1-5f68ec1ff349)  
![Discription](https://github.com/user-attachments/assets/4a778202-1072-463a-bfa3-842226e300af) &nbsp;&nbsp;: ![Devices Manager](https://github.com/user-attachments/assets/609320c6-e79f-435f-83d2-a9ca78c8d535)  
![Last Update](https://github.com/user-attachments/assets/e1d05f21-2a01-4ecf-94f3-b7bdff4d44dd) &nbsp;: ![102025](https://github.com/user-attachments/assets/62cea8cc-bd7d-49bd-b920-5590016735c0)  
![License](https://github.com/user-attachments/assets/ff71a38b-8813-4a79-8774-09a2f3893b48) &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;: ![Freeware](https://github.com/user-attachments/assets/1fea2bbf-b296-4152-badd-e1cdae115c43)

</br>

Device Manager is a component of the Microsoft Windows operating system. It allows users to view and control the hardware attached to the computer. When a piece of hardware is not working, the offending hardware is highlighted for the user to deal with. The list of hardware can be sorted by various criteria.

</br>

![Device manager](https://github.com/user-attachments/assets/d7e36c78-cb97-471c-99fa-2661d216cc68)

</br>

For each device, users can:

* Supply device [drivers](https://en.wikipedia.org/wiki/Device_driver) in accordance with the Windows [Driver Model](https://en.wikipedia.org/wiki/Windows_Driver_Model) Enable or disable devices
* Tell Windows to ignore malfunctioning devices
* View other technical properties
* Device Manager was introduced with Windows 95 and later added to Windows 2000. On Windows 9x, Device Manager is part of the System applet in Control Panel. On Windows 2000 and all other Windows NT-based versions of Windows, it is a snap-in for Microsoft Management Console.

The executable program behind the Device Manager is  ```devmgmt.msc```

### Disabled device:
A disabled device has either been manually disabled by a user or by some way of error. In Windows 95 through XP, this is denoted by a red X. In Windows Vista and Windows 7, this was replaced by a grey downward pointing arrow in the lower right-hand corner of the device's icon.

### Hardware not working properly:
There are many reasons why hardware may not work properly. If Windows recognizes a problem with a device, it is denoted by a black exclamation point (!) on a yellow triangle in the lower right-hand corner of the device's icon.

### Hardware not recognized:
Hardware may not be recognized if it is not installed properly or not compatible with the system. This is denoted by a yellow question mark in place of the device's icon.

### Device manually selected:
A blue "i" on a white field in the lower right-hand corner of a Device's icon indicates that the Use automatic settings feature is not selected for the device and that the resource was manually selected. Note that this does not indicate a problem or disabled state.

### Device Types:
Windows separates devices and their drivers by class types. Extra hidden and disconnected devices can be exposed through the devmgr_show_nonpresent_devices flag.

* USB Class devices: Peripherals that connect exclusively through the [USB bus](https://en.wikipedia.org/wiki/USB).
  * Human Interface Devices: Devices used by the users to interface with the OS (eg. Touchpads, Pens, Mices and Keyboards)
  * Printer devices: Drivers that contain printer information. Hidden category since Windows Vista.
  * Imaging devices: Webcams and Scanners. A new webcam class driver was introduced in [Windows 10 v1709](https://en.wikipedia.org/wiki/Windows_10_version_history#Version_1709_(Fall_Creators_Update)).
  * Biometric devices: Devices that read biometric data using Windows Biometric Framework. (eg. IR Webcams, Fingerprint sensor)
* [PCI Class devices](https://en.wikipedia.org/wiki/PCI_configuration_space): Devices that connect to the PCI bus for high speed (eg. Graphics Card, Network card, Chipset)
  * System devices: Peripherals that tie to the system, chipset or have no set category (eg. [Intel Management Engine](https://en.wikipedia.org/wiki/Intel_Management_Engine), [Disk controller](https://en.wikipedia.org/wiki/Disk_controller), [ACPI events](https://en.wikipedia.org/wiki/ACPI))
  * Video and Audio Capture devices: Devices used to route audio/video streams (eg. Audio cards, TV Tuner cards, MIDI devices)
    * Audio inputs and outputs: Since Windows 8, audio ports have their own category.
* Non-PnP devices: Mostly software that need a driver installed to interface with the core kernel components. Hidden category since Windows 10.
* DCH devices: A new type of driver introduced in Windows 10 v1709 that can interface with [Universal Windows Platform ](https://en.wikipedia.org/wiki/Universal_Windows_Platform)apps or Hardware Support Apps (HSA). The goal was to * separate the core driver from the interfacing app. They are grouped under "Software components" (eg. Audio and Video drivers released post-2018)
* [Bluetooth Profiles](https://en.wikipedia.org/wiki/List_of_Bluetooth_profiles): Those are listed under "Bluetooth Virtual Devices" and aren't normally visible. Showing as "Bluetooth Peripheral Device" if no drivers are present.
* Other devices: This is not a category but a section where devices with missing drivers are grouped.
