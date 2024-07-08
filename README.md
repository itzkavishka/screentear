### This script may help fix screen tearing issues on systems with an Intel CPU.
-- Make sure you have installed xf86-video-intel package.

   ```
sudo pacman -S xf86-video-intel
   ```

To install and run the script, follow these steps:

-- Clone this repository to your local machine.

-- Navigate to the cloned directory.

-- Make the script executable by running the following command:
   ```
chmod +x tear.sh
   ```
-- Run the script with elevated privileges by running the following command:
   ```
sudo ./tear.sh
   ```
<details>
<summary><b>OR</b></summary>
Just copy that 20-intel.conf file to /etc/X11/xorg.conf.d/
