# WebMSX Container

> [!NOTE]
> Forked from [ppeccin/WebMSX](https://github.com/ppeccin/WebMSX)


## Configuration

- Put ROM file(*.rom) you want to play into roms/ directory 

- Set `WMSX.CARTRIDGE1_URL` to your ROM file(*.rom) (index.html)


## Run

```bash
docker build -t webmsx-container .
docker run -d -p 8080:80 webmsx-container
```
