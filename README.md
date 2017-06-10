![documentations](http://getprowl.com/assets/images/documentation1.png)
<h1 align="center">Common Use Cases with Prowl</h1>

# Nightclubs 

We've installed Prowlboxes at various venues, but nothing as diverse as a nightclub. 

![documentations](http://getprowl.com/assets/images/prowlbox.jpg)

This is so you can see your patrons playlist (once they are connected to your WiFi, they automatically accept the ToS by accepting the ToS that the club's WiFi has. So this is completely fine. 

So there's a couple of things you can do with this data that you capture at a nightclub when you purchase a Prowlbox. 

* Take the data you get, then know what artist to book for your next event.
* Know your demographic better, market in different ways, for more of a population outcome. 

Graph out your population each event you throw.

![documentations](https://sites.google.com/a/academicrightspress.com/arp/_/rsrc/1456074309358/entertainment/music/music/Flyer%20graph%20image.png)

# Coffee Shops 

This is essentially very different from a nightclub, you want to know what people are listening to so you can cater to your customers listening habits by playing stuff over your system when they walk in, they are more inclined to come back to that coffee shop, and set the perfect atmosphere for customer retention. 

![documentations](https://static1.squarespace.com/static/55b65ffee4b0eeee5d6a5a39/55ee11a0e4b06837e7058b5d/55ee11a3e4b0c46828ed5176/1441665454847/3+Ideas4.jpg)


# Music Festivals 

The amount of data the Prowlbox would be receiving would be overwhelming, which is why we have a bigger Prowlbox for bigger events, with stronger hardware, usually the Prowlbox can handle up to 500 patrons at a time. When you're talking a music festival you are talking several thousdands, in some cases tens of thousands. 

![documentations](https://www.tourtech.com/wp-content/uploads/2017/01/Screen-Shot-2017-01-31-at-4.27.39-PM.png)


# Retail Stores 

Implanting a Prowlbox at your retail store could be crucial for your PoS service, and your PoP. For example, to see what music to play to get the best customer retention, but to get the customer to make their purchase quickly to make other customers feel more attended to by your staff. 

![documentations](http://d3fi73yr6l0nje.cloudfront.net/PublishingImages/rsz_retailnext_heatmap_art_03-2012.jpg)

# Getting moods from playlists

We can decipher moods from people's playlist, which of course depending on the mood of the overall crowd in your coffee shop/retail store, you can switch the music to say "upbeat  music" to increase chances of sales, via mood, or even play more depressing music so the people shop more via "Retail Therapy", to make themselves feel better. 

![documentations](http://www.getprowl.com/assets/images/flow.png)

With some of the software we offer (along side the box) is heatmaps of the store where it gets cold at certain times, and why this might be - to see if that customer was listening to music at that time or not, or at the very LEAST to see what their Spotify playlist says about their personality so Prowl can start bulding customer profiles on individual customers.

## Common Troubleshooting Processes You Can Use In Real Life Scenarios

If the Prowlbox "quits" working, e.g. stops collecting data, you can bring your MacBook, boot into the box, and make sure the container is running, via running 

<pre>docker inspect -f prowlbox</pre>

If you get results, then reboot the container via

<pre>docker restart</pre> 

![documentations](https://getprowl.com/assets/images/terminal.png)

That should solve 99% of the issues, we are currently working for a fix on this problem, it's only happened once. One time is too many though for our device to fail. This will be solved within the week of this MD page being made. 
