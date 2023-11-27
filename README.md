# eprel_tyre_sticker
google colab notebook that gets svg files from eprel links stored in "eprel_links.xlsx" file that you should upload, and converts svg files to jpeg format.

# why google colab notebook?
beacuse installling cairosvg dependencies on windows was pain in the butt.

# how to use it?
* on your PC create "eprel_links.xlsx" file, place all product codes in column names "TyreQRCode"<br> 
![image](https://github.com/MarkoNovi/eprel_tyre_sticker/assets/76423352/68dce67f-e1c1-40ea-8b79-68fb6da8523d)
* drag & drop xlsx file and upload to google colab<br>
![image](https://github.com/MarkoNovi/eprel_tyre_sticker/assets/76423352/a3951bd3-8061-46bc-9475-a1cfbd22ffa0)
* run the first cell to install cairosvg
* run script
* download "jpeg.zip" file from "data/" directory to your PC
