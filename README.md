# httpsqs
HTTPSQS is a Simple Queue Service based on HTTP GET/POST protocol. 

# Discription
This is another fork of Zhangyan(张宴)'s work, which is originally in [google code](https://code.google.com/p/httpsqs/).

### why fork?
In my work I find this useful, yet I don't think the interfaces standard.
e.g.
```
http://127.0.0.1:1218/?name=sequence_name&opt=put&data=urlencodedcontenthere'
```
The interfaces I can get in touch with are always like this
```
http://127.0.0.1:1218/put?name=sequence_name&data=urlencodedcontenthere'
```
I will try my best to make this another master piece.
