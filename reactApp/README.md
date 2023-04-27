##Reactの環境
ディレクトリ内で
```
docker compose build
docker compose run --rm react-app sh -c "npm install -g create-react-app && create-react-app sample-app"
docker compose up -d
```
logをみるには
```
docker compose logs -f
```