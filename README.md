# GitHub Actions Exercise

An exercise for 'DevOps and SRE' on HTW Berlin

![Image of a kangaroo](https://static.spreeradio.de/img/7679/388291/351000/Img_2_1/1440/die_kaenguru_chroniken-plakat.jpg)

## Test

```bash
go test ./...
```

## Build

```bash
docker build . -t my-app
```

## Run

```bash
docker run -p 8080:8080 my-app
```
