# colab-katago-gd

This program has been modified from the original colab-katago to store SSH information on Google Drive.

See how to use:   

**English Version**  
[colab_katago_gd_en.ipynb](https://colab.research.google.com/github/mildinvestor/katago-colab/blob/master/colab_katago_gd_en.ipynb)

**Japanese Version(colab_katago_gd_en.ipynbの使い方紹介)**  
[【無料GPU】囲碁AI KataGoをGoogle Colaboratory上で動かす方法](https://mildinvestor.com/2021/08/26/katago-on-google-colaboratory/)

# Build
```
GOOS=darwin GOARCH=amd64 go build -o ./bin/colab-katago-for-mac 
GOOS=linux GOARCH=amd64 go build -o ./bin/colab-katago-for-linux
GOOS=windows GOARCH=amd64 go build -o ./bin/colab-katago-for-windows
```

See how to build:

This notebook contains examples of how to build colab-katago-gd and KataGo, and how to create KataGo's tuning files.  
[build_colab_katago_gd.ipynb](https://colab.research.google.com/github/mildinvestor/katago-colab/blob/master/build_colab_katago_gd.ipynb)
