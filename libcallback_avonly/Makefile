# libcallback.so

CC = /openmiko/build/mips-gcc472-glibc216-64bit/bin/mips-linux-uclibc-gnu-gcc
CFLAGS = -fPIC -std=gnu99 -shared -ldl  -lm
CC_SRCS = video_callback.c
TARGET = libcallback.so audio_callback.c

all: ${TARGET}

${TARGET}: ${CC_SRCS}
	${CC} ${CFLAGS} -o ${TARGET} ${CC_SRCS}
