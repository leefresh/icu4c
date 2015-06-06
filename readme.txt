# Using msys with Rtools 3.2 (gcc 4.6.3)
CLFAGS="-m64" CXXFLAGS="-m64" ./configure --enable-release --disable-rpath --disable-shared --enable-static

make -j8
