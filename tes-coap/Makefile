all:
	gcc coap_list.c cmdline.c client_misc.c main.c -I /usr/local/include/coap/ -O2 -D_GNU_SOURCE -DWITH_POSIX -lcoap-1 -g -o tes
client-asli:
	gcc coap_list.c client-asli.c -I /usr/local/include/coap/ -O2 -D_GNU_SOURCE -DWITH_POSIX -lcoap-1 -g -o client-asli
