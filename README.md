# VAST 4.0 Test

It is example of linear 30 seconds video ad, skippable after 10 seconds.
Ad is defined in [VAST 4.0](https://www.iab.com/wp-content/uploads/2016/04/VAST4.0_Updated_April_2016.pdf), Video player with VAST capabilities is [Fluid Player](https://docs.fluidplayer.com)


## Run

```console
$ docker build -t vast4 .
$ docker run -dit --name vasr4-app -p 8080:80 vast4
```