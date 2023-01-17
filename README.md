# dancode
Password encoding/decoding for all files. (lossless)

# usage
ENCODING
________
Import the module and use: dancode.dancode('foo/bar/file.xxx')

It will first prompt you to set a password, you can use any text.

Next, it will store the file as "file.xxx.dancode".

Finally, it will ask if you want to delete the origional file.


DECODING
________
Import the module and use: dancode.dancode('foo/bar/file.xxx.dancode')

It will first prompt you to enter the password you set earlier.

Next, it will store the file as "file.xxx".

Finally, it will ask if you want to delete the origional file.

