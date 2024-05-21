# eprel_tyre_sticker
Google Colab notebook that gets SVG files from eprel links stored in the "eprel_links.xlsx" file that you should upload, and converts SVG files to jpeg format.

# why google colab notebook?
because installing cairosvg dependencies on Windows was pain in the butt.
# how to use it?
* on your PC create "eprel_links.xlsx" file, place all codes in column "Tokić šifra", place all product links in column names "TyreQRCode". (you can use full link or just the code part)<br>
![image](https://github.com/MarkoNovi/eprel_tyre_sticker/assets/76423352/8a6ba6f0-8152-4846-8b8d-898ad065315d)
* right click on this "Open in Colab" button and select "Open link in new tab"<br>
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/MarkoNovi/eprel_tyre_sticker/blob/main/eprel_tyre_stickers.ipynb)
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
