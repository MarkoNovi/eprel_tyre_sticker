# eprel_tyre_sticker
google colab notebook that gets svg files from eprel links stored in "eprel_links.xlsx" file that you should upload, and converts svg files to jpeg format.

# why google colab notebook?
beacuse installling cairosvg dependencies on windows was pain in the butt.

# how to use it?
* on your PC create "eprel_links.xlsx" file, place all product codes in column names "TyreQRCode". (you can use full link or just the code like on the image)<br> 
![image](https://github.com/MarkoNovi/eprel_tyre_sticker/assets/76423352/68dce67f-e1c1-40ea-8b79-68fb6da8523d)
* here you click on "eprel_tyre_sticker.ipynb" and when it opens click on "Open in colab"<br>
![image](https://github.com/MarkoNovi/eprel_tyre_sticker/assets/76423352/9444e322-4420-4f97-abdf-b7bd54cdf23e)<br>
![image](https://github.com/MarkoNovi/eprel_tyre_sticker/assets/76423352/3a5f191f-8ed3-409b-b803-22644ced0fdb)
* drag & drop xlsx file and upload to google colab<br>
![image](https://github.com/MarkoNovi/eprel_tyre_sticker/assets/76423352/be8b411b-50ae-4ab3-a806-3f0d807dde9e)
* run the first cell to install dependencies<br>
![image](https://github.com/MarkoNovi/eprel_tyre_sticker/assets/76423352/b7fbb7d5-6105-4741-9056-3ab0c4c7ffe5)
* run script<br>
![image](https://github.com/MarkoNovi/eprel_tyre_sticker/assets/76423352/9d7e03ab-03a6-41c1-987d-00bc23e888cd)
* check "done.xlsx" file for any errors
* download "jpeg.zip" file from "data/" directory to your PC
* run !rm -r data/ to delete all files in script directory<br>
![image](https://github.com/MarkoNovi/eprel_tyre_sticker/assets/76423352/335f8565-b7fa-46b7-ab11-0f7a71a821c1)
