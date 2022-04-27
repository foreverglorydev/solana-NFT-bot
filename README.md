# Solana Mint bot

---

This bot will help you mint all the Magic Eden NFT's projects, This bot of does not guarantee a successful mint but increases chances as well as gives you the possibility to mint bypass the minting limit !

Easy setup which uses ChromeDriver to open up a new chrome instance and mint the nft you are looking for quicker than a human. **This bot does not guarantee you will get your NFT**, this bot simply goes faster than humans to mint and automates everything since you do not have to click yourself.

You can **launch multiple instances of the bot to bypass minting limit / wallet**

You can support me with some SOL : 5sC1ZeD21wbQyvL5wc7yL2wFntNdQWyKHg3AZaeXnkh7

---

### Support

-   [x] Window
-   [x] Mac (Intel + m1)
-   [x] Linux (Not verified)

-   [x] MagicEden.io
-   [x] MonkeLabs.io

---

-   This bot uses ChromeDriver so on mac there is a possiblity that you will have to **allow the software to run in your privacy settings**. Check mac folder for more info.

-   The chrome window will appear **WITHOUT** loading the images, this is to ensure the fastest loading.

---

## Tutorial

1. Clone the repository / Download zip file

    `git clone https://github.com/JacobSterns/Solana-mint.git`

    OR

    [Download Zip File](https://github.com/JacobSterns/Solana-mint/archive/refs/heads/main.zip)
    

2. Be sure you have installed Python correctly, [here is a link to download](https://www.python.org/downloads/)

2. Open command prompt

3. Install all python module

   `pip install selenium requests webdriver-manager`
   

4. Replace Phantom Passphrase and password in `config.json`

    `launchpadLink` --> Launchpad link on magic eden

    `seedPhrase` --> your phantom wallet passphrase (Careful do not share this key)

    `password` --> A password for your wallet

5. Open CMD and go to directory

    `cd /path/to/directory/Solana-mint`

6. Run the python file

    windows : `python main.py`

    mac : `python3 main.py`
