# cgdb cross compile config
this is a cgdb cross-compile configure option

# configure script option
../configure --prefix=`pwd`/usr --host=arm-linux-gnueabihf --enable-static --with-readline='/home/briq/work/src/readline-8.0/build/usr' --with-ncurses='/home/briq/win/d/work/src/ncurses-6.1/build/usr' CFLAGS='-I /home/briq/win/d/work/src/ncurses-6.1/build/usr/include -I /home/briq/work/src/readline-7.0/build/usr/include' CPPFLAGS='-I /home/briq/win/d/work/src/ncurses-6.1/build/usr/include' ac_cv_file__dev_ptmx=no ac_cv_file__proc_self_status=no ac_cv_func_setpgrp_void=no ac_cv_rl_version='8.0' LDFLAGS='-static'

# libncurses config 
./configure --prefix=`pwd`/usr --host=arm-linux-gnueabihf --enable-static --without-ada LDFLAGS='-static'

# readline config
../configure --prefix=`pwd`/usr --host=arm-linux-gnueabihf --enable-static --disable-shared LDFLAGS='-static' CFLAGS='-fPIC'
