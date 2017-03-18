main.o: bird.cc birdlist.cc bird.h birdlist.h
        cc -c bird.cc birdlist.cc

bird.o: bird.c bird.h
        cc -c bird.cc

birdlist.o: birdlist.cc birdlist.h
            cc -c birdlist.cc
