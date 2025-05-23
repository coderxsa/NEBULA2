# NEBULA termux

## Requirements

- ✅ Termux installed on your Android device.
- ✅ Node.js and Git installed using Termux.
- ✅ Samsung Galaxy A20 with Android 11, or any Samsung device that's newer or better.
- ✅ You must be able to run this command successfully:
    ```
    pkg update -y && pkg upgrade -y
    ```
 ⚠️ If this command fails, you cannot continue.


## Installation
<details>
  <summary><strong>🚀 Termux - Installation Guide</strong></summary>

### Step 1: Install Dependencies

1. Update and upgrade your system packages to ensure everything is up to date and storage:
    ```
    termux-setup-storage
    ```
    ```
    pkg update -y && pkg upgrade -y
    ```

3. Install Node.js (JavaScript runtime) and Git (version control system):
    ```
    pkg install -y nodejs git
    ```

4. Clone the GitHub repository into your local machine:
    ```
    git clone https://github.com/coderxsa/nebula2.git
    ```

5. Change into the directory of the cloned repository:
    ```
    cd nebula2
    ```

6. Edit `bot.js`:
    ```
    nano bot.js
    ```
    To save the edit u need to tap: || ctrl || x || y || enter

7. Install the necessary dependencies for the project defined in `package.json`:
    ```
    npm install
    ```

8. Run the Node.js application, passing a specific phone number you want to use and get the login code:
    ```
    node index.js
    ```

9. To remove stat file 
    ```
    cd nebula2
    ```
    ```
    rm -rf state
    ```
    ```
    node index.js
    ```

</details>

<details>
  <summary><strong>Relink Bot</strong></summary>

### Step 2: Relink Bot (If Necessary)

- If Termux disconnects, you can simply relink the bot by running the following commands:
    ```
    cd nebula2
    node index.js
    ```

- If you removed the linked device, you need to follow **Step 1** again and reinstall the bot. To clear data on Termux:
    - Go to Android settings > Apps > Termux > Clear Data

- Reinstall the bot:
    ```
    git clone https://github.com/coderxsa/nebula2.git
    cd nebula2
    npm install
    node index.js
    ```
</details>

## 🤩 Support

SUPPORT: <a href="https://pay.yoco.com/ShopZa"><img alt="Yoco" src="https://a.storyblok.com/f/111633/600x120/efd2e37265/payment-strip.svg"/></a>
- Support me with small Donation (Click Above Images)

- Star ⭐ the repo if you like nebula2.

## CREDITS 

## `Main Dev` 
<a href="https://github.com/coderxsa"><img src="https://avatars.githubusercontent.com/u/149763717?v=4" width="250" height="250" alt="coderxsa"/></a>
  
`nebula2 - By coderxsa`



<h2 align="center">  Reminder
</h2>
   
## 
- This bot is not made by `WhatsApp Inc.` So misusing the bot might `ban` your `WhatsApp account!`(Though your WhatsApp account can be unbanned only 3 times.)
- I am not responsible for banning your account.
- Use at your own risk by keeping this warning in mind.

<h2 align="center">  NOTICE
</h2>

## 
- Not For Sale
- If A plugin's code is obfuscated , You don't have permission to edit it in any form 
- Don't Forget to Give Credits If you are using or Reuploading My Plugins/files
- Have A Good Day Ahead
