# Netrek

This is the multi-player game of Netrek.

Netrek is probably the first video game which can accurately be
described as a "sport".  It has more in common with basketball than
with arcade games or Quake.  Its vast and expanding array of tactics
and strategies allows for many different play styles; the best
players are the ones who think fastest, not necessarily the ones who
twitch most effectively.  It can be enjoyed as a twitch game, since
the dogfighting system is extremely robust, but the things that
really set Netrek apart from other video games are the team and
strategic aspects.  Team play is dynamic and varied, with roles
constantly changing as the game state changes.  Strategic play is
explored in organized league games; after 6+ years of league play,
strategies are still being invented and refined.

The game was created in 1988, and still has players, including some
people who have been playing for nearly as long as the game has
existed.

## Get Started

Clone this repository;

```
git clone --recursive https://github.com/quozl/netrek
```

On Debian, Raspbian or Ubuntu, install the dependencies;

```
sudo apt install libtool libgdbm-dev \
	    libx11-dev libxt-dev libxxf86vm-dev \
	    libimlib2-dev libsdl-mixer1.2-dev libsdl1.2-dev
```

Build the game;

```
./build
```

Run the game;

```
./start
```

See [Get Started](https://github.com/quozl/netrek-client-cow/blob/master/README.md#get-started).
