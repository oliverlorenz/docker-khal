# docker-khal
a dockerized hkal WITHOUT any synchronize backend. If you want to synchronize with a CalDAV Server I recommend [vdirsyncer](https://github.com/pimutils/vdirsyncer)

## usage

### interactive mode (default)

```
docker run -it -v $PWD/config:/root/.config/khal/config -v /path/to/vdirsyncer/calender/directory:/data khal
```
