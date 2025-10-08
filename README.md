## Here is a quick guide on how to setup Fastfetch

### 1. Install fastfetch using the command below:
   - i. ```sudo dnf install fastfetch```

### 2. Add fastfetch to .zshrc by running the command below and writting just "fastfetch" without qoutes:
   - i. ```nano .zshrc```

### 3. Check if you have a config.jsnoc file in your fastfetch folder if not run the command below:
   - i. ```fastfetch --gen-config```

### 4. Open the config.jsonc file in with you readily available text-editor like nano and paste the following:
   - i. ``nano ~/.config/fastfetch/config.jsonc```
   - ii. Paste the code (refer to config.jsonc ) in this repo.

### After this you should restart your terminal and everything should be fine except the logo since it might not find my own logo in you file path.

## 5. Add a personal logo. You can look of an ascii file, usually its just a .txt file. Run the following command to create a folder in fastfetch and save you logo there.
  - i. ```cd ~/.config/fastfetch```  
  - ii. ```mkdir images```

### 6. Open your config.jsonc file again using your text-editor and make sure your file path and name matches the setup you did in STP 5.
   - i. ```nano ~/.config/fastfetch/config.jsonc```


### After all this is done  you will be good to go. Please note that I did all this in Fedora Workstation 42  | Gnome 48.5 | Wayland.
### Running zsh in a gnome terminal. 

### Written by Dave Budah
#### https://apexbytes.dev
#### https//:www.linkedin.com/in/dave-budah
#### https://reddit.com/user/cyberzues/