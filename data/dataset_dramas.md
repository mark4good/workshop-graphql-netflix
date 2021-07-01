```
mutation movies_dramas {

 girl1: insertmovies_by_genre(
    value: { 
      genre:"Dramas", 
      year:2016,
      title:"The girl on the Train",
      synopsis:"A divorcee becomes entangled in a missing persons investigation that promises to send shockwaves throughout her life.",
      duration:112,
      thumbnail:"https://i.imgur.com/yinQyyT.mp4"}) {
    value{title}
  }
 hippowars_1: insertmovies_by_genre(
    value: { 
      genre:"Dramas", 
      year:1996,
      title:"Hippo Strikes Back",
      synopsis:"One Hippo, One Dream, One Crazy Summer. From the Creators of Parasite.",
      duration:123,
      thumbnail:"https://i.imgur.com/m7nx4nX.mp4"}) {
    value{title}
  }
}
```
