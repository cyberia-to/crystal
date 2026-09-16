---
tags: cyb, cyber, core
alias: video particle, moving image, recording, temporal pixels
crystal-type: entity
crystal-domain: cyb
---
temporal [[pixels]] — the physical world unfolding over time as [[file]]. the native format for recordings, experiments, lectures, and any knowledge that requires a sequence of frames

source format: WebM, MP4 — any video container with hardware-decodable codec

---

## rendering

```
video file → hardware decode (GPU/NPU) → frame texture per block → temporal sampler → fragment shader
```

hardware decoding offloads the codec to dedicated silicon. the decoded frame uploads as a GPU texture per displayed block. playback, seek, and scrub operate at native speed. the robot plays a 4K video on the same pipeline as a 360p recording — hardware handles the resolution, the pipeline handles the display

## in the cybergraph

video is the highest-bandwidth truth in the graph. the lecture, the experiment, the species behavior, the physical process — some knowledge only exists as sequence. when video becomes a file, every frame is potentially a [[cyberlink]] target

types of video files: scientific experiment recordings, species behavior observations, surgical procedures, lecture recordings, protein folding simulations, astronomical events (supernova, pulsar), physical phenomena (fluid dynamics, crystallization), historical events, sensor array recordings, drone surveys, clinical trial documentation, machine behavior in testing

a video file is timestamped evidence at its highest resolution. the observation that no verbal description can replace

## properties

- seekable by block height — video files in the [[cybergraph]] can be linked with timestamp offsets. a [[cyberlink]] can reference a specific moment: "this claim begins at 4:32 in this file"
- chapter-linkable — the [[cybergraph]] treats video chapters as addressable sub-files, enabling section-level citation of long recordings
- transcript-paired — a video file commonly has a [[text]] file paired by [[cyberlink]] containing its transcript. the robot renders both together: synchronized text and video
- the most expensive file — video files are large. [[karma]] earned by valuable video files is proportionally significant. the incentive structure favors high-signal recordings over low-signal ones

## relation to other languages

video is pixels made temporal. [[pixels]] is the individual frame; video is the sequence. [[sound]] is often the acoustic component of the same event — a video file and a sound file may link to the same underlying event. [[text]] annotates what video shows

see [[pixels]] for single-frame content. see [[sound]] for acoustic knowledge. see [[component]] for interactive video players with synchronized annotation

discover all [[concepts]]
