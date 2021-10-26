# elrond-qrcode-generator
Elrond Qrcode generator hosted on `qrcodegen.eu`.

Usage example :
http://qrcodegen.eu/?text=erd999gdf7dvxs9g65g7krrg6xq9degscqkwe2h0xmbfke48vtb5ubwpx8f594


## Run it
```
# for local use on 8080 (source : https://gist.github.com/willurd/5720255)
python -m SimpleHTTPServer 8080

# with caddy for https
cd ~/workspace/elrond-qrcode-generator; nohup caddy file-server --domain qrcodegen.eu > ~/workspace/elrond-qrcode-generator/output.log 2>&1 &

```

