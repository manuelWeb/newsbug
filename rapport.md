diff -r /cygdrive/c/Users/mdevries/Pictures/tl/newsLetter/loco/0518/TH07_salade/HTML/src/FR/partial/_content.slim /cygdrive/c/Users/mdevries/Desktop/tempsDiff_FR/src/FR/partial/_content.slim
75c75
<                         span == eval("$lib#{item[1]}_")
---
>                         span == $objso["lib"]["fr_"]["pk#{item[1]}"]
77c77
<                         b == eval("$price#{item[1]}")
---
>                         b == $objso["price"]["pk#{item[1]}"]["fr"]
diff -r /cygdrive/c/Users/mdevries/Pictures/tl/newsLetter/loco/0518/TH07_salade/HTML/src/FR/partial/_header.slim /cygdrive/c/Users/mdevries/Desktop/tempsDiff_FR/src/FR/partial/_header.slim
3c3
<   td.m0auto width="620" align="center" style="padding-top: 4px;"
---
>   td.m0auto width="620" align="center" style="padding-top: 4px; padding-bottom: 12px;"
