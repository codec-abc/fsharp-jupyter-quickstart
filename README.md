# fsharp-jupyter-quickstart


```bash
wget https://raw.githubusercontent.com/fsprojects/IfSharp/master/Dockerfile
docker build -t jupyterfsharp .
docker run -p 8888:8888 -v //p:/home/fs jupyterfsharp --notebook-dir=/home/fs
```
