[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/ayushma-gupta04/MirrorX.git)

# - What Modified In My Fork.
1. Addded Mega Download Support For Complex And Big Size(100-200+) Folders.Read The Msg About Mega Download Below.
2. Added Support For UpToBox Links (Premium Account Needed).
3. Added Ability To Do Speed Test Of The Host. (/speedtest Command).
4. Added Support For Indian Streaming Sites Like Hotstar, Zee5, Mx Player, Voot, And Many Others........
5. Added Custom User Agent ,Peer Agent..Transmission For Now.

# Important - About Mega Downloads.
1. There Is No Max Size Limit For Mega Folder Or File
2. If A Folder Fails To Download , Import It Into Your Mega Account And Create A Fresh Sharing Link. Weird But Works.
3. If Mega Download Is Running, Don't Put Torrents Or Direct Link Mirror With It , Crashes Sometime.
4. We Recommand One Download At Time , If You Have Multicore Instance Or Vps You Can Try Multiple Download At A Time.

# [A Guide On How To Customise Bot Further for Personal Use.](https://github.com/iamLiquidX/MirrorX/blob/master/modificaton.md#a-guide-on-how-to-customise-bot-further-for-personal-use)
### Added A Small Guide Which Has The Following :-
1. [Customising Bot /start Message](https://github.com/iamLiquidX/MirrorX/blob/master/modificaton.md#Customising-Bot-start-Message)
2. [Changing Bot Commands](https://github.com/iamLiquidX/MirrorX/blob/master/modificaton.md#Changing-Bot-Commands)
3. [Changing Max Allowed Downloads & Set Auto Cancel Time If No Seeders Available](https://github.com/iamLiquidX/MirrorX/blob/master/modificaton.md#Changing-Max-Allowed-Downloads-and-Set-Auto-Cancel-Time-If-No-Seeders-Available)
4. [Customising Bot Message When Bot Auto Cancels the Torrent Due to No Seeders are Available](https://github.com/iamLiquidX/MirrorX/blob/master/modificaton.md#Customising-Bot-Message-When-Bot-Auto-Cancels-the-Torrent-Due-to-No-Seeders-are-Available)
5. [Customising Bot Stats Message](https://github.com/iamLiquidX/MirrorX/blob/master/modificaton.md#Customising-Bot-Stats-Message)
6. [Customising Mirror Status](https://github.com/iamLiquidX/MirrorX/blob/master/modificaton.md#Customising-Mirror-Status)
7. [Customising Mirror Progress Bar](https://github.com/iamLiquidX/MirrorX/blob/master/modificaton.md#Customising-Mirror-Progress-Bar)
8. [Customising Bot status Message](https://github.com/iamLiquidX/MirrorX/blob/master/modificaton.md#Customising-Bot-status-Message)
9. [Customising Bot After Download Complete Message](https://github.com/iamLiquidX/MirrorX/blob/master/modificaton.md#Customising-Bot-After-Download-Complete-Message)

# Another Important Thing, Always Give Credit. These People/Devs Have Worked Really Hard Without Incentive To Make These Awesome Bots. Give Them Respect.

All The Credits To Real Owners Who Made And Modified This Amazing Bot. Sir lzzy12,Sir ZeroCool Aka Jaskaran ,Sir Magneto And Some Unkown Users Of Git. #Check Credits Below For Full Credit Details.

I Am Just Doing The Modification For Personal Use.



# Important - Read these points first
- Original repo is https://github.com/lzzy12/python-aria-mirror-bot
- I have collected some cool features from various repositories and merged them in one.
- So, credits goes to original repo holder, not to me. I have just collected them.
- This (or any custom) repo is not supported in official bot support group.
- So if you have any issue then check first that issue is in official repo or not, You are only allowed to report that issue in bot support group if that issue is also present in official repo.

## Features Coming soon....
- ~Custom Filename~ Added 
```
Only for url, telegram files and ytdl.
Not for mega links and magnet/torrents
```
- Rename Drive files

Let's have some chit chat here - [@Magneto_chit_chat](https://t.me/magneto_chit_chat).
Note :- it is not a Bot Support group. It's only for discussing rubbish things bcoz i want your help to learn coding 😜🤪.


## Credits :-
- First of all, full credit goes to [Shivam Jha aka lzzy12](https://github.com/lzzy12) and [JaskaranSM aka Zero Cool](https://github.com/jaskaranSM) They build up this bot from scratch.
- Then a huge thanks to [Sreeraj V R](https://github.com/SVR666) You can checkout his [repo here](https://github.com/SVR666/LoaderX-Bot)
- Features added from [Sreeraj V R's](https://github.com/SVR666) repo -
```
1. Added Inline Buttons
2. Added /del command to delete files from drive
3. /list module will post search result on telegra.ph
```
- Special thanks to [archie](https://github.com/archie9211) for very much useful feature **Unzipmirror**
- Features added from [archie's](https://github.com/archie9211) repo
```
1. unzipmirror
2. Update tracker list dynamically
3. Fix SSL handsake error
```


# What is this repo about?
This is a telegram bot writen in python for mirroring files on the internet to our beloved Google Drive.

# Inspiration 
This project is heavily inspired from @out386 's telegram bot which is written in JS.

# Features supported:
- Mirroring direct download links to google drive
- Mirroring Mega.nz links to google drive (In development stage)
- Mirror Telegram files to google drive
- Mirror all youtube-dl supported links
- Custom filename support in direct link, telegram files, YT-DL links
- Extract these filetypes and uploads to google drive
> ZIP, RAR, TAR, 7z, ISO, WIM, CAB, GZIP, BZIP2, 
> APM, ARJ, CHM, CPIO, CramFS, DEB, DMG, FAT, 
> HFS, LZH, LZMA, LZMA2, MBR, MSI, MSLZ, NSIS, 
> NTFS, RPM, SquashFS, UDF, VHD, XAR, Z.
- Copy files from someone's drive to your drive (using Autorclone)
- Service account support in cloning and uploading
- Download progress
- Upload progress
- Download/upload speeds and ETAs
- Docker support
- Uploading To Team Drives.
- Index Link support
- Shortener support
- Extract password protected files (It's not hack, you have to enter password for extracting. LOL)

- For extracting password protected files and using custom filename see these examples :-
> https://telegra.ph/Magneto-Python-Aria---Custom-Filename-Examples-01-20

## Bot commands to be set in botfather

```
mirror - Start Mirroring
tarmirror - Upload tar (zipped) file
unzipmirror - Extract files
clone - copy folder to drive
watch - mirror YT-DL support link
tarwatch - mirror youtube playlist link as tar
cancel - Cancel a task
cancelall - Cancel all tasks
del - Delete file from Drive
list - [query] searches files in G-Drive
status - Get Mirror Status message
stats - Bot Usage Stats
help - Get Detailed Help
log - Bot Log [owner only]
```

# How to deploy?
Deploying is pretty much straight forward and is divided into several steps as follows:
## Installing requirements

- Clone this repo:
```
git clone https://github.com/iamLiquidX/MirrorX
cd MirrorX
```

- Install requirements
For Debian based distros
```
sudo apt install python3
sudo snap install docker 
```
- For Arch and it's derivatives:
```
sudo pacman -S docker python
```

## Setting up config file
```
cp config_sample.env config.env
```
- Remove the first line saying:
```
_____REMOVE_THIS_LINE_____=True
```
Fill up rest of the fields. Meaning of each fields are discussed below:
- **BOT_TOKEN** : The telegram bot token that you get from @BotFather
- **GDRIVE_FOLDER_ID** : This is the folder ID of the Google Drive Folder to which you want to upload all the mirrors.
- **DOWNLOAD_DIR** : The path to the local folder where the downloads should be downloaded to
- **DOWNLOAD_STATUS_UPDATE_INTERVAL** : A short interval of time in seconds after which the Mirror progress message is updated. (I recommend to keep it 5 seconds at least)  
- **OWNER_ID** : The Telegram user ID (not username) of the owner of the bot
- **AUTO_DELETE_MESSAGE_DURATION** : Interval of time (in seconds), after which the bot deletes it's message (and command message) which is expected to be viewed instantly. Note: Set to -1 to never automatically delete messages
- **IS_TEAM_DRIVE** : (Optional field) Set to "True" if GDRIVE_FOLDER_ID is from a Team Drive else False or Leave it empty.
- **AUTHORIZED_CHATS** : (Optional field) Write all the User and Group ID's you want to authorize Bot Separated by Space  (Example : "123456789 987654321 -1001234567890")  Bot Can Distinguish Between User ID and Group Id & Allow only users to Restart the bot while Group IDs can't Restart the Bot.
- **USE_SERVICE_ACCOUNTS**: (Optional field) (Leave empty if unsure) Whether to use service accounts or not. For this to work see  "Using service accounts" section below.
- **INDEX_URL** : (Optional field) Refer to https://github.com/maple3142/GDIndex/ The URL should not have any trailing '/'
- **API_KEY** : This is to authenticate to your telegram account for downloading Telegram files. You can get this from https://my.telegram.org DO NOT put this in quotes.
- **API_HASH** : This is to authenticate to your telegram account for downloading Telegram files. You can get this from https://my.telegram.org
- **UPTOBOX_TOKEN** : This is to download files using premium account of UpToBox. You can get this from https://uptobox.com/my_account
- **MEGA_API_KEY**: Mega.nz api key to mirror mega.nz links. Get it from [Mega SDK Page](https://mega.nz/sdk)
- **MEGA_EMAIL_ID**: Your email id you used to sign up on mega.nz for using premium accounts (Leave th)
- **MEGA_PASSWORD**: Your password for your mega.nz account 
- **STOP_DUPLICATE_MIRROR**: (Optional field) (Leave empty if unsure) if this field is set to `True` , bot will check file in drive, if it is present in drive, downloading will ne stopped. (Note - File will be checked using filename, not using filehash, so this feature is not perfect yet)
- **BLOCK_MEGA_LINKS**: (Optional field) If you want to remove mega.nz mirror support (bcoz it's too much buggy and unstable), set it to `True`.
- **SHORTENER**: (Optional field) if you want to use shortener in Gdrive and index link, fill shotener url here. Examples :-

> exe.io

> gplinks.in

> shrinkme.io

> urlshortx.com

> shortzon.com

Note :- Above are the supported url shorteners. Except these only some url shorteners are supported. If you want to use any other url shortener then first ask me that shortener is supported or not.
- **SHORTENER_API**: Fill your shortener api key if you are using shortener.

Note: You can limit maximum concurrent downloads by changing the value of MAX_CONCURRENT_DOWNLOADS in aria.sh. By default, it's set to 4
 
## Getting Google OAuth API credential file

- Visit the [Google Cloud Console](https://console.developers.google.com/apis/credentials)
- Go to the OAuth Consent tab, fill it, and save.
- Go to the Credentials tab and click Create Credentials -> OAuth Client ID
- Choose Desktop and Create.
- Use the download button to download your credentials.
- Move that file to the root of mirror-bot, and rename it to credentials.json
- Visit [Google API page](https://console.developers.google.com/apis/library)
- Search for Drive and enable it if it is disabled
- Finally, run the script to generate token file (token.pickle) for Google Drive:
```
pip install google-api-python-client google-auth-httplib2 google-auth-oauthlib
python3 generate_drive_token.py
```
## Deploying

- Start docker daemon (skip if already running):
```
sudo dockerd
```
- Build Docker image:
```
sudo docker build . -t mirrorx
```
- Run the image:
```
sudo docker run mirrorx
```

# Using service accounts for uploading to avoid user rate limit
For Service Account to work, you must set USE_SERVICE_ACCOUNTS="True" in config file or environment variables
Many thanks to [AutoRClone](https://github.com/xyou365/AutoRclone) for the scripts
## Generating service accounts
Step 1. Generate service accounts [What is service account](https://cloud.google.com/iam/docs/service-accounts)
---------------------------------
Let us create only the service accounts that we need. 
**Warning:** abuse of this feature is not the aim of autorclone and we do **NOT** recommend that you make a lot of projects, just one project and 100 sa allow you plenty of use, its also possible that overabuse might get your projects banned by google. 

```
Note: 1 service account can copy around 750gb a day, 1 project makes 100 service accounts so thats 75tb a day, for most users this should easily suffice. 
```

`python3 gen_sa_accounts.py --quick-setup 1 --new-only`

A folder named accounts will be created which will contain keys for the service accounts created

NOTE: If you have created SAs in past from this script, you can also just re download the keys by running:
```
python3 gen_sa_accounts.py --download-keys project_id
```

### Add all the service accounts to the Team Drive or folder
- Run:
```
python3 add_to_team_drive.py -d SharedTeamDriveSrcID
```

# Youtube-dl authentication using .netrc file
For using your premium accounts in youtube-dl, edit the netrc file (in the root directory of this repository) according to following format:
```
machine host login username password my_youtube_password
```
where host is the name of extractor (eg. youtube, twitch). Multiple accounts of different hosts can be added each separated by a new line
