 # Universidad de Los Andes
 # Sincronizacion de procesos
 # Asignatura: Sistemas Operativos
 # Autor: Alvaro Araujo
 # Fecha: 20/04/2018

CC  = gcc
INC =
OPC = -g -c
LIB =
LIBH = -pthread
EXECUTABLES = programa1.out programa2.out

.c.o:
	$(CC) $(OPC) $(INC) $<

all: $(EXECUTABLES)

programa1.out: programa1.o
	$(CC) -o $@ $< $(LIB)

programa2.out: programa2.o
	$(CC) -o $@ $< $(LIB)

clean:
	rm -fr *~ *.o $(EXECUTABLES)
