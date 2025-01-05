# bartesian_pods
Bartesian pods with images and codes

## Images
Images are generated from photos where the barcode is generally in the center of the image. Those images are processed through the following command:

```
convert "Drink Name.jpg" -resize 512x640^ -gravity north -extent 512x640 "Drink Name.jpg"
```

## Codes
Codes are in `pods_data.csv` file formatted as:
```
code,Drink Name
```

The drink name in the csv file should correspond to the `jpg` file name in the `images` directory.

