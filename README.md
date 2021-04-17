# Interactive-map-of-Places-i-want-to-visit-in-europe-
Interactive map of places where i want to visit. When you click on the markers, instagram photos that i saved will pop up. I was interested from this 
	[Github page](https://github.com/Pubs-of-Oxfordshire-Map)


For creating the map that you can see below, i provided coordinates and instagram urls of the photos. Clicking to the markers pops up the instagram photo. <br/>
![map of germany](https://user-images.githubusercontent.com/65399053/115022431-0f292500-9ec6-11eb-8053-4d9a8090fdc9.JPG)
<br/>
Right now i am trying to impove my code by automaticaly adding photos to my map. One can easily add instagram photos to a saved folder in Instagram app. However, it is not a straightforward process to add those photos to the map i showed above. I am trying to implement a code that will transfer those saved photos into my map. 

Here are the steps i will take (includes problems i am facing right now):
<br/>
1.Below image shows the instagram website where the photos i saved from the Instagram app goes. <br/>
![germany list](https://user-images.githubusercontent.com/65399053/115020785-b9ec1400-9ec3-11eb-80c6-35249d2302a5.JPG) <br/>
This web page is piravate and only accesible to my account. So I will use the html code of it ( probably javascript will cause some issues but i will provide the data accordingly) and extract instagram links of the individual photos, which those links are accessible by any browser.
<br/>
2. Next step will be extracting information from the individual photos. Each photo that i saved to my instagram "Germany" list includes adresses. I can't access to the address information by just looking at the html code, because they are hidden with the javascript barrier. I am looking for solutions for this. <br/>
4. After that i will have to transform addresses into latitude and longitude, and i have already written code for that and it works. <br/>
5. Finally, I will have coordinate information and corresponding instagram link to a photo. I will plug this information to my initial mapping code. 
