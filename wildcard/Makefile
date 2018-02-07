 objects := $(patsubst %.c,%.o,$(wildcard *.c))
 objects += $(patsubst %.c,%.o,$(wildcard dir0/*.c))
 foo : $(objects)
	@echo "echo >>>>>>"
	@echo $(ojbects)
	@echo ${ojbects}
	@echo "echo <<<<<<"

#$ ls
#Makefile a.c      b.c
#$ make
#cc    -c -o a.o a.c
#cc    -c -o b.o b.c
#echo >>>>>>
#
#echo <<<<<<
#$ ls
#Makefile a.c      a.o      b.c      b.o
