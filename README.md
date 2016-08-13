# Python-AES-module
For python AES C module, for speed

### You can use the command `gcc aes.c -fPIC -I /usr/include/python2.7 -shared -o aes.so` to make it

And in you python file, `import aes` to import the `so` file

There have to function in this module
* aes.aes(key, into)
* aes.inv_aes(key, out)

aes.aes() function is for the encryption

and the aes.inv_aes is for the decrypt

## Attention

the `key` length must be the `32bit`, and the `into` and `out` must be the `16bit`

and here have a example

![example](https://github.com/SuperSuperSuperSuper5/Python-AES-module/blob/master/p1.jpg)
