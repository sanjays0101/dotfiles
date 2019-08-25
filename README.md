# dotfiles

udo ./configure --with-features=huge \
--enable-multibyte \
--enable-pythoninterp=yes \
--with-python-config-dir=/usr/local/bin/python2.7/ \  # pay attention here check directory correct
--enable-python3interp=yes \
--with-python3-config-dir=/usr/local/bin/python3.7/ \  # pay attention here check directory correct
--enable-gui=gtk2 \
--enable-cscope \
--prefix=/usr/local/

