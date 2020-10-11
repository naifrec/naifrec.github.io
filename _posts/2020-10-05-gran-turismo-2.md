---
layout: post
title: gran turismo 2, a data analysis
date: 2020-10-10 08:00:00 -0000
description: visualizing some data about one of the pillars of the psx
---

As mentionned in [my post on my musical influences](../../2019/glimpses-of-a-90s-child-musical-journey), I grew up with the PlayStation. My father offered me the PSX in 1997, I was 4 years old. I think he made this gift to me, but really he was low-key buying it for him. He bought it with Tekken 2, and we also had the demo disc. I remember the latter vividly, it was so awesome, intriguing, and even a bit scary. When going back to it recently, I realized how acid and futuristic they made the menus look. The intro music is [pure acid techno goodness for your ears](https://youtu.be/lPhFsdgI958?t=14). The tech demo is where it got a bit scary, I distincly remember watching the T-Rex walking with the ominous music playing and being absolutely speechless, my heart racing.

<div style="text-align: center;"> <iframe width="560" height="315" src="https://www.youtube.com/embed/YCtZIlolG6w" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe> </div>
<div style="text-align: center;margin-bottom: 25px"> T-Rex tech demo on PlayStation 1 demo one disc, 1997</div>

In 1998 my father expanded our video game library, adding Gran Turismo and Colin McRae Rally to the collection. I sucked hard at Colin McRae, so I sticked to Gran Turismo which was way more forgiving to a 5 years old. I remember playing the arcade mode, as I could not navigate the simulation mode just yet. I would play Clubman Stage Route 5, with the absolutely amazing Chevrolet Corvette Stingray '67. It was such a powerful car. I loved playing it specifically on this track, as the night model of the car would have the opened headlights. I sometimes raced with my father, and would win each time I'd play this car... to this day I still don't know if he was letting me win or if my victories were legit.

<div style="text-align: center;"> <iframe width="560" height="315" src="https://www.youtube.com/embed/c-fW0xH4lgg" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe> </div>
<div style="text-align: center;margin-bottom: 25px">Chevrolet Corvette Stingray in arcade mode on Clubman Stage Route 5, Gran Turismo 1</div>

When I moved to Normandy in 1999, I spent a lot more time playing with my cousin Pierre. We spent most of our time outside of school together, playing an array of awesome video games (Crash Bandicoot Warped, Crash Team Racing, Syphon Filter, and many others). We eventually started playing Gran Turismo 2, and I think it is one of the games we invested most time on. It was so innovative for its time. Frankly even by today's standards, a car list just shy of 600 cars is baffling. There was also so much to do: special races with different requirements (muscle car cup, cup for each drivetrain, GT300 and 500 series), endurance events, rally events, national and world championships, and then a myriad of manufacturer events...

One of the many highlights of this release is the soundtrack. While researching this game, I realized us Europeans were blessed with the best (change my mind) version of the soundtrack, with the likes of [Fatboy Slim](https://youtu.be/Nh7oGo5sn2o) and [Propellerhead](https://youtu.be/A4ZuS7ebwTA). By far my favorite track while racing was the one featured below by Grooverider, [considered an originator](https://en.wikipedia.org/wiki/Grooverider) of the UK dnb scene. The mix gives into that amazing ambient drum'n'bass genre, which was living its golden era at the time.

<div style="text-align: center;"> <iframe width="560" height="315" src="https://www.youtube.com/embed/rTG1YWbt5d0" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe> </div>
<div style="text-align: center;margin-bottom: 25px">Everything But The Girl - Blame (Grooverider Jeep Mix)</div>

***

Back to the actual game, I recently went back at it. I installed ePSXe (a PSX emulator) on my desktop PC, tuned it so I could play the game in widescreen mode, downloaded the ROM and jumped straight back at it. And suffice to say the game still holds to this day, I am having tons of fun. I came to realize the depth of gameplay, where tuning your car can make the worst car a worthy opponent. Back when we were 8, me and my cousin, we had no clue what we were doing. We were just buying the 4 upgrades for that turbo and brought that horsepower number as high as possible, to hopefully win against the AI by being faster on the straights. Or, after grinding for some cash on that Red Rock Valley race which would win you the TVR Speed 12 worth 500,000 credits, we would buy the Escudo Pikes Peak and win by just pressing on the accelerator and nudging the car in the right direction.

Being now a [30 years old man](https://twitter.com/MediumWilly/status/1311070574177779712) and a licensed driver with some knowledge of car mechanics and physics, I could better navigate the car tuning. In fact, I delved into it in details out of curiosity. I subscribed to an amazing YouTube channel called [viperconcept](https://www.youtube.com/user/viperconcept) which has an endless number of tutorials on racing related topic, including how to setup [suspensions](https://youtu.be/djfi7F31jyM) and [Limited Slip Differential](https://youtu.be/8HXhUd5pZlM) (LSD, kek). And while viperconcept shows the effect of tuning his cars in more recent sim racing games, what amazed me is that most of his advices still held true in GT2! I developed my own strategy at tuning. First buy the fully customizable gear, soft tyres and fully customizable suspensions. Then lower the car close to its minimum height to avoid weight transfer / roll, stiffen the suspensions to make the car more nervous, put 1 to 2 degrees of negative camber then tune the gear ratios (using the automatic slider) so that you max out exactly at the end of the longest straight. One of the many learnings I got out of viperconcept is: *tune the suspensions to the car, the dampeners to the track*. Super smooth track like High Speed Ring, low dampening, very rough track like Grindelwald or Seattle, high dampening. If you feel like the gear shifts are too slow, buy an improved clutch, and off you go.

This time around, I challenged myself not to use overpowered cars like I used to as a kid, crossed off the Escudo Pikes Peak entirely, and it made the game quite exciting and frankly not so easy at times. However, as a more observant adult, I started notifying some (mildly annoying) patterns. My main criticism to this game is how skewed towards Japanese cars it actually is. I know this is a bit ridiculous to blame Polyphony Digital, a Japanese company, for focusing on Japanese cars, but let's say that I feel like they could have tried a bit harder at making manufacturers from other countries, especially European ones, less gimmicky / we put you there so you cannot complain there was no european cars.

***

As I wanted to back up my claim with data, I went through the effort of scraping the car list from [GT wiki website](https://gran-turismo.fandom.com/wiki/Gran_Turismo_2/Car_List), clean it up and make it usable for data analysis. I hereby present you [GT scrape](https://github.com/naifrec/gt-scrape), a small python project I built which uses beautifulsoup for scraping, a lot of regex magic for cleaning up, and finally pandas to process and analyze data. I am hosting [the cleaned up data on dropbox](https://www.dropbox.com/sh/aghqvta3wl0adri/AABQc85oMTnrTcDpycBZzsg4a?dl=0) if you want to have a go at it yourself. For now, using this data, we are going to address 4 of my claims:
1. most cars are Japanese
2. most prize cars are Japenese
3. most of the best cars are Japanese (and we will take the time to define what "best" means)
4. most cars are from the 90's

For the first two claim, I made the following figure, [using this code](https://github.com/naifrec/gt-scrape/blob/main/gt/plots/car_distribution.py). It shows, for each country of origin, the number of available cars in the game (in pink), and within them the subset of cars that can be won as prize during race events (in brown). Note that I used a log-scale on the x-axis, otherwise it would have been impossible to see that you can actually win at least one car from each country.

<div class="row mt-3" >
    <div class="col-sm mt-3 mt-md-0" style="text-align: center;">
        <img class="img-fluid rounded" src="{{ site.baseurl }}/assets/img/distribution-of-cars-log.png" width="65%">
    </div>
</div>

We can try and summarize these statistics, let's see how to compute the percentage of cars per country using the following code snippet:

{% highlight python %}
import pandas as pd

from gt.paths import DATA_DIR


# load the CSV data in a pandas DataFrame
df = pd.read_csv(DATA_DIR / 'cars-clean-v2.csv', index_col=0)
# count the number of car per country
data_cars = df['Country'].value_counts().reset_index().rename(
    {'index': 'Manufacturing Country',
     'Country': '# cars featured',
    },
    axis=1
)
# count the number of prize car per country
data_prize_cars = df[df['IsPrizeCar']]['Country'].value_counts().reset_index().rename(
    {'index': 'Manufacturing Country',
     'Country': '# cars featured',
    },
    axis=1,
)
# print percentages of cars per country
print(100 * data_cars['# cars featured'] / data_cars['# cars featured'].sum())
# print percentages of prize cars per country
print(100 * data_prize_cars['# cars featured'] / data_prize_cars['# cars featured'].sum())

{% endhighlight %}

In summary, **7 cars out of 10 in the game are Japanese**, and if you only look at **prize cars**, then **8 out of 10** are Japanese! I wonder how many Skylines are within these hehe, an exercise left to the reader.

***


Now let's tackle my third claim that *most of the best cars are Japanese*. It is of course impossible to find one single metric which can define how great a car is, as none will reflect how well the car is tuned or handles. One car could have the highest power, yet suck because too heavy or tuned poorly, as in too soft suspensions, too long gear ratios, etc. For this exercise though, we will use one metric which is a good predictor of a car's performance (assuming handling and tuning): power to weight ratio (kg per brake horse power). The lower this number is, the more powerful is the car, as it literally counts how much mass does each horse power have to move, lower meaning it will be easier to get that car moving. You can find [here](https://github.com/naifrec/gt-scrape/blob/main/gt/plots/top_cars.py) the code used to obtain the table and images below.


|    | Name                               | Power (bhp) | Weight (kg) |   Power/Weight Ratio |
|---:|:-----------------------------------|------------:|------------:|---------------------:|
|  1 | Suzuki Escudo Pikes Peak Version   |         981 |         800 |                 0.82 |
|  2 | Nissan HKS Drag 180SX              |        1011 |         980 |                 0.97 |
|  3 | Suzuki Cultus Pikes Peak Version   |         788 |         873 |                 1.11 |
|  4 | Toyota GT-ONE Race Car (TS020) '99 |         765 |         900 |                 1.18 |
|  5 | TVR Speed 12                       |         807 |         950 |                 1.18 |
|  6 | Nissan HKS R33 Drag GT-R           |        1011 |        1280 |                 1.27 |
|  7 | Toyota GT-ONE Race Car (TS020) '98 |         672 |         900 |                 1.34 |
|  8 | Venturi Atlantique 600 LM          |         705 |         960 |                 1.36 |
|  9 | TVR Cerbera LM Edition             |         624 |         890 |                 1.43 |
| 10 | Honda CR-X del Sol LM Edition      |         617 |         890 |                 1.44 |
| 11 | Lotus Elise GT1                    |         613 |         900 |                 1.47 |
| 12 | Toyota GT-ONE Road Car (TS020) '98 |         593 |         900 |                 1.52 |
{:.table}

<div class="row mt-3" >
    <div class="col-sm mt-3 mt-md-0" style="text-align: center;">
        <img class="img-fluid rounded" src="{{ site.baseurl }}/assets/img/top12.png">
    </div>
</div>


First of all, the limitation of picking a single metric to define how good a car is should jump to the GT amateur's eyes, because god knows how terrible these drag cars are. They handle like a potatoe, and are only remnants of an abandonned drag mode.

If we forget about these two cars for a moment however, the rest of the ranking seems quite truthful. Unsurprisingly we find the **Suzuki Escudo Pikes Peak at the top**, with 0.82 kg per bhp (far better than any other cars, which makes it so overpowered). **Only 4 cars out of the top 12 are non-Japanese**: the British TVR Speed 12, TVR Cerbera LM Edition and Lotus Elise GT1, and the French Venturi Atlantique 600 LM. I lol'ed at the fact that the Toyota GT-One appears 3 times in the top 12, did we really need both the '98 and the '99 race car models?

Finally, interesting to note that it may be worth grinding for the gold in License B early in game, as you will be rewarded the 10th best car in the game, the Honda CR-X del Sol LM Edition.

***

Finally, let's visualize my last claim: *most cars are from the 90's*. While this is both obvious, and also an expected feature (nobody wants to race with only cars from the 60's), I found it interesting to see it drawn on a timeline. Note that many approximations had to be made, a lot of cars in the games did not have a manufacturing date, so I implemented an automated way to get a year from their in-game descriptions, which is not without bugs (see logic [here](https://github.com/naifrec/gt-scrape/blob/main/gt/table/scrape.py#L118-L136)). You can find the code used to create the timeline below [at this location](https://github.com/naifrec/gt-scrape/blob/main/gt/plots/car_timeline.py).

<div class="row mt-3" >
    <div class="col-sm mt-3 mt-md-0" style="text-align: center;">
        <img class="img-fluid rounded" src="{{ site.baseurl }}/assets/img/timeline-of-cars.png" width="80%">
    </div>
</div>

We can further summarize this timeline by computing the percentage of cars released in the 90's using the following code snippet:

{% highlight python %}
df = df[~df['Date'].isna()]
df['Date'] = df['Date'].astype(np.int32)
print(100 * ((df['Date'] >= 1990).sum() / len(df)))
{% endhighlight %}

From this computation comes out that **9 cars out of 10 are from the 90's**. The GT amateur would have a good grasp on this limitation, as for some race events in the games, this leaves for very few options (most notably the muscle car event, where you probably have to pick from 4-5 cars max).

***

This concludes my quick go at scraping, cleaning and analyzing the data from Gran Turismo 2. I hope this article was somewhat entertaining, and that you can yourself make use of the data I extracted from the Gran Turismo Wiki website to show some cool facts about the game! Not to leave you without one last track, here is one of my favorite remix from the Gran Turismo 2 soundtrack, with some crazy drum patterns... enjoy!

<div style="text-align: center;"> <iframe width="560" height="315" src="https://www.youtube.com/embed/suB4gLaR6wc" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe> </div>
<div style="text-align: center;margin-bottom: 25px"> Gran Turismo 2 Extended Score - Groove - Blowing Away</div>
