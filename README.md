# HTC Vive Lighthouse — Position Sensing

Building a position sensor for the 1st generation of HTC Vive's Lighthouse tracking system.

A work in progress.

## Cloning the repository

This repo uses [Git LFS](https://git-lfs.github.com/) for tracking large files such as images and signal waveform logs (CSV). To clone it, use a regular `git clone` when Git LFS is installed:

```console
$ git clone git@github.com:sunsided/lighthouse.git
```

## Directory structure

- `docs/` contains papers, datasheets and other documents,
- `fritzing/` contains Fritzing schematics for the sensor board
- `measurements/` contains sensor measurements from both a Saleae Logic analyzer and a Rigol DS1104Z scope
- `simulation/` contains Jupyter Notebooks for working out the details

## Source material

### Blogs posts and articles

- [HTC vive lighthouse custom tracking](https://hackaday.io/project/19570-htc-vive-lighthouse-custom-tracking) on Hackaday.io
- [Homebrew interface for the HTC v1 Lighthouses](https://trmm.net/Lighthouse/)
- [Lighthouse tracking examined](http://doc-ok.org/?p=1478)
- [SteamVR HTC Vive in-depth: Lighthouse Tracking System dissected and explored](https://pcper.com/2016/04/steamvr-htc-vive-in-depth-lighthouse-tracking-system-dissected-and-explored/)
- [DAC with DMA and buffer on a Teensy 3.2](https://hackaday.io/project/12543-solid-state-flow-sensing-using-eis/log/41575-dac-with-dma-and-buffer-on-a-teensy-32)
- [Alan Yates: Why Valve's Lightouse can't work](https://hackaday.com/2016/12/21/alan-yates-why-valves-lighthouse-cant-work/)

### GitHub Respositories

- [DIY Position Tracking using HTC Vive's Lighthouse](https://github.com/widemeadows/vive-diy-position-sensor) (the sensor board)
- [Unofficial Documentation for the Lighthouse Tracking System](https://github.com/widemeadows/LighthouseRedox)

### 3D Printing

- [IR Receiver mount for 3x BPV22NF](https://www.thingiverse.com/thing:2686995) (the diode holder used on the sensor board)

### YouTube

- [HTC Vive Lighthouse Chaperone tracking system Explained](https://www.youtube.com/watch?v=J54dotTt7k0)
- [The Secret Prototypes of Valve's VR Lab](https://www.youtube.com/watch?v=QLBxz7djQvc)