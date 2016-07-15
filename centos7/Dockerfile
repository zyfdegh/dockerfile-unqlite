FROM centos:7

COPY libunqlite.so.1.0 /usr/local/lib/
COPY unqlite.h /usr/local/include/
RUN ln -sf /usr/local/lib/libunqlite.so.1.0 /usr/local/lib/libunqlite.so.1
RUN ln -sf /usr/local/lib/libunqlite.so.1 /usr/local/lib/libunqlite.so
RUN ldconfig /usr/local/lib/libunqlite.so
