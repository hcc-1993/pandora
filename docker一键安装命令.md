## docker一键安装命令

### 一键安装命令

1. 第一步

   ```shell
   docker pull pengzhile/pandora
   ```

2. 第二步

   ```shell
   docker run  -e PANDORA_CLOUD=cloud -e PANDORA_SERVER=0.0.0.0:8899 -p 8899:8899 -d pengzhile/pandora
   ```

   

