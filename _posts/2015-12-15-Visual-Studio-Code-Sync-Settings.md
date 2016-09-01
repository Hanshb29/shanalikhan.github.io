---
layout: post
title: Visual Studio Code Settings Synchronization
description : synchronize your visual studio code settings across multiple machines. Whether your editor settings are changed in office you can set synchronize that settings in home editor also.
---

I have developed a small utility in order to synchronize your visual studio code settings across multiple machines. Whether your editor settings are changed in office you can set synchronize that settings in home editor also.

<blackquote>
<p>
<strong>MARKETPLACE URL : 
<a href="https://marketplace.visualstudio.com/items/Shan.code-settings-sync">Visual Studio Code Settings Sync</a></strong>
</p>
</blackquote>

> To Install : type "ext install code-settings-sync"

<strong> Type Sync in command to get all the commands </strong>


**Type Sync in command Palette in order to view all commands.**

### Key Features
```
1. Use your github account token and GIST.
2. Easy to Upload and Download on one click.
3. Upload Key : Shift + Alt + U
4. Download Key : Shift + Alt + D
5. Use Other User's Public GIST to completely sync your settings with them.
6. Show a summary page at the end with details 
```  



## It Syncs
```
1. Settings File
2. Keybinding File
3. Launch File
4. Snippets Folder
5. VSCode Extensions
```

	
## Steps To Get the Github Key.

This extension required your GitHub Account Personal Access Token. You can create one simple by looking into the following pictures.

#### Goto Settings / Personal Access Tokens / Generate New Token

![Goto Settings / Personal Access Tokens](/img/github1.PNG)

#### Select Scopes

![Select Scopes](/img/github2.PNG)

#### Get Unique Key

![Get Unique Key](/img/github3.PNG)

> You need to save this key for this extension for future use, and dont share this key with anyone as it will get your data without needing to logg in.

## Upload Your Settings For the first time


#### Type "Sync : Upload" in command

> Shortcut key is : Shift + Alt + u

It will open github account page. Enter the github account in the window and click enter.

![github account access token](/img/upload1.png)

#### Upload your settings automatically and give you GIST ID.

Copy this Gist ID in order to download the settings in other machines.

![uploaded automatically](/img/upload2.png)


## Download your Settings

#### Type "Sync : Download" in command

> Shortcut Key : Shift + Alt + d

Enter the github account in the window and click enter.

![github account access token](/img/upload1.png)

#### Enter Your GIST ID.

you need to enter your Gist ID in order to get the all files

![Enter Your GIST ID](/img/download2.png)

#### Settings Downloaded.

You are Done ! All your files are downloaded and it will start downloading your extensions in the background and will let you know to restart the VSCode in order to use the installed extensions.

![Enter Your GIST ID](/img/download3.png)


## Reset Token / GIST Settings

> Type ">Sync" In Command Palette and select Reset Token and GIST Settings

## Toggle Auto Download

Auto Download is **enabled by default**. It will sync all the setting by default when the editor starts.
Please make sure you have valid github Token and GIST available to make it work properly.

Select Command **"Sync : Advance Options > Toggle Auto-Download On Startup"** command to Turn ON / OFF the auto download.

## Toggle Summary

Summary is **enabled by default** which shows all the files and extensions that are added or deleted in a single page.
You may turn it off in order to make a upload and download process clean and quiet.  

Select Command **"Sync : Advance Options > Toggle Summary Page On Upload / Download"** command to Turn ON / OFF the auto download.

## Create Public GIST To Share

By default, it creates secret GIST so only you can see it but if you want to share your GIST with other users, you can set it to public.
You can't change the exiting GIST type from secret to public so it will reset the GIST ID so you can create new GIST with all the existing editor settings.

Select Command **"Sync : Advance Options > Public / Private GIST Mode & Reset GIST"**

## Fetch Other User's Settings

You may give the GIST ID to other users , your friends or employees so they download each of the extensions or settings you upload but they cant edit your GIST or upload anything on your GIST.

Select Command **"Sync : Advance Options > Fetch Other User's Settings"**


> To Install : type "ext install code-settings-sync"


<blackquote>
<p>
<strong>MARKETPLACE URL :
<a href="https://marketplace.visualstudio.com/items/Shan.code-settings-sync">Visual Studio Code Settings Sync</a></strong>
</p>
</blackquote>
