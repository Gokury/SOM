# SOM
Anomaly detection using SOM and ANN
Project: Anomaly detection using SOM and ANN

HOW DO SELF-ORGANIZING MAPS (SOM) WORK?
The short answer would be reducing dimensionality.
The example below of a SOM comes from a paper discussing an amazingly interesting application of self-organizing maps in astronomy.
 
The example shows a complex data set consisting of a massive amount of columns and dimensions and demonstrates how that data set's dimensionality can be reduced.
So, instead of having to deal with hundreds of rows and columns (because who would want that!), the data is processed into a simplified map; that's what we call a self-organizing map.
The map provides you with a two-dimensional representation of the exact same data set; one that is easier to read.

What exactly is the outcome to be gained from this process?
What you see below is an actual SOM. This map represents the levels of economic wellbeing across a wide range of countries.
 
As you can see, the countries are lined up in a cluster, and their order inside that cluster is based on various indicators (e.g. health conditions, quality of education, average income per capita, etc.).
You can imagine this data set of 200+ countries to have started off with 39 different columns.
It's tough to imagine such a bulk of data, isn't it?

That's exactly why we use SOMs.

Instead of presenting you with each indicator separately, the SOM lines up the countries inside this cluster to make up a spectrum of wellbeing.
You can see the countries on the left side being the ones with the best economic statuses, although they vary in colors based on their positions within the category of high-income countries.

Then as you move to the right, you find the countries getting poorer until you reach the far right which contains the countries with the direst levels of poverty.
There's an important difference between SOMs as an unsupervised deep learning tool and the supervised deep learning methods like convolutional neural networks that you need to understand.

While in supervised methods the network is given a labeled data set that helps it classify the data into these categories, SOMs receive unlabeled data.

The SOM is given the data set and it has to learn how to classify its components on its own.
In this example, it would look at, say, Norway, Sweden, and Belgium, and left to its own devices, it learns that these countries belong together within the same area on the spectrum.
Besides giving us an easy way to read this data, SOMs have a wider range of uses.
For instance, you probably saw a map similar to the one below where countries are colored based on their human development scores, crime levels, military spending, etc.
Such maps can be colored using a SOM, since we can take the colors that the SOM chose for each group and apply it to our world map.
 

Here's how the process goes:

 

In this case, we got the data set from the World Bank containing all 39 indicators of human development, processed them into a SOM, and then applied that to a world map.
As simple as that!

If you want to study this process at a more detailed level, we would recommend a paper titled “The Self-Organizing Map” that was authored by Tuevo Koheonen himself back in 1990, and  a slightly deeper introduction to SOMs, you can read this post from 2004 by Mat Buckland.




Data set: 
http://archive.ics.uci.edu/ml/datasets/statlog+(australian+credit+approval)
