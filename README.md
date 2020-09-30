![Image of ImageDownloader Logo](https://github.com/druzgeorge/ImageDownloader/blob/master/imagedownloaderlogo.png)
# ImageDownloader
### Python ImageDownloader: This program downloads images, possibly videos and music from sites when set stream=True pasre main(url, path-to-save) to file endline python3 main.py.
```python
...
def main(url, path):
    #get all images
    imgs = get_all_images(url)
    for img in imgs:
        download(img, path)
main('https://xmenmovies.fandom.com/wiki/Deadpool/Gallery', '/home')
```
 - Run code in terminal:
 ```bash
 python3 main.py
 ```
### Written by druzgeorge
