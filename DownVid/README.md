Download videos from [a plethora of video sources](https://rg3.github.io/youtube-dl/supportedsites.html), even when embedded in other pages.

Copy a link to your clipboard, run `dv`, and you’re done. The workflow will show you a notification when it starts downloading and another when finished.

If you have [WatchList](https://github.com/vitorgalvao/alfred-workflows/tree/master/WatchList) you’ll see an option to automatically add the downloaded video to your watchlist.

![](https://i.imgur.com/Q33FNRw.png)
 
Run with the ⌘ modifier, and the full playlist the video is part of will be downloaded.

To see the download progress, run `dvp`. It will auto-refresh the progress. Actioning it with the ⌘ modifier will restart the current download (adding it to the back of the queue), while actioning with ⌃ will abort the current download.

![](https://i.imgur.com/92TfpDM.png)
 
You can also run `:downvidservices` to install (or later remove, running the same command) DownVid actions to macOS Services. What this means is wherever you find a URL, you’ll be able to right click it and start the download right from the context menu.

![](https://i.imgur.com/NWHIWcY.png)

The two Workflow Environment Variables represent the directories (relative to your home) where videos will download to.
