# Awesome Broadcasting [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
A curated list of amazingly awesome open source resources for broadcasters.

* [Awesome Broadcasting](#awesome-broadcasting)
  * [Audio over IP](#audio-over-ip)
  * [Codecs](#codecs)
  * [Companion Screens](#companion-screens)
  * [Connected TVs](#connected-tvs)
  * [Distributed Media Processing](#distributed-media-processing)
  * [DVB & WiFi](#dvb--wifi)
  * [Graphics & Video Playout](#graphics--video-playout)
  * [Hybrid Radio](#hybrid-radio)
  * [Media Players](#media-players)
  * [Metadata](#metadata)
  * [Multimedia content processing](#multimedia-content-processing)
  * [Network & Storage Testing](#network--storage-testing)
  * [Quality Control](#quality-control)
  * [Radio Production](#radio-production)
  * [Software-defined radio](#software-defined-radio)
  * [Subtitling](#subtitling)
* [Resources](#resources)
  * [Blogs](#blogs)
  * [Websites](#websites)
* [Contributing](#contributing)

<!-- This page is available on http://ebu.io/opensource -->
## Audio over IP

* [Kamailio](http://www.kamailio.org/) - Open SIP server. Commonly used SIP server for Audio contribution over IP using SIP (EBU ACIP)
* [PJSIP](http://www.pjsip.org/) - Open Source multimedia library implementing SIP, SDP, RTP, STUN, TURN, and ICE. Used in some contribution equipment (dual licensing).
* [OpenOB](https://jamesharrison.github.io/openob/) - Open Outside Broadcast project for radio contribution links and studio-transmitter links based on Opus.

## Codecs

* [Opus](http://www.opus-codec.org) - Opus is a totally open, royalty-free, highly versatile audio codec. 
* [FLAC](https://www.xiph.org/flac/) - FLAC Free Lossless Audio Coding. Used by some broadcaster for audio exchange, storage.
* [Lame](http://lame.sourceforge.net/) - Lame, high quality MPEG Audio Layer III (MP3) encoder. (Warning, MP3 is not royalty free!)
* [TwoLame](http://www.twolame.org/) - TwoLame, MPEG Audio Layer 2 (MP2) encoder.
* [Turing Codec](http://turingcodec.org/) - Turing codec, an H.265/HEVC open source software encoder designed for fast and efficient video compression.

## Companion Screens

* [dvbcss-synctiming](https://github.com/BBC/dvbcss-synctiming) - dvbcss-synctiming is a system for measuring how accurately a TV or companion are synchronised.
* [pydvbcss](https://github.com/BBC/pydvbcss) - pydvbcss is library implementing the DVB Companion Screens and Streams protocols for accurately synchronising media playback between TVs and companions.

## Connected TVs

* [Cross-Platform Authentication](http://ebu.io/project/cpa) - CPA offers an open standard for associating any media device with an online identity.
* [HbbPlayer](https://github.com/Samsung/HbbPlayer) - An HbbTV application which can playback media from a URL. Conforms to HbbTV and W3C specifications.
* [TAL](http://fmtvp.github.io/tal) - The TV Application Layer (TAL) is an open source library for building applications for Connected TV devices.

## Distributed Media Processing

* [StormCV](https://github.com/sensorstorm/StormCV) - Apache Storm + OpenCV = large scale distributed image and video analysis.

## DVB & WiFi

* [DTT 2 IP](https://github.com/ebu/dtt2ip) - Broadcast to IP conversion for Wifi indoor coverage.
* [DVB Inspector](https://sourceforge.net/projects/dvbinspector/) - DVB Inspector is an open-source DVB analyzer.
* [DVBlast](http://www.videolan.org/projects/dvblast.html) - DVBlast is a simple and powerful MPEG-2/TS demux and streaming application.
* [Opencaster](http://www.avalpa.com/the-key-values/15-free-software/33-opencaster) - OpenCaster is a free and open source MPEG2 transport stream data generator and packet manipulator.
* [WiFiBroadcast](https://befinitiv.wordpress.com/wifibroadcast-analog-like-transmission-of-live-video-data/) - Analog-like transmission of live video data.

## Graphics & Video Playout

* [Aurena](https://github.com/thaytan/aurena) - Aurena is a network distributed media playback system.
* [CasparCG](http://www.casparcg.com/) - CasparCG is a professional graphics and video play-out software, proven in 24/7 broadcasts since 2006
* [i-Score](http://i-score.org/) - A free and open-source intermedia sequencer

## Hybrid Radio

* [RadioDNS Manager](https://github.com/ebu/radiodns-plugit) - A platform to manage Hybrid Radio static services such as RadioVIS, RadioEPG and Service Following.
* [RadioTag.js](https://github.com/ebu/radiotag.js) - RadioTag client library in JavaScript.
* [RadioVIS Html Player](https://github.com/ebu/radiovis-html5player) - RadioVIS Player using WebSocket.
* [RadioVIS Demo](https://github.com/bbcrd/RadioVisDemo) - RadioVIS client application in Python.

## Media Players

* [Dash.js](https://github.com/ebu/dash.js) - A reference client implementation for the playback of MPEG DASH via Javascript and compliant browsers.
* [Kodi](https://github.com/xbmc/xbmc) - A software media player and entertainment hub for digital media.
* [Media4DPlayer](https://github.com/ebu/media4Dplayer) - HTML5 player focused on accessibility.
* [Peaks.js](http://waveform.prototyping.bbc.co.uk/) - Browser-based audio waveform visualisation.
* [VLC](http://www.vlc.org) - Simple, fast and powerful media player. 
* [GPAC](http://gpac.wp.mines-telecom.fr/home/) - Multimedia player, packager and tools
* [rx-player](https://github.com/canalplus/rx-player) - HTML5/Javascript video player with some reactive programming inside, supporting MPEG-DASH and SmoothStreaming transports.

## Metadata

* [BMXlib](http://sourceforge.net/projects/bmxlib/) - Library and utilities to read and write broadcasting media files. Primarily supports the MXF file format.
* [EBUCore](https://github.com/ebu/ebucore) - the Github for maintenance of the [EBUCore schema](https://tech.ebu.ch/docs/tech/tech3293.pdf).
* [jebu-core](https://github.com/mikrosimage/jebu-core) - EBUCore XML Schema Java port. Java port of [TECH 3293](https://tech.ebu.ch/publications/tech3293) EBU CORE METADATA SET (EBUCore) SPECIFICATION v. 1.5, including new [Audio Definition Model](https://tech.ebu.ch/docs/tech/tech3364.pdf).
* [Ledger](https://github.com/Streampunk/ledger) - Node.js implementation of the NMOS registration and discovery specifications.
* [MAJ API](https://github.com/AMWA-TV/maj) - Pure Java library for reading and writing MXF and AAF files.
* [TV-Anytime](https://github.com/ebu/tvanytime) - The tv-anytime schema github maintenance page.

## Multimedia content processing

* [AvTranscoder](https://github.com/avTranscoder/avTranscoder) - Based on FFmpeg/LibAV libraries to support various video and audio formats, avTranscoder provides the high level API to re-wrap or transcode media easily. It also provide bindings for any usage in Java or Python.
* [Bento4](https://github.com/axiomatic-systems/Bento4) - Full-featured MP4 format and MPEG DASH C++ class library and tools.
* [Codem-isoboxer] (https://github.com/madebyhiro/codem-isoboxer) A small browser-based MPEG-4 (ISOBMFF) parser.
* [Dynamorse](https://github.com/Streampunk/dynamorse) - IT swiss army knife - a Node-RED media pipeline builder, adding professional media processing nodes.
* [FFmpeg](http://ffmpeg.org) - A complete, cross-platform solution to record, convert and stream audio and video.
* [FFmbc](https://code.google.com/p/ffmbc/) - FFmpeg customized for broadcast and professional usage.
* [GStreamer](https://gstreamer.freedesktop.org/) - A library for constructing graphs of media-handling components.
* [KFR](https://www.kfrlib.com/) - Fast, modern C++ DSP framework, DFT/FFT, Audio resampling, FIR/IIR, Biquad.
* [L-SMASH](https://github.com/l-smash/l-smash/) - A rigidly spec-compliant ISOBMFF library, which has full DASH muxing support.
* [LibAV](https://libav.org/) - Open source audio and video processing tools.
* [Libebur128](http://github.com/jiixyj/libebur128) - A library that implements the EBU R 128 standard for loudness normalisation.
* [Loudness Validator](https://github.com/mikrosimage/loudness_validator) - A set of applications to analyse, visualise and correct the loudness.
* [MP4Box.js](https://github.com/gpac/mp4box.js) - JavaScript library to process MP4 files in the browser (and in NodeJS).
* [MXFLib](http://sourceforge.net/projects/mxflib) - A multi-platform C++ library for reading and writing MXF files.
* [Open Broadcast Encoder](https://github.com/ob-encoder) - Broadcast encoder built from Open Source components.
* [Photon](https://github.com/Netflix/photon) - Implementation of the SMPTE Material Exchange Format (MXF) file specification.
* [SoX](http://sox.sourceforge.net/) - The Swiss Army knife of sound processing programs. 
* [TuttleOFX](http://www.tuttleofx.org/) - TuttleOFX is an open source image processing framework based on OpenFX plugin standard.
* [UPipe](https://github.com/cmassiot/upipe/) - Upipe is primarily designed to be the core of a multimedia player, transcoder or streamer.
 
## Network & Storage Testing

* [BBC Media Storage Meter](http://sourceforge.net/projects/msmeter/) - An application for the testing of network attached storage, originally assumed to be used for the streaming of professional media.

## Quality Control

* [BeaqleJS](https://github.com/HSU-ANT/beaqlejs) - BeaqleJS provides a framework to create browser based listening tests for subjective audio quality assessment.
* [MediaConch](https://mediaarea.net/MediaConch/) - Implementation checker, policy checker, & reporter for Matroska, FFV1, & PCM.
* [MediaInfo](https://mediaarea.net/en/MediaInfo) - MediaInfo provides a convenient unified display of the most relevant technical and tag data for video and audio files.
* [MXF Inspect](http://www.myriadbits.com/) - A Windows tool to display the internal structure of an MXF (Material eXchange Format) file.
* [QCTools](https://github.com/bavc/qctools) - Quality Control tools for video preservation to analyse digitized video files
* [Sonic Visualiser](http://www.sonicvisualiser.org/) - An application for viewing and analysing the contents of music audio files.
* [VMAF](https://github.com/Netflix/vmaf) - Perceptual video quality assessment based on multi-method fusion.
* [Wisual](https://github.com/MarcAntoine-Arnaud/wisual) - A web service for Visual Quality Assessment, which supports PSNR, SSIM, VQM, etc.

## Radio Production

* [Audacity](http://audacity.sourceforge.net/) - Cross-platform software for recording and editing sounds
* [Airtime](https://www.sourcefabric.org/en/airtime/) - Radio management application for remote broadcast automation (via web-based schedule)
* [Rivendell](http://www.rivendellaudio.org/) - Complete radio broadcast automation solution, translated to many languages and used worldwide. 

## Software-defined radio

* [CRC mmbTools](http://mmbtools.crc.ca/) - Original Tools for DAB digital radio multiplexing and software defined radio modulation.
* [ODR mmbTools](http://www.opendigitalradio.org) - Fork, continuation of CRC mmbTools. Adding new features for 24/24 365/365 live operation, DAB+, associated data (slideshow, text), distributed infrastructure, SFN.

## Subtitling

* [CCExtractor](http://ccextractor.sourceforge.net/about-ccextractor.html) - A tool that analyzes video files and produces stand-alone subtitle files.
* [GStreamer TTML subtitling package](https://github.com/bbc/gst-ttml-subtitles) - A means for GStreamer pipelines to parse and render  EBU-TT-D (TTML) subtitles. 
* [EBU-TT-D Subtitling within dash.js](https://github.com/ebu/dash.js/tree/ebu-subtitling-dev) - The original fork of dash.js to experiment with XML based subtitles like EBU-TT-D within dash.js. Uses an HTML/CSS overlay. Has since been integrated into [dash.js](https://github.com/ebu/dash.js).
* [EBU-TT-D W3C XML Schema](https://github.com/ebu/ebu-tt-d-xsd/) - Informative EBU-TT-D XML Schema to support the implementation of EBU Tech 3380.
* [EBU-TT Live Interoperability Toolkit](https://github.com/ebu/ebu-tt-live-toolkit) - A set of components for generating, testing and distributing subtitle documents in the [EBU-TT Live](https://tech.ebu.ch/publications/tech3370) format.
* [imscJS](https://github.com/sandflow/imscJS) - JavaScript library for rendering IMSC1 Text and Image Profile documents to HTML5.
* [IRT EBU-TT-D Application Samples](https://github.com/IRT-Open-Source/irt-ebu-tt-d-application-samples) - EBU-TT-D sample files, related PNG images and mp4 videos showing how they should be rendered.
* [Subtitling Conversion Framework (SCF)](https://github.com/Irt-Open-Source/scf) - A set of modules for converting subtitle formats. Main target is the conversion of EBU STL and EBU-TT subtitle files. Alpha release.
* [Timed Text Toolkit (ttt)](https://github.com/skynav/ttt) - A collection of related tools that provide support for or make use of the W3C Timed Text Markup Language (TTML).

# Resources
Various resources, such as books, websites and articles, for improving your skills and knowledge.

## Blogs

* [BBC R&D](http://bbc.co.uk/rd) - BBC Research and Development. Checkout the weekly notes.
* [3D CineCast](http://3dcinecast.blogspot.ch/) - A curation about new media technologies.
* [Canal+](http://canalplus.github.io/) - CANAL+ Open Source Community.
* [The Netflix Tech Blog](http://techblog.netflix.com/) - A Netflix blog focused on technology and technology issues.
* [Youtube Engineering and Developers Blog](http://youtube-eng.blogspot.com) - What's happening with engineering and developers at YouTube.

## Websites
*Useful broadcasting related websites.*

* [EBU.io](http://www.ebu.io) - A platform for agile collaboration.

<!-- This page is available on http://ebu.io/opensource -->

# Contributing
Please see [CONTRIBUTING](https://github.com/ebu/awesome-broadcasting/blob/master/CONTRIBUTING.md) for details.
