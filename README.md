Collapsible-tree-D3.js
======================

This is the code for collapsible tree using D3.js . It will read the json file in the data folder and based on the data
it will produce the collapsible tree.

Each circle represent a node having a name similar to the name given in the data.json file and color of every node/
circle is based on the size of every node given in the file.

Color based on the size : 

                 size                     color
              size < 1000                 pink
              1000< size < 2000           green
              2000 < size < 4000          red
              4000 < size < 7000          blue
              7000< size < 15000          light green
              size > 15000                yellow

In that size option in the file you can replace it with any other parameter and if the circle color is orange it means that
it has children set which on clicking the node will open up and if the circle color is white it means that its all child are 
opened up or it has no child.

Using the D3.tip.js we can get the size as we hover on the respective node . 

So we can change the data file according to your need and set any parameter and change the color of that.


