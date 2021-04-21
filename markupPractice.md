# markupPractice
Practicing markup code and version control with branches

 
 For my data analytics class in Spring 2021, I evaluated the question "Does March come in like a lion, and go out like a lamb?" This is a folk wisdom that poor weather in the early part of the month means the end will be nice. An example would be snow, wind and chilly temps during the first week of March, and above average temps with little precipitation the last week.

![Raincloud](https://upload.wikimedia.org/wikipedia/commons/thumb/f/f7/Light_Rain_Cloud.png/298px-Light_Rain_Cloud.png)

My project is [here](https://rpubs.com/trishBeekeeper44231/751030)!

![lion and lamb](https://img.17qq.com/images/qrrtuwqtchx.jpeg)


An example of R code for making a figure is below:
```fig3.raw.normed<-ggplot(weekAvg) + 
  geom_point(aes(x=week,y=NORMED,color=year)) +
  geom_text(aes(x=week,y=NORMED,label=year),data=yrAvg) +
  geom_text(aes(x=week,y=NORMED,label=year),data=yrFlipdn) +
    geom_text(aes(x=week,y=NORMED,label=year),data=yrFlipup) +
  ggtitle("Normalized high temps with the average removed for weeks 1 or 4") + 
  xlab("week in March") + 
  ylab("Normalized High Temp")
  ```
  where **_fig3.raw.normed_** is the name of the figure that is called later, and the rest of the code after the **_<-_** is the instructions on drawing the figure. 

  The upshot of my findings: February seems to do a better job of coming in like a lion, and out like a lamb. It is probably just random. 