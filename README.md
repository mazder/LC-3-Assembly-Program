# LC-3-Assembly-Program

```
wget http://highered.mcgraw-hill.com/sites/dl/free/0072467509/104652/lc3tools_v12.zip
unzip lc3tools_v12.zip
cd lc3tools
./configure --installdir /usr/local/bin
make LDFLAGS=-lreadline USE_READLINE=-DUSE_READLINE
sudo make install
rm -rf ~/lc3_install

```