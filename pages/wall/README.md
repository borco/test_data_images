# Testing images

Downloaded from https://pixabay.com/

```sh
# using fish shell

set index 1; \
    for x in *.jpg; \
    set target (string pad -w4 -c0 $index); \
    echo \| $target.jpg \| $x \| ; \
    mv $x $target.jpg
    set index (math $index + 1) ; \
    end
```

| Current name | Pixabay name |
|---|---|
| 0001.jpg | alberta-2297204.jpg |
| 0002.jpg | ama-dablam-2064522.jpg |
| 0003.jpg | amalfi-2241861.jpg |
| 0004.jpg | autumn-2183489.jpg |
| 0005.jpg | badlands-1110558.jpg |
| 0006.jpg | birch-1782320.jpg |
| 0007.jpg | boat-4899802.jpg |
| 0008.jpg | camel-1839616.jpg |
| 0009.jpg | canyon-1740973.jpg |
| 0010.jpg | castelmezzano-1979546.jpg |
| 0011.jpg | cave-1835823.jpg |
| 0012.jpg | cliff-1206473.jpg |
| 0013.jpg | cliff-1822484.jpg |
| 0014.jpg | dresden-5987976.jpg |
| 0015.jpg | etretat-4538160.jpg |
| 0016.jpg | fog-693350.jpg |
| 0017.jpg | forest-438432.jpg |
| 0018.jpg | forest-6656672.jpg |
| 0019.jpg | grass-3445804.jpg |
| 0020.jpg | grove-of-trees-867931.jpg |
| 0021.jpg | hallstatt-3609863.jpg |
| 0022.jpg | hd-wallpaper-190056.jpg |
| 0023.jpg | hd-wallpaper-540115.jpg |
| 0024.jpg | himalayas-2301040.jpg |
| 0025.jpg | hintersee-3601004.jpg |
| 0026.jpg | hot-air-balloons-4561264.jpg |
| 0027.jpg | lake-1681485.jpg |
| 0028.jpg | landscape-564738.jpg |
| 0029.jpg | landscape-3913325.jpg |
| 0030.jpg | landscape-4347888.jpg |
| 0031.jpg | landscape-4928266.jpg |
| 0032.jpg | milky-way-3802391.jpg |
| 0033.jpg | milky-way-5673357.jpg |
| 0034.jpg | mill-4542153.jpg |
| 0035.jpg | moon-399834.jpg |
| 0036.jpg | moon-3572287.jpg |
| 0037.jpg | moon-4245400.jpg |
| 0038.jpg | mountain-425134.jpg |
| 0039.jpg | mountain-454249.jpg |
| 0040.jpg | mountain-477832.jpg |
| 0041.jpg | mountain-547363.jpg |
| 0042.jpg | mountain-1462655.jpg |
| 0043.jpg | mountain-2143877.jpg |
| 0044.jpg | mountain-4320647.jpg |
| 0045.jpg | mountain-4353332.jpg |
| 0046.jpg | mountain-biking-95032.jpg |
| 0047.jpg | mountain-climbing-2124113.jpg |
| 0048.jpg | mountain-landscape-2031539.jpg |
| 0049.jpg | mountain-range-640617.jpg |
| 0050.jpg | mountain-ranges-1835815.jpg |
| 0051.jpg | mountaineer-1185474.jpg |
| 0052.jpg | mountaineering-455338.jpg |
| 0053.jpg | mountains-100367.jpg |
| 0054.jpg | mountains-139012.jpg |
| 0055.jpg | mountains-190055.jpg |
| 0056.jpg | mountains-192987.jpg |
| 0057.jpg | mountains-276995.jpg |
| 0058.jpg | mountains-440520.jpg |
| 0059.jpg | mountains-540116.jpg |
| 0060.jpg | mountains-736886.jpg |
| 0061.jpg | mountains-833326.jpg |
| 0062.jpg | mountains-862870.jpg |
| 0063.jpg | mountains-1244132.jpg |
| 0064.jpg | mountains-1590012.jpg |
| 0065.jpg | mountains-1629079.jpg |
| 0066.jpg | mountains-1752433.jpg |
| 0067.jpg | mountains-1828596.jpg |
| 0068.jpg | mountains-1899264.jpg |
| 0069.jpg | mountains-1985027.jpg |
| 0070.jpg | mountains-3048299.jpg |
| 0071.jpg | mountains-4423621.jpg |
| 0072.jpg | nature-3082832.jpg |
| 0073.jpg | nepal-2184940.jpg |
| 0074.jpg | norway-4540662.jpg |
| 0075.jpg | outlook-1844110.jpg |
| 0076.jpg | phone-wallpaper-3807667.jpg |
| 0077.jpg | phone-wallpaper-5173654.jpg |
| 0078.jpg | phone-wallpaper-5372890.jpg |
| 0079.jpg | poppies-4971583.jpg |
| 0080.jpg | pyrenees-351266.jpg |
| 0081.jpg | rocks-1757593.jpg |
| 0082.jpg | rough-horn-2146181.jpg |
| 0083.jpg | sandstone-4025.jpg |
| 0084.jpg | schilthorn-3033448.jpg |
| 0085.jpg | schrecksee-2534484.jpg |
| 0086.jpg | sea-5515005.jpg |
| 0087.jpg | snow-1768544.jpg |
| 0088.jpg | starry-sky-5410078.jpg |
| 0089.jpg | sunset-2080072.jpg |
| 0090.jpg | tree-3095683.jpg |
| 0091.jpg | trees-6556336.jpg |
| 0092.jpg | valley-90388.jpg |
| 0093.jpg | view-from-table-mountain-3360058.jpg |
| 0094.jpg | volcano-1905556.jpg |
| 0095.jpg | water-3271579.jpg |
| 0096.jpg | waterfall-5312692.jpg |
| 0097.jpg | winnats-pass-5455265.jpg |
| 0098.jpg | winter-270160.jpg |
| 0099.jpg | wintry-2068298.jpg |
| 0100.jpg | yellow-mountains-532857.jpg |
