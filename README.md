# docker-jupyter

# 初回
環境を構築する。インストールまでに少し時間がかかります。<br>
`docker build --platform linux/amd64 .`

起動するときは、以下のコマンドを実行する。<br>
`docker run -p 8888:8888`

# 毎回の操作

docker run -p 8888:8888 -v /Users/poclab_macmini/PycharmProjects/docker-jupyter
 --name my-lab d723190a8650

注意事項
Start Docker Desktop when you log in