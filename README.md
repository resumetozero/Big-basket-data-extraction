# Big-basket-data-extraction
Raw file:<br>
while scrapping if any value is missing then that product is skipped<br>
all combos are there<br>
if unit is having + or x in there unit than that product is either combo or instead of weight/volume, the dimension of product are given<br>
some product have different units so please be aware of it (sets, pack, g/bag etc)<br>

TLC file:<br>
if any duplicate are there then it is removed<br>
all products are unique (based on id and EAN )<br>

anomaly in data:<br>
som have unit in sentence such as "g pack of" there mag will also be affected by it.<br>
