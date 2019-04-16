# Awesome Broadcasting [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
A curated list of amazingly awesome open source resources for broadcasters.

* [Awesome Broadcasting](#awesome-broadcasting)
  * [Codecs](#codecs)
  * [Companion Screens](#companion-screens)
  * [Connected TVs](#connected-tvs)
  * [Distributed Media Processing](#distributed-media-processing)
  * [Documentation](#documentation)
  * [DVB & WiFi](#dvb--wifi)
  * [Animation, Graphics & Video Playout](#animation-graphics--video-playout)
  * [Hybrid Radio](#hybrid-radio)
  * [LiveIP](#liveip)
  * [Media Players](#media-players)
  * [Metadata](#metadata)
  * [Monitoring & Quality Control](#monitoring--quality-control)
  * [Multimedia content processing](#multimedia-content-processing)
  * [Network & Storage Testing](#network--storage-testing)
  * [Radio Production](#radio-production)
  * [Software-defined radio](#software-defined-radio)
  * [Subtitling](#subtitling)
  * [Video Production](#video-production)
* [Resources](#resources)
  * [Blogs](#blogs)
  * [Websites](#websites)
* [Contributing](#contributing)

<!-- This page is available on http://ebu.io/opensource -->
## Codecs

* [FLAC](https://www.xiph.org/flac/) - Free Lossless Audio Coding, used by some broadcasters for audio exchange, storage.
* [Lame](http://lame.sourceforge.net/) - A high quality MPEG Audio Layer III (MP3) encoder.
* [opencore-amr](https://sourceforge.net/projects/opencore-amr/) - Audio codecs extracted from Android Open Source Project, including AAC.
* [Opus](http://www.opus-codec.org) - A totally open, royalty-free, highly versatile audio codec.
* [Turing Codec](http://turingcodec.org/) - An H.265/HEVC open source software encoder designed for fast and efficient video compression.
* [TwoLame](http://www.twolame.org/) - An MPEG Audio Layer 2 (MP2) encoder.

## Companion Screens

* [dial-discovery-ios](https://github.com/bbc/dial-discovery-ios) - A library for the discovery of devices via the DIAL protocol on the iOS platform.
* [dvbcss-synckit-ios](https://github.com/bbc/dvbcss-synckit-ios) - iOS libraries for companion screen applications that are synchronised frame-accurately to a TV.
* [dvbcss-synctiming](https://github.com/BBC/dvbcss-synctiming) - A system for measuring how accurately a TV or companion are synchronised.
* [pydvbcss](https://github.com/BBC/pydvbcss) - Implementation of the DVB Companion Screens and Streams protocols for synchronised media playback.

## Connected TVs

* [Cross-Platform Authentication](http://ebu.io/project/cpa) - CPA offers an open standard for associating any media device with an online identity.
* [HbbPlayer](https://github.com/Samsung/HbbPlayer) - An HbbTV and W3C specifications compliant application that can playback media from a URL.
* [TAL](http://bbc.github.io/tal/) - The TV Application Layer (TAL) is an open source library for building applications for Connected TV devices.

## Distributed Media Processing

* [StormCV](https://github.com/sensorstorm/StormCV) - Apache Storm + OpenCV = large scale distributed image and video analysis.

## Documentation

* [Kronekeeper](https://github.com/nick-prater/kronekeeper) - A web based application for recording and managing Krone frame records.

## DVB & WiFi

* [DTT 2 IP](https://github.com/ebu/dtt2ip) - Broadcast to IP conversion for Wifi indoor coverage.
* [DVB Inspector](https://sourceforge.net/projects/dvbinspector/) - An open-source DVB analyzer.
* [DVBlast](http://www.videolan.org/projects/dvblast.html) - A simple and powerful MPEG-2/TS demux and streaming application.
* [dvbshout](https://github.com/njh/dvbshout) - Tool to send DVB audio to a shoutcast server or a RTP stream.
* [Opencaster](http://www.avalpa.com/the-key-values/15-free-software/33-opencaster) - A free and open source MPEG2 transport stream data generator and packet manipulator.
* [Project X](https://sourceforge.net/projects/project-x/) - DVB demux tool.
* [ts2mpa](https://github.com/njh/ts2mpa) - Simple tool to extract MPEG Audio from a MPEG Transport Stream (TS).
* [TSDuck](https://tsduck.github.io/) - Extensible toolkit for MPEG/DVB transport streams testing, monitoring, integration, debugging, and more.
* [WiFiBroadcast](https://befinitiv.wordpress.com/wifibroadcast-analog-like-transmission-of-live-video-data/) - Analog-like transmission of live video data.

## Animation, Graphics & Video Playout

* [Aurena](https://github.com/thaytan/aurena) - A network distributed media playback system.
* [Blender](https://developer.blender.org/diffusion/) - 3D creation suite supporting 3D modelling, animation, motion tracking, video editing, and more.
* [CasparCG](http://www.casparcg.com/) - A professional graphics and video play-out software, proven in 24/7 broadcasts since 2006.
* [i-Score](http://i-score.org/) - A free and open-source intermedia sequencer.
* [Macadam](https://github.com/Streampunk/macadam) - Blackmagic Node.js bindings that support HTML/CSS (via [Electron](https://electronjs.org/)) and SVG (via [Sevruga](https://github.com/Streampunk/sevruga)) graphics.
* [Open Playout Automation](https://github.com/jaskie/PlayoutAutomation) - A CasparCG-based MCR play-out system.
* [Sofie - TV Automation](https://github.com/nrkno/Sofie-TV-automation) - MOS-driven automation system for news casts, with many libraries for e.g. device control.

## Hybrid Radio

* [RadioDNS for Node.js](https://github.com/bbc/node-radiodns) - Perform RadioDNS resolutions and service lookups in node.js.
* [RadioDNS Manager](https://github.com/ebu/radiodns-plugit) - Platform to manage Hybrid Radio services, e.g. RadioVIS, RadioEPG and Service Following.
* [RadioTag.js](https://github.com/ebu/radiotag.js) - RadioTag client library in JavaScript.
* [RadioVIS Demo](https://github.com/bbc/RadioVisDemo) - RadioVIS client application in Python.
* [RadioVIS Html Player](https://github.com/ebu/radiovis-html5player) - RadioVIS Player using WebSocket.
* [RadioVIS Stomp Server](https://github.com/bbc/node-radiovis-stomp-server) - RadioVIS STOMP server written in node.js.

## LiveIP
*Audio/Video over IP & Streaming*

* [butt](https://danielnoethen.de/) - broadcast using this tool (butt) is an easy to use, multi OS streaming tool. It supports SHOUTcast and Icecast.
* [Cool Mic](https://coolmic.net/) - Android audio livestreaming Icecast source client app.
* [DarkIce](http://www.darkice.org/) - A live audio streamer that records audio from an audio interface (e.g. sound card), encodes it and sends it to a streaming server.
* [Icecast](http://icecast.org/) - A streaming media (audio/video) server which supports Ogg (Vorbis and Theora), Opus, WebM and MP3 streams.
* [Kamailio](http://www.kamailio.org/) - Open SIP server, commonly used for Audio contribution over IP using SIP (EBU ACIP).
* [OpenOB](https://jamesharrison.github.io/openob/) - Open Outside Broadcast project for radio contribution links and studio-transmitter links based on Opus.
* [PJSIP](http://www.pjsip.org/) - Open Source multimedia library implementing SIP, SDP, RTP, STUN, TURN, and ICE. Used in some contribution equipment (dual licensing).
* [trx](http://www.pogo.org.uk/~mark/trx/) - A simple toolset for broadcasting live audio from Linux.

## Media Players

* [Dash.js](https://github.com/ebu/dash.js) - A reference client implementation for the playback of MPEG DASH via Javascript and compliant browsers.
* [GPAC](http://gpac.wp.mines-telecom.fr/home/) - Multimedia player, packager and tools.
* [IDJC](http://idjc.sourceforge.net/) - A GTK+ Shoutcast/Icecast client with two main media players.
* [Kodi](https://github.com/xbmc/xbmc) - A software media player and entertainment hub for digital media.
* [Media4DPlayer](https://github.com/ebu/media4Dplayer) - HTML5 player focused on accessibility.
* [MPD](https://www.musicpd.org/) - A flexible, powerful, server-side application for playing music.
* [mpg123](https://www.mpg123.de/) - A fast console MPEG Audio Player and decoder library.
* [Mixxx](https://www.mixxx.org/) - A free, open source DJ software.
* [Peaks.js](http://waveform.prototyping.bbc.co.uk/) - Browser-based audio waveform visualisation.
* [rx-player](https://github.com/canalplus/rx-player) - HTML5/Javascript video player with some reactive programming inside, supporting MPEG-DASH and SmoothStreaming transports.
* [VLC](http://www.vlc.org) - Simple, fast and powerful media player.

## Metadata

* [BMXlib](http://sourceforge.net/projects/bmxlib/) - Library and utilities to read and write broadcasting media files. Primarily supports the MXF file format.
* [EBUCore](https://github.com/ebu/ebucore) - The Github for maintenance of the [EBUCore schema](https://tech.ebu.ch/docs/tech/tech3293.pdf).
* [AMWA IS-04 and IS-05](https://github.com/bbc/nmos-joint-ri) - Python implementation of the AMWA IS-04 NMOS Registration and Discovery Specification and AMWA IS-05 NMOS Device Connection Management Specification.
* [jebu-core](https://github.com/mikrosimage/jebu-core) - EBUCore XML Schema Java port. Java port of [TECH 3293](https://tech.ebu.ch/publications/tech3293) EBU CORE METADATA SET (EBUCore) SPECIFICATION v. 1.5, including new [Audio Definition Model](https://tech.ebu.ch/docs/tech/tech3364.pdf).
* [libadm](https://github.com/irt-open-source/libadm) - Audio Definition Model (ITU-R BS.2076) handling C++11 library.
* [MAJ API](https://github.com/AMWA-TV/maj) - Pure Java library for reading and writing MXF and AAF files.
* [NMOS](https://github.com/sony/nmos-cpp) - An NMOS (Networked Media Open Specifications) Registry and Node in C++ (IS-04, IS-05).
* [SDPoker](https://github.com/Streampunk/sdpoker) - CLI tool and library for testing SMPTE ST2110 SDP files.
* [TV-Anytime](https://github.com/ebu/tvanytime) - The TV-Anytime schema github maintenance page.

## Monitoring & Quality Control

* [BeaqleJS](https://github.com/HSU-ANT/beaqlejs) - A framework to create browser based listening tests for subjective audio quality assessment.
* [Jack Meter](https://github.com/njh/jackmeter) - Text console based DPM (Digital Peak Meter) for JACK.
* [JACK Meterbridge](http://plugin.org.uk/meterbridge/) - A collection of graphical Audio meters for JACK.
* [Jmeters](http://kokkinizita.linuxaudio.org/linuxaudio/index.html) - A collection of graphical audio meters for JACK, including VU, PPM and [EBU R 128](https://tech.ebu.ch/publications/r128) Loudness meters.
* [LTC-tools](https://github.com/x42/ltc-tools) - A collection of tools to read, generate and trigger against Linear Timecode (LTC) and convert to MIDI Timecode (MTC) with JACK and to/from standalone files.
* [MediaConch](https://mediaarea.net/MediaConch/) - Implementation checker, policy checker, & reporter for Matroska, FFV1, & PCM.
* [MediaInfo](https://mediaarea.net/en/MediaInfo) - A convenient unified display of the most relevant technical and tag data for video and audio files.
* [MXF Inspect](http://www.myriadbits.com/) - A Windows tool to display the internal structure of an MXF (Material eXchange Format) file.
* [Pi Audio Monitor](https://github.com/martim01/pam) - Audio Monitoring for Raspberry Pi, supports S/PDIF, AES3, AES67, Livewire and Ravenna.
* [Photon](https://github.com/Netflix/photon) - Implementation of the SMPTE Interoperable Master Format (IMF) standard.
* [QCTools](https://github.com/bavc/qctools) - Quality Control tools for video preservation to analyse digitized video files.
* [Rotter](https://github.com/njh/rotter) - Recording of Transmissions / Audio Logger for JACK.
* [silan](https://github.com/x42/silan) -  Audiofile silence analyzer.
* [SilentJack](https://github.com/njh/silentjack) - Dead-air / Silence detector for JACK.
* [Sonic Visualiser](http://www.sonicvisualiser.org/) - An application for viewing and analysing the contents of music audio files.
* [VMAF](https://github.com/Netflix/vmaf) - Perceptual video quality assessment based on multi-method fusion.
* [Wisual](https://github.com/MarcAntoine-Arnaud/wisual) - A web service for Visual Quality Assessment, which supports PSNR, SSIM, VQM, etc.

## Multimedia content processing

* [AvTranscoder](https://github.com/avTranscoder/avTranscoder) - Based on FFmpeg/LibAV libraries to support various video and audio formats, avTranscoder provides the high level API to re-wrap or transcode media easily. It also provide bindings for any usage in Java or Python.
* [Beam Coder](https://github.com/Streampunk/beamcoder) - Node.js native bindings to FFmpeg, with support for asynchronous processing via promises and streams.
* [Bento4](https://github.com/axiomatic-systems/Bento4) - Full-featured MP4 format and MPEG DASH C++ class library and tools.
* [Codem-isoboxer](https://github.com/madebyhiro/codem-isoboxer) A small browser-based MPEG-4 (ISOBMFF) parser.
* [Dynamorse](https://github.com/Streampunk/node-red-contrib-dynamorse-core) - IT swiss army knife - a Node-RED media pipeline builder, adding professional media processing nodes.
* [EBU ADM Renderer](https://github.com/ebu/ebu_adm_renderer) - Reference implementation of the EBU ADM Renderer ([EBU Tech 3388](https://tech.ebu.ch/publications/tech3388))
* [FFmbc](https://github.com/bcoudurier/FFmbc) - FFmpeg customized for broadcast and professional usage.
* [FFmpeg](http://ffmpeg.org) - A cross-platform solution to record, convert and stream audio and video. Supports SMPTE ST 2110.
* [Flowblade](https://github.com/jliljebl/flowblade) - A multitrack non-linear video editor.
* [GStreamer](https://gstreamer.freedesktop.org/) - A library for constructing graphs of media-handling components.
* [Kelvinadon](https://github.com/Streampunk/kelvinadon) - Node.JS pure Javascript module for streaming MXF files to and from JSON.
* [KFR](https://www.kfrlib.com/) - Fast, modern C++ DSP framework, DFT/FFT, Audio resampling, FIR/IIR, Biquad, EBU R 128.
* [L-SMASH](https://github.com/l-smash/l-smash/) - A rigidly spec-compliant ISOBMFF library, which has full DASH muxing support.
* [LibAV](https://libav.org/) - Open source audio and video processing tools.
* [libbw64](https://github.com/irt-open-source/libbw64) – Header-only Broadcast Wave 64 (ITU-R BS.2088) C++11 library.
* [Libebur128](http://github.com/jiixyj/libebur128) - A library that implements the EBU R 128 standard for loudness normalisation.
* [Loudness Validator](https://github.com/mikrosimage/loudness_validator) - A set of applications to analyse, visualise and correct the loudness.
* [MP4Box.js](https://github.com/gpac/mp4box.js) - JavaScript library to process MP4 files in the browser (and in NodeJS).
* [MXFLib](http://sourceforge.net/projects/mxflib) - A multi-platform C++ library for reading and writing MXF files.
* [OBS-Studio](https://github.com/jp9000/obs-studio) - Software for live streaming and screen recording.
* [Open Broadcast Encoder](https://github.com/ob-encoder) - Broadcast encoder built from Open Source components.
* [rgain](https://bitbucket.org/fk/rgain) - Tools and Python library to read, write and calculate Replay Gain.
* [rtmp](https://github.com/c-bata/rtmp) - Server implementation of Adobe's RTMP 1.0 protocol in Go.
* [Snowmix](https://sourceforge.net/projects/snowmix/) - Live Video Mixer.
* [SoX](http://sox.sourceforge.net/) - The Swiss Army knife of sound processing programs.
* [TuttleOFX](http://www.tuttleofx.org/) - An open source image processing framework based on OpenFX plugin standard.
* [UPipe](https://github.com/cmassiot/upipe/) - Primarily designed to be the core of a multimedia player, transcoder or streamer.
* [VideoContext](https://github.com/bbc/videocontext) - Experimental HTML5/WebGL media processing and sequencing library for creating interactive and responsive videos on the web.
* [Voctomix](https://github.com/voc/voctomix) - Customizable conference recording and mixing software based on Python and GStreamer with streaming capabilities and Core/GUI separation.

## Network & Storage Testing

* [BBC Media Storage Meter](http://sourceforge.net/projects/msmeter/) - An application for the testing of network attached storage, originally assumed to be used for the streaming of professional media.
* [Fio](https://github.com/axboe/fio) - Flexible I/O Tester
* [iPerf3](https://iperf.fr/) - The TCP, UDP and SCTP network bandwidth measurement tool.
* [SMPTE 2110-20 Analyzer](https://github.com/ebu/smpte2110-analyzer) - An analyzer to inspect network packets generated in accordance with the SMPTE ST 2110 specification.

## Radio Production

* [Airtime](https://www.sourcefabric.org/en/airtime/) - Radio management application for remote broadcast automation (via web-based schedule).
* [Ardour](https://ardour.org/) - A digital audio workstation.
* [Audacity](http://audacity.sourceforge.net/) - Cross-platform software for recording and editing sounds.
* [AzuraCast](http://github.com/AzuraCast/AzuraCast) - A self-hosted web radio management suite.
* [LibreTime](http://libretime.org/) - Radio broadcast & automation platform (fork of Airtime).
* [Liquidsoap](https://github.com/savonet/liquidsoap) - A Swiss army knife for multimedia streaming ([documentation](http://liquidsoap.fm/index.html)).
* [OpenBroadcaster](https://openbroadcaster.com/) Open Source LPFM IPTV Broadcast Automation. [Server and Player code here](https://github.com/openbroadcaster).
* [RAAR](https://github.com/radiorabe/raar) - A ruby application to manage and browse an audio archive.
* [Rivendell](http://www.rivendellaudio.org/) - Complete radio broadcast automation solution, translated to many languages and used worldwide.

## Software-defined radio

* [GNU Radio](https://www.gnuradio.org/) - A software development toolkit that provides signal processing blocks to implement software radios.
* [Gqrx SDR](http://gqrx.dk/) - An open source software defined radio receiver (SDR).
* [ODR-mmbTools](https://www.opendigitalradio.org) - Fork, continuation of CRC-mmbTools. Adding new features for 24/24 365/365 live operation, DAB+, associated data (slideshow, text), distributed infrastructure, SFN.
* [rtl-sdr](http://osmocom.org/projects/sdr/wiki/rtl-sdr) - Turns a Realtek RTL2832 based DVB dongle into a SDR receiver.
* [welle.io](https://www.welle.io/) - An open source DAB and DAB+ software defined radio (SDR) with support for airspy and rtlsdr.

## Subtitling

* [CCExtractor](http://ccextractor.sourceforge.net/about-ccextractor.html) - A tool that analyzes video files and produces stand-alone subtitle files.
* [EBU-TT-D Subtitling within dash.js](https://github.com/ebu/dash.js/tree/ebu-subtitling-dev) - The original fork of dash.js to experiment with XML based subtitles like EBU-TT-D within dash.js. Uses an HTML/CSS overlay. Has since been integrated into [dash.js](https://github.com/ebu/dash.js).
* [EBU-TT-D W3C XML Schema](https://github.com/ebu/ebu-tt-d-xsd/) - Informative EBU-TT-D XML Schema to support the implementation of EBU Tech 3380.
* [EBU-TT Live Interoperability Toolkit](https://github.com/ebu/ebu-tt-live-toolkit) - A set of components for generating, testing and distributing subtitle documents in the [EBU-TT Live](https://tech.ebu.ch/publications/tech3370) format.
* [GStreamer TTML subtitling package](https://github.com/bbc/gst-ttml-subtitles) - A means for GStreamer pipelines to parse and render  EBU-TT-D (TTML) subtitles.
* [imscJS](https://github.com/sandflow/imscJS) - JavaScript library for rendering IMSC1 Text and Image Profile documents to HTML5.
* [IRT EBU-TT-D Application Samples](https://github.com/IRT-Open-Source/irt-ebu-tt-d-application-samples) - EBU-TT-D sample files, related PNG images and mp4 videos showing how they should be rendered.
* [Subtitle Edit](http://www.nikse.dk/SubtitleEdit) - An editor for subtitles.
* [Subtitling Conversion Framework (SCF)](https://github.com/Irt-Open-Source/scf) - A set of modules for converting subtitle formats. Main target is the conversion of EBU STL and EBU-TT subtitle files. Alpha release.
* [Timed Text Toolkit (ttt)](https://github.com/skynav/ttt) - A collection of related tools that provide support for or make use of the W3C Timed Text Markup Language (TTML).

## Video Production

* [MIDIMonster](https://github.com/cbdevnet/midimonster) - Lightweight adapter tool for common show control protocols.
* [MOS-connection](https://github.com/nrkno/tv-automation-mos-connection) - A JavaScript library for connection and MOS messaging either as MOS device or NRCS.
* [Open Lighting Architecture (OLA)](https://www.openlighting.org/ola/) - OLA is a framework for lighting control information, the travel adaptor for the lighting industry, for converting between Digital Multiplex (DMX-512) and IP variants and interfacing with USB adaptors.
* [PiClock](https://github.com/simonhyde/PiClock) - Customisable network based displays of clocks, on-air, mic live and other studio indicators.
* [Q Light Controller+ (QLC+)](https://www.qlcplus.org/) - QLC+ is cross-platform software to control DMX or analog lighting systems like moving heads, dimmers, scanners etc.
* [Teleprompter](https://github.com/ImaginarySense/Teleprompter-Core) - Web browser and standalone Electron app prompter.

# Resources
Various resources, such as books, websites and articles, for improving your skills and knowledge.

## Blogs

* [BBC News Labs](https://github.com/BBC-News-Labs) - Open Source projects from BBC News Labs.
* [BBC R&D](http://bbc.co.uk/rd) - BBC Research and Development. Checkout the weekly notes.
* [3D CineCast](http://3dcinecast.blogspot.ch/) - A curation about new media technologies.
* [Canal+](http://canalplus.github.io/) - CANAL+ Open Source Community.
* [IRT Lab](https://lab.irt.de/) - IRT blog posting developments and demos for all digital audiovisual media technology.
* [The Netflix Tech Blog](http://techblog.netflix.com/) - A Netflix blog focused on technology and technology issues.
* [Youtube Engineering and Developers Blog](http://youtube-eng.blogspot.com) - What's happening with engineering and developers at YouTube.

## Websites
*Useful broadcasting related websites.*

* [EBU.io](http://www.ebu.io) - A platform for agile collaboration.

<!-- This page is available on http://ebu.io/opensource -->

# Contributing
Please see [CONTRIBUTING](https://github.com/ebu/awesome-broadcasting/blob/master/CONTRIBUTING.md) for details.
