# gradle-mirror
This script download all version  of Gradle(http://www.gradle.org/downloads)


# How-to Use
* Clone this repository

```
$ git clone https://github.com/tobiashochguertel/gradle-mirror.git
```

* Change the download folder directory

```  
DOWNLOAD_FOLDER=/home/`whoami`/gradle
```

* Run 

```
./gradle-mirror
```

You might want to put the script on crontab, run the script daily, so you will always get the latest version of gradle on your local server. 
