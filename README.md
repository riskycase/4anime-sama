# 4anime-sama
A batch download link generator for 4anime.to.


## Purpose

* The python script can generate download links for anime hosted on [4anime](https://4anime.to/).
* The generated links can be copied to a text file and batch dowloaded using a download manager. (IDM, ADM, etc)

## Instructions
* Navigate to [4anime.to](https://4anime.to/).
* Search/Select the anime you want to download (e.g. [Naruto](https://4anime.to/anime/naruto)).
* Click on the First Episode of the anime.
![](https://github.com/hyPnOtICDo0g/4anime-sama/blob/master/firstep.png?raw=true)

* Right click & Copy the download link located beneath the player.
![](https://github.com/hyPnOtICDo0g/4anime-sama/blob/master/linkcopy.png?raw=true)
* Run the script in the repo folder & follow the instructions. (Check **Usage** for more.)

## Usage

* Clone the [repo](https://github.com/hyPnOtICDo0g/4anime-sama) to your computer.
```
    git clone https://github.com/hyPnOtICDo0g/4anime-sama.git
```  
* Navigate to the repo folder & look for the python script.

    ### On Linux
    * Open a Terminal Window in the repo folder & excecute the following command.
    ```
        python 4anime.py
    ```
    ### On Windows
    
    
    
    ### Alternative (if you aren't familiar with scripts)
    * Navigate to [Google Colab](https://colab.research.google.com/drive/1q56pQDS7m4LmQESZju9hy8qOqu6C8-c2).
    * Click on **Open in Playground** located at the top-left corner.
    ![](https://github.com/hyPnOtICDo0g/4anime-sama/blob/master/collab.png?raw=true)
    * Click on the run button & you'll be prompted to Sign-in to your Google account.
    ![](https://github.com/hyPnOtICDo0g/4anime-sama/blob/master/run.png?raw=true)
    * After Signing in, click on the run button & you'll be prompted with a warning.
    * Click on **Run Anyway** & wait for the Jupyter Notebook to process.
    * Later, Scroll down and follow the instructions.
    
## Downloading
   * Copy the generated links (output) into a text file & save it.
   * They can be batch downloaded using a Download Manager.
   * Note: After feeding the Download Manager with the text file, Queue your Downloads to 2-3 videos or it may result in a 503 error, as the website doesn't allow a single ip to download multiple files at one go.
    
        #### Download Managers:
        * Internet Download Manager(IDM)/Xtreme Download Manager(XDM): For Windows/MAC
        * uGet: For Linux
        * ADM: Android
