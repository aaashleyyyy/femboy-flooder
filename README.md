# rule34-flooder
0x150's femboy-flooder but way worse and more convincing.

Theres a jar with extra file size to make the jar more convincing in releases.

You can easily change the rule34.xxx image tag by navigating to src/main/java/cum.java, on line 26, there is this code " String resp = getHTML("https://rule34.xxx/index.php?page=dapi&s=post&q=index&tags=guro&limit=" + winAmount);" at the end of it, replace the "guro" with whatever tag you want.

You also can easily change the amount of images that appear by navigating to src/main/java/cum.java, line 20 (int winAmount = 120;), change the number on the end to any number you'd like.  ***Going above 200 images will likely break it because it will run out of memory.***
