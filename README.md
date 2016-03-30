# mp4meta

The codes are from AOSP multimedia framework.

## Sample output

```
❯ build/mp4meta ~/qcasting/h264-aac.mp4
welcome using build/mp4meta, version: 0.1.0
mpeg4 file: /Users/akagi201/qcasting/h264-aac.mp4

box: ftyp @ 0 size 24
box: moov @ 24 size 74702
    box: mvhd @ 32 size 108
    box: iods @ 140 size 21
    box: trak @ 161 size 27900
        box: tkhd @ 169 size 92
        box: mdia @ 261 size 27800
            box: mdhd @ 269 size 32
            box: hdlr @ 301 size 115
            box: minf @ 416 size 27645
                box: vmhd @ 424 size 20
                box: dinf @ 444 size 36
                    box: dref @ 452 size 28
                box: stbl @ 480 size 27581
                    box: stsd @ 488 size 185
                        box: avc1 @ 504 size 169
                            box: pasp @ 590 size 16
                            box: avcC @ 606 size 47
                            box: btrt @ 653 size 20
                    box: stts @ 673 size 24
                    box: stss @ 697 size 108
                    box: stsc @ 805 size 2620
                    box: stsz @ 3425 size 22692
                    box: stco @ 26117 size 1944
    box: trak @ 28061 size 46665
        box: tkhd @ 28069 size 92
        box: mdia @ 28161 size 46565
            box: mdhd @ 28169 size 32
            box: hdlr @ 28201 size 55
            box: minf @ 28256 size 46470
                box: smhd @ 28264 size 16
                box: dinf @ 28280 size 36
                    box: dref @ 28288 size 28
                box: stbl @ 28316 size 46410
                    box: stsd @ 28324 size 94
                        box: mp4a @ 28340 size 78
                            box: esds @ 28376 size 42
                    box: stts @ 28418 size 24
                    box: stsc @ 28442 size 52
                    box: stsz @ 28494 size 44288
                    box: stco @ 72782 size 1944
box: mdat @ 74726 size 16955317
box: free @ 17030043 size 55


summary of this presentation
  duration: 236 s
  created at: 2013-08-23 T 02:21:35 .000Z
  last modified at: 2013-08-23 T 02:21:35 .000Z
  has 2 track(s)
    video track info:
      width: 640
      height: 480
    audio track info:
      channels: 2
      sample rate: 48000 Hz
```
