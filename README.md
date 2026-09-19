<div align="center">

<a href="https://aiazzone.github.io"><img src="assets/header.svg" alt="Simone Zuliani" width="100%"></a>

<br><br>

**Chartered electrical engineer who writes desktop software.**<br>
Python and Qt, from the timeline of a video editor to the millisecond a machine has to be told where to reach.

<br>

[![Site](https://img.shields.io/badge/aiazzone.github.io-9ece6a?style=for-the-badge&logo=githubpages&logoColor=0c0e10)](https://aiazzone.github.io)
[![Email](https://img.shields.io/badge/email-24283b?style=for-the-badge&logo=gmail&logoColor=9ece6a)](mailto:simone.engineer@gmail.com)
[![LinkedIn](https://img.shields.io/badge/linkedin-24283b?style=for-the-badge&logoColor=9ece6a)](https://www.linkedin.com/in/simonezuliani/)

</div>

<br>

<img src="assets/divider.svg" alt="" width="100%">

## `~/about`

I started in power — substations, transmission lines, photovoltaic plants — and ended
up writing Python, because the interesting problem stopped being the cable sizing and
became **what the machine knows about the thing in front of it**.

Most of what I build is a desktop application with something demanding on the other
end: a camera at thirty frames a second, a GPU running inference, a PLC that has to
receive a coordinate while it is still true. The engineering is rarely the algorithm.
It is keeping the UI thread off the critical path, discarding what is already stale,
and making sure the program never slows down *in silence*.

I still draw schematics. The two halves talk to each other more than people expect.

<br>

<img src="assets/divider.svg" alt="" width="100%">

## `~/projects`

### [IVE — Individual Video Editor](https://github.com/Aiazzone/IVE-Individual-video-editor)

![status](https://img.shields.io/badge/status-alpha-9ece6a?style=flat-square&labelColor=1a1b26)
![license](https://img.shields.io/badge/license-GPL--3.0-7aa2f7?style=flat-square&labelColor=1a1b26)
![platform](https://img.shields.io/badge/platform-Windows%20%C2%B7%20Linux-bb9af7?style=flat-square&labelColor=1a1b26)

A free, open-source video editor built around a CapCut-style timeline. Two ideas hold
it together.

Every creative asset — colour looks, transitions, export presets, sticker packs — is a
**declarative JSON file** you can copy into a folder and send to a friend. Nothing
executes, so installing content is safe, and nothing sits behind an account.

And every feature of the program is exposed as a typed **Action**, invoked identically
from the interface, from a script, or from an assistant. There is nothing reachable
only by clicking.

- Frame-accurate playback, audio clock driving A/V sync
- Multi-clip timeline — trimming, snapping, real waveforms
- 29 colour looks with live previews on your own footage
- 16 transitions; a wipe is just a greyscale luma map
- Lottie and SVG stickers, composited identically on export
- Titles typed live onto the frame, moved with on-video handles
- Music beds with ducking under speech
- Social export presets — the preview graph renders the file

```
Python  ████████████████████████████████   64.4 %
QML     █████████████████                  35.4 %
GLSL    ▏                                   0.2 %
```

PySide6 / Qt Quick on the surface, FFmpeg through PyAV underneath, an engine modelled
on MLT. Still early: it opens, edits, plays and exports, and it breaks between commits.

<br>

<img src="assets/divider.svg" alt="" width="100%">

## `~/stack`

**Applications**

![Python](https://img.shields.io/badge/Python-24283b?style=for-the-badge&logo=python&logoColor=9ece6a)
![Qt](https://img.shields.io/badge/PySide6%20·%20Qt%20Quick-24283b?style=for-the-badge&logo=qt&logoColor=9ece6a)
![PyInstaller](https://img.shields.io/badge/PyInstaller-24283b?style=for-the-badge&logoColor=9ece6a)

**Media &amp; vision**

![FFmpeg](https://img.shields.io/badge/FFmpeg%20·%20PyAV-24283b?style=for-the-badge&logo=ffmpeg&logoColor=7aa2f7)
![OpenCV](https://img.shields.io/badge/OpenCV-24283b?style=for-the-badge&logo=opencv&logoColor=7aa2f7)
![PyTorch](https://img.shields.io/badge/PyTorch-24283b?style=for-the-badge&logo=pytorch&logoColor=7aa2f7)
![YOLO](https://img.shields.io/badge/YOLO%20·%20Ultralytics-24283b?style=for-the-badge&logoColor=7aa2f7)
![ONNX](https://img.shields.io/badge/ONNX%20·%20TensorRT%20·%20OpenVINO-24283b?style=for-the-badge&logo=onnx&logoColor=7aa2f7)

**Industrial I/O**

![Siemens](https://img.shields.io/badge/Siemens%20S7--1500%20·%20TIA%20Portal-24283b?style=for-the-badge&logo=siemens&logoColor=bb9af7)
![snap7](https://img.shields.io/badge/python--snap7-24283b?style=for-the-badge&logoColor=bb9af7)
![3D](https://img.shields.io/badge/3D%20time--of--flight-24283b?style=for-the-badge&logoColor=bb9af7)

**Electrical design**

![EPLAN](https://img.shields.io/badge/EPLAN%20Electric%20P8%20·%20Pro%20Panel-24283b?style=for-the-badge&logoColor=ff9e64)
![C#](https://img.shields.io/badge/EPLAN%20API%20·%20C%23-24283b?style=for-the-badge&logoColor=ff9e64)
![IEC](https://img.shields.io/badge/NBR%205419%20·%20IEC%2062305-24283b?style=for-the-badge&logoColor=ff9e64)

<br>

<img src="assets/divider.svg" alt="" width="100%">

## `~/background`

| | |
|---|---|
| `2014 —` | Senior electrical designer &amp; software developer — beverage-industry machinery |
| `2012 – 2014` | Electrical engineer, high-voltage substations |
| `2010 – 2012` | Design engineer, photovoltaic plants &amp; building systems |
| `2009 – 2010` | Research internship — magnetic-field assessment algorithm for city substations |
| `2011` | Chartered engineer — Ordine degli Ingegneri |
| `2007 – 2010` | MSc Electrical Engineering — Università degli Studi di Padova |
| `2003 – 2007` | BSc Energy Engineering — Università degli Studi di Padova |
| `1998 – 2003` | Perito elettrico — I.T.I.S. G. Ferraris |

<br>

<div align="center">
<img src="assets/divider.svg" alt="" width="100%">
<br><br>
<sub>Italian &amp; Portuguese (native) · English · Spanish &nbsp;•&nbsp; NR-10 certified</sub>
</div>
