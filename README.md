# BackrollFiles
Drop these files in your Unity project to access Backroll without importing it as a package

In your package Manifest.json make sure to add:

    "com.discord.game-sdk": "3.1.0",
    "com.facepunch.steamworks": "2.2.1"
    
And:

  "scopedRegistries": [
    {
      "name": "Hourai Teahouse",
      "url": "https://upm.houraiteahouse.net",
      "scopes": [
        "com.houraiteahouse",
        "com.facepunch",
        "com.discord"
      ]
    }
  ]
  

and you should be good!
