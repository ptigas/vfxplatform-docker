# vfxplatform-docker

Docker container for [CY2018 VFX Reference Platform](http://www.vfxplatform.com).

<br><br>

## Build info

If there's no version specified, the application has not yet been added to the Dockerfile/image. Feel free to create a PR! :smile:


|        | gcc   | glibc | python | Qt    | PyQt | PySide           | NumPy | OpenEXR | Ptex | OpenSubdiv | OpenVDB | Alembic | FBX | OpenColorIO | ACES | Boost | Intel TBB | Intel MKL | C++ API/SDK |
| ------ | ----- | ----- | ------ | ----- | ---- | ---------------- | ----- | ------- | ---- | ---------- | ------- | ------- | --- | ----------- | ---- | ----- | --------- | --------- | ----------- |
| CY2018 | 5.3.1 | 2.17  | 2.7.5  | 5.6.1 |      | 2.x (5.6 branch) | 1.12.1| 2.2.0   |      |            |  5.0.0  |         |     |             |      | 1.61.0| 2017 update 6 |       |   C++14     |


<br><br>

## Try it

```bash
docker run --rm -ti fredrikaverpil/vfxplatform:[TAG] bash
```

<br><br>
