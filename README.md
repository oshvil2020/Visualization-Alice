# Visualization-Alice

You can color a word-cloud by using an image-based coloring strategy implemented in ImageColorGenerator. 
It uses the average color of the region occupied by the word in a source image. 
You can combine this with masking - pure-white will be interpreted as ‘don’t occupy’ by the WordCloud object when passed as mask. 
If you want white as a legal color, you can just pass a different image to “mask”, but make sure the image shapes line up.
