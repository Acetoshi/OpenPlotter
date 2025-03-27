# UGS Setup

IMPORTANT : These instructions are for a debian-based linux OS like ubuntu, adapt to your needs.

1. **Download UGS** from their website: [UGS Download](https://winder.github.io/ugs_website/download/)

2. **Extract the file**, and then execute `bin/ugsplatform`.

3. **Create a shortcut**:
   - Navigate to `Tools` > `Create Shortcut`.

4. **Add user to dialout group**:  
   - Run the following command:  
     ```bash
     sudo usermod -aG dialout username
     ```
   - Replace `username` with the actual user's name.

5. **Download UGS settings from the repository**:  
   - Get the configuration files from the following links:  
     - [UGS Config](https://github.com/Acetoshi/OpenPlotter/blob/main/Software/UGS/ugs_config.zip)
     - [Macros](https://github.com/Acetoshi/OpenPlotter/blob/main/Software/UGS/macros)  

6. **Import UGS settings**:  
   - Navigate to **Tools > Options > Import** in UGS, then import the **UGS_Config.zip** file
   - Navigate to **Tools > Options > UGS > MACROS > Import** in UGS, then import the **macros** file
   - Make sure your joystick is activated if you want to control the machine with a gamepad

7. **Install support for Xbox 360 controller**:  
   - Run the following command:  
     ```bash
     sudo apt-get install xboxdrv
     ```

Reboot, and you're done !