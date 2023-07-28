# Create_CPP_project
test to build a cpp project.


##方法1
g++ -o main main.cpp hello/hello.cpp world/world.cpp -I ./world



##方法2
g++ -c main.cpp -I ./world
g++ -c hello/hello.cpp
g++ -c world/world.cpp
g++ -o main main.o hello.o world.o




