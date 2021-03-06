# Vincent DeAugustine: iOS Developer

## Hi, my name is Vincent. I am a recent college graduate and iOS App developer. I graduated with a BS in Computer Science from California State University, Fullerton. I have been developing iOS apps for 6 months. Here is some more about me and my projects.    

---
# Contents 
- [Finished iOS Apps](#finished-ios-apps)
    - [Dialed In Golf (Published to App Store)](#dialed-in-golf)
        - [About](#about-dialed-in-golf)
- [Baseble: A Baseball Name Word Game](#baseble-a-baseball-name-word-game)
- [My Other Interests](#my-other-interests)
    - [My Podcast](#my-podcast)
    - [Golf](#golf)
    - [Movies and TV Shows](#movies-and-tv-shows)

<br/>
<br/>
<br/>

# Finished iOS Apps
## Dialed In Golf 


<body style="text-align: center;">
    <a href="https://apps.apple.com/us/app/dialed-in-golf/id1607559987">
        <img src=
"https://user-images.githubusercontent.com/32307897/170838107-8c4239a4-1a45-436f-a99d-e18c552a58e0.png"
             alt="Dialed In Golf" width="80">
    </a>
</body>
<br>

### [Apple App Store Link](https://apps.apple.com/us/app/dialed-in-golf/id1607559987) 


<body style="text-align: center;">
    <a href="https://github.com/vdeaugustine/DialedInGolfApp">
        <img src=
"https://user-images.githubusercontent.com/32307897/170837967-4e5a660c-c207-4fd5-9f51-0b6e439683c4.png"
             alt="Dialed In Golf Github" width="80">
    </a>
</body>
<br>

### [Github Link](https://github.com/vdeaugustine/DialedInGolfApp)

<br>
<p float="left">
  <img src="https://user-images.githubusercontent.com/32307897/153724192-b38d111c-2d15-48b0-abc4-ed4cc4badfb2.jpeg" width="175" />
  <img src="https://user-images.githubusercontent.com/32307897/153724191-b34155b3-51a7-4674-a8bb-1ae96f1776aa.jpeg" width="175" /> 
  <img src="https://user-images.githubusercontent.com/32307897/153724190-bab2694f-dc38-47b5-9063-d7f8353f91e9.jpeg" width="175" />
  <img src="https://user-images.githubusercontent.com/32307897/153724186-4531f46e-a3aa-4b3b-906b-6ad3dba6bce0.jpeg" width="175" />
</p>

## About **Dialed In Golf**
This was my first iOS app I developed from scratch and published to the App Store. 

## Purpose
I developed this app because I love to golf. I believe it solves a proble mthat so many golfers face, regardless of skill level. Every golfer needs to know how far they hit their clubs. It is often not easy to know these numbers, espeically off the top of your head while you are on the course. 


## Technologies and Frameworks used in development
- **UIKit** and **Storyboard**
 are used for UI Design.
- **Codable, Encodable, Decodable,** and **Equatable** used for saving club distances and other persistence using **NSUserDefaults**.
- **CoreData** is used for saving and updating notes.
- **StoreKit** is used for in-app purchases.
- **AVFoundation** is used for sound effects. 

## Challenges faced during development and lessons learned
- This app tought me about strategies to use while developing independently. 
- When I began, I had an idea in my head about what I wanted the app to do, but I wasn't sure how I was going to make it look. 
- There was a fair amount of trial and error when developing the UI and it progressed through different iterations. 
- I began using Storyboards to build the app but for some of the scenes I used  




# Redesign

<p float="left">
  <img src="https://user-images.githubusercontent.com/32307897/175080021-f8ffa951-4f2c-4a67-9957-ff23351a26f6.png" width="175" />
  <img src="https://user-images.githubusercontent.com/32307897/175080048-99886cff-7e05-40fd-a442-5a814c3f7de4.png" width="175" /> 
</p>
### Framework: <u><b>SwiftUI</b></u>

  ### Purpose of Redesign:
  - When I was building the golf app for the first time, I was in a hurry to get it finished and I was eager to publish it to the App Store. 
  - After it got accepted to the App Store, I knew I didn't like the UI design. I wrote up what I wanted the design to look like if I gave it enough time. 
  - I knew I could accomplish this design in UIKit but I thought it would be a great opportunity to finally learn the SwiftUI framework. 
  - So after finalizing what I wanted it to look like, I took on the task of rebuilding the app from scratch using SwiftUI. 
  - It took longer than it would have if I just redesigned it using the same UIKit codebase that I already had, but it was a good learning experience as now I am comfortable with data flow in SwiftUI and I am confident in my ability to tackle any design using SwiftUI. 
  - The redesign is almost finished and should be published as an update to the app on the App Store soon.

- [Back to Table of Contents](#contents)
---

<br/>
<br/>

# Baseble A Baseball Name Word Game

<body style="text-align: center;">
    <a href="https://github.com/vdeaugustine/BaseballWordle">
        <img src=
"https://user-images.githubusercontent.com/32307897/170837967-4e5a660c-c207-4fd5-9f51-0b6e439683c4.png"
             alt="Baseble Github" width="80">
    </a>
</body>
<br>

### [Github Link](https://github.com/vdeaugustine/BaseballWordle)




<p float="left">
  <img src="https://user-images.githubusercontent.com/32307897/170774251-8cc39686-d2cc-42c4-9e8e-533b2a4d6a18.gif" width="175" /> 
  <img src="https://user-images.githubusercontent.com/32307897/170769781-408b8243-7025-4cbf-8a9b-2987af74b0c6.jpeg" width="175" />
  <img src="https://user-images.githubusercontent.com/32307897/170769988-72e57435-ed43-4c15-82db-61d100dc3324.jpeg" width="175" />
  <img src="https://user-images.githubusercontent.com/32307897/170770066-b6eedc94-ffa5-47e5-965d-7e2f409834eb.jpeg" width="175" />
</p>

### Framework: <u><b>UIKit</b></u>

## About Baseble
As Wordle took off in popularity, I noticed there was a demand for variations of it, and especially in the sports fan community on Twitter and Reddit. I combined my love for baseball and iOS app development into a fun game that helped me learn about animations, JSON parsing, and using third party libraries with Swift Package Manager.



## Technologies and Frameworks used in development
- In order to have the word of the day be the same for every user of the app, I used Firebase.
- The database would be updated every day at midnight and the app would make a REST API call to get the word using the Firebase SDK.

 - [Back to Table of Contents](#contents)
---

<br>
<br>

# In Progress 


## Baseball Draft App
<p float="middle">
<img src="https://user-images.githubusercontent.com/32307897/170808980-66b96f01-efd5-47a9-8849-50197a30ca97.gif" width="175" />
<img src="https://user-images.githubusercontent.com/32307897/171047440-fedd6046-d04d-41c4-a5f2-7fd01f8fd592.gif" width="175" />
</p>

### Framework: <u><b>UIKit</b></u>

## Purpose
- When you are drafting a team for fantasy baseball, should you draft a second baseman with 450 projected points or a first baseman with 550 projected points? What if the other second basemen available average only 300 points and the other first basemen average 500 points? 

- This app is designed to take that confusion out of it for you. Every player's projected points are weighted against the average at that position. That way you know which player is more valuable due to "position scarcity."

- Other features:
    - Search bar for players
    - Stats for each player from different projection systems including [ATC Projection System](https://fantasy.fangraphs.com/the-atc-projection-system/) and [ZiPS Projection System](https://blogs.fangraphs.com/category/2022-zips-projections/). Both found on [Fangraphs](https://fangraphs.com)
    - Trade Analysis tool 
        - Select the players that each team would give up and it will give you an analysis of the trade, telling you which team will win the trade and by how much each team will benefit. 


## Technologies and Frameworks used in development

- [Back to Table of Contents](#contents)

## Cryptocurrency Library

<img src="https://user-images.githubusercontent.com/32307897/170835988-45e6a510-0533-4975-9c06-df9fbf3ec728.gif" width="175" />

### Framework: <u><b>UIKit</b></u>

The purpose of this application is to demonstrate the ability to use REST API calls in swift. The program uses the CoinLib API to fetch information about any cryptocurrency listed on the market. The user can also create their own wallet and keep track of certain coins they own. 


  [Back to Table of Contents](#contents)

## SwiftUI Projects in Progress
### I love learning the latest technology. And right now one of the most exciting things in iOS development, I believe is SwiftUI. I love seeing the designs and experiences people in the iOS development community. 


<img src="https://user-images.githubusercontent.com/32307897/170836147-0e840945-829b-49a9-894f-65828dbebab8.gif" width="175" />

This is the same concept as the Coin Lib app that I am working on above, however this one is built in SwiftUI. 


- [Back to Table of Contents](#contents)
---

<br>
<br>

# School Projects 

## Piano Keys Imitation App
<img src="https://user-images.githubusercontent.com/32307897/170810637-1dae6f97-a6ec-4150-88a4-46281319e3a3.gif" width="175" />

<p> This was one of the first apps I ever built. It was for a homework assingment for my iOS development class at CSUF. If you are not failiar with the Piano Keys app on the App Store, the goal is to tap only the black tiles as fast as you can. If you tap the white tiles, the game is over. The app saves the user's high score in NSUserDefaults. 

- [Back to Table of Contents](#contents)
---

# Social Media
## Active in the iOS Development Twitter community
<img src= "https://user-images.githubusercontent.com/32307897/170811107-c4716eae-a637-4c0a-8b73-41f68df4f6f0.PNG" width="50"> [My Twitter Account](https://www.twitter.com/VinnieiOS)


<br>
<br>


- [Back to Table of Contents](#contents)

# My Other Interests

## My Podcast

<img src="https://user-images.githubusercontent.com/32307897/170810045-1abb06d7-c940-4e09-8e6d-f7cfde4543a5.PNG" width="200" />
<p> Produce and host my own baseball podcast about the Angels and the Dodgers </p>


 
 ## [Apple Podcasts Link](https://podcasts.apple.com/us/podcast/freeway-feuds-an-angels-and-dodgers-podcast/id1499440527)
<body style="text-align: center;">
    <a href="https://podcasts.apple.com/us/podcast/freeway-feuds-an-angels-and-dodgers-podcast/id1499440527">
        <img src=
"https://user-images.githubusercontent.com/32307897/170810102-26a24135-a969-4159-a08e-5c64d03e4c29.PNG"
             alt="Freeway Feuds on Apple Podcasts" width="80">
    </a>
</body>
<p>
<br>

## [Spotify Link](https://open.spotify.com/show/5iuhwWLiPXHWXKnrkVPjX1)
<body style="text-align: center;">
    <a href="https://open.spotify.com/show/5iuhwWLiPXHWXKnrkVPjX1">
        <img src=
"https://user-images.githubusercontent.com/32307897/170810132-7b2f0b98-8816-45d6-b462-2c0a0d1ca0e7.PNG"
             alt="Freeway Feuds on Spotify" width="80">
    </a>
</body>
 
---

## Golf



<img src="https://user-images.githubusercontent.com/32307897/170836274-a5cf5575-61c7-4a93-b36e-8d541a6c181b.jpg" width="300" />

I started golfing a little bit in high school, but I didn't start taking it seriously until around the beginning of 2021. My average score is usually somewhere around +10 to +12.
I am always excited for a round of golf. It is a great way to get outside and have fun with some friends, and even meet new people. 

## Favorite Movies

<img src="https://images-wixmp-ed30a86b8c4ca887773594c2.wixmp.com/f/5298bac0-b8bf-4c80-af67-725c1272dbb0/defibp5-8019b091-dae8-426d-8276-7b6d15afcce8.jpg?token=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJzdWIiOiJ1cm46YXBwOjdlMGQxODg5ODIyNjQzNzNhNWYwZDQxNWVhMGQyNmUwIiwiaXNzIjoidXJuOmFwcDo3ZTBkMTg4OTgyMjY0MzczYTVmMGQ0MTVlYTBkMjZlMCIsIm9iaiI6W1t7InBhdGgiOiJcL2ZcLzUyOThiYWMwLWI4YmYtNGM4MC1hZjY3LTcyNWMxMjcyZGJiMFwvZGVmaWJwNS04MDE5YjA5MS1kYWU4LTQyNmQtODI3Ni03YjZkMTVhZmNjZTguanBnIn1dXSwiYXVkIjpbInVybjpzZXJ2aWNlOmZpbGUuZG93bmxvYWQiXX0.pojNP43h1WC_XSz5oyqkpLbNmCChKMYG38UqYi8b44o" width="400" />
<br>

### Anything in the Marvel Cinematic Universe

<br>
<br>
<p float="left">
  <img src="https://c4.wallpaperflare.com/wallpaper/743/1018/523/interstellar-2014-wallpaper-preview.jpg" width="300" /> 
</p>

---




## Currently Reading
<p float="left">
  <img src="https://images-na.ssl-images-amazon.com/images/I/9168wNMBk1L.jpg" width="150" /> 
</p>

---

## Recently Read
<p float="left">
  <img src="https://go.darrenhardy.com/_next/static/images/book-new-small-360-a67170c3e8fb54e2949a93942c6a9777.png" width="150" /> 
</p>



- [Back to Table of Contents](#contents)
