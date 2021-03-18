# Fb auto post

fbautopost is a Python file for automatize post in the facebook groups.

## Configuration

Use the variable [account]()  to put email of the facebook.

Use the variable [passwordCredential]()  to put password of the facebook.

Use the variable [groupPotList]() to indicate the groups to post

Use the variable [imageFolderPath]()   to select file directory where is the images that upload to post

Use the variable [nameImagesToPost]()  to select images to upload in the folder

 
```

## Configuration

```python
    account = "*****"
    passwordCredential = "*****"
    descripcionPost = "SAMPLE"\
        " SAMPLE LINE "\
        " SAMPLE LINE "\
        " SAMPLE LINE "    
    titlePost ="SAMPLE TITLE"
    pricePost ="250"
    groupPostList = [
        "urlgroupPost",
    ]    
    imageFolderPath = 'C:/Users/images'
    nameImagesToPost = '"2.png" "1.png"'
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)