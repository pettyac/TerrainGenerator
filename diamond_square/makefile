#------------------------------------------------------------------------------
# Makefile for main.exe
# Adam Petty
#------------------------------------------------------------------------------
# Macros
#------------------------------------------------------------------------------
CXX 	= g++
CXXFLAGS = -g -Wall
LINK 	= g++
LINKFLAGS = -lGL -lGLU -lglut -lGLEW
OBJS 	= mygllib3d/config.o mygllib3d/reshape.o mygllib3d/SingletonView.o \
	  mygllib3d/Keyboard.o main.o
EXE	= main.exe

#------------------------------------------------------------------------------
# Executable
#------------------------------------------------------------------------------
$(EXE):	$(OBJS)
	$(LINK) $(OBJS) -o $(EXE) $(LINKFLAGS)

#------------------------------------------------------------------------------
# Object files
#------------------------------------------------------------------------------
main.o:	main.cpp
	$(CXX) $(CXXFLAGS) main.cpp -c -o main.o 

#------------------------------------------------------------------------------
# Utilities
#------------------------------------------------------------------------------
clean: 
	rm -f $(EXE) main.o
c: 
	rm -f $(EXE) main.o
run:
	./$(EXE)
r:
	./$(EXE)
