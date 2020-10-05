# clang_dev
C言語開発環境 on docker

## Usage
```bash
git clone https://github.com/mitty1293/clang_dev.git
cd clang_dev
docker-compose up -d
```

## Sample
コンテナ内の `/home/work` にサンプルプログラムを格納済です。
```bash
gcc sample.c
./a.out
```