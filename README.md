# Big-basket-data-extraction
with this code you can scrap whole valid dataset of products available on website within minutes<br>

**Raw file:**
   - while scrapping if any value is missing then that product is skipped
   - all combos are there
   - if unit is having + or x in there unit than that product is either combo or instead of weight/volume, the dimension of product are given
   - some product have different units so please be aware of it (sets, pack, g/bag etc)

**TLC file:**
   - if any duplicate are there then it is removed
   - all products are unique (based on id and EAN )

**Anomaly in data:**
   - some have unit in sentence such as "g pack of" there magnitude will also be affected by it.<br>

**Requirements:**
   - goood internet connection otherwise it will cause less number of pages scrapped<br>
   - you may change the number of thread from 2 to more. But it depends on your internet speed<br>
   - (while doing this project my internet speed was 500kbps)<br>

TLC: TLC level category<br>
MLC: Medium level category<br>
LLC: Low level category<br>

*Make the required changes in code as you are scrappig different category*
1. change the category names in:<br>
   a) url<br>
   b) while saving scrapped data in csv file (raw file) <br>
    - change mode if w and a accordingly
    - add header when required
   c) while saving csv file category wise(mlc,llc)<br>

2. if scrapping stops at mid way, or to check if all pages are scraped or not, change the page number in code from 1, to the page number where response sending failed.<br>
