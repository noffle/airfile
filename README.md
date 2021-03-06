# airfile

> Painlessly transfer files from a web browser to your local machine.

Airfile was designed specifically to make it easier to get data off my android
phone to my laptop without needing a native application, cloud services, or a
USB cable.

## Usage

In a directory of your choosing, run `airfile`:

```
> airfile
Listening on 192.168.0.123:8400
```

Point your phone's web browser to this address. You'll be greeted with an
interface that lets you select files from your phone and send them.

These files are sent one by one to your local machine, saving them locally in
the directory you ran `airfile` in.

**Caveat**: I've found Chrome to work best with allowing multi-select of photos.
Make sure you select `Documents` as the place to choose photos from. Firefox
didn't seem to let me do multi-select.

## Install

With [npm](https://npmjs.org/) installed, run

```
$ npm install --global airfile
```

## License

ISC
