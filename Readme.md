<link href="style.css" rel="stylesheet"></link>

#### Video tests

`LC_ALL=C datamash -R 2 mean 1 mean 2 mean 3 < infile.txt`

* RaspiOS 12

    ```
                 CPU     GPU     Temp
    vlc       :  6.91    1.97   39.37
    ffplay    : 43.28   14.70   47.03
    mpv       : 43.42   17.56   46.42
    ```

* RaspiOS 13
    
    fullscreen :
    
    ```
                 CPU     GPU     Temp
    vlc       :  6.09    0.00   37.01
    ffplay    : 41.26   14.54   43.92
    mpv       : 48.92   38.32   44.03
    ```
    
    window :
    
    ```
                 CPU     GPU     Temp
    mpv       : 55.20	48.65	43.96
    ```

