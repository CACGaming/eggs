
# Minecraft Console Client

Minecraft Console Client is a lightweight app that will make your life easier! Able to connect to any minecraft server, both offline and online mode, it enables you to send commands and receive text messages in a fast and easy way without having to open the main Minecraft game.

## Config

**WARNING**  
The password is stored in plaintext, if you add the password to the MinecraftClient.ini file anyone with access to your server can get your Minecraft account password!

Modify the the login, password, and server settings in MinecraftClient.ini to have it login automatically on server start.

    [Main]
    # General settings
    # Leave blank to prompt user on startup
    # Use "-" as password for offline mode
    login=                             # Minecraft account email
    password=                          # Minecraft account password
    serverip=                          # IP for the client to connect to on startup
    type=microsoft                     # Account type. mojang or microsoft. Also affects interactive login in console.
    method=mcc                         # Microsoft Account sign-in method. mcc OR browser
