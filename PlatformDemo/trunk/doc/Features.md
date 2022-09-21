# Features

The features of SRS.

- [x] System: Support coroutine [state-threads](https://github.com/ossrs/state-threads) for high performance.
- [x] System: Support native HTTP server([CN](https://ossrs.net/lts/zh-cn/docs/v4/doc/sample-http), [EN](https://ossrs.io/lts/en-us/docs/v4/doc/sample-http)) for http api and http live streaming.
- [x] System: Support DVR([CN](https://ossrs.net/lts/zh-cn/docs/v4/doc/dvr), [EN](https://ossrs.io/lts/en-us/docs/v4/doc/dvr)) to record live streaming to FLV file.
- [x] System: Support security strategy including allow/deny publish/play IP([CN](https://ossrs.net/lts/zh-cn/docs/v4/doc/security), [EN](https://ossrs.io/lts/en-us/docs/v4/doc/security)).
- [x] System: Support Vhost([CN](https://ossrs.net/lts/zh-cn/docs/v4/doc/rtmp-url-vhost), [EN](https://ossrs.io/lts/en-us/docs/v4/doc/rtmp-url-vhost)) and \_\_defaultVhost\_\_.
- [x] System: Support reloading([CN](https://ossrs.net/lts/zh-cn/docs/v4/doc/reload), [EN](https://ossrs.io/lts/en-us/docs/v4/doc/reload)) to apply changes of config.
- [x] System: Support traceable and session-based log([CN](https://ossrs.net/lts/zh-cn/docs/v4/doc/log), [EN](https://ossrs.io/lts/en-us/docs/v4/doc/log)).
- [x] System: Support listen at IPv4 and IPv6, read [#460](https://github.com/ossrs/srs/issues/460).
- [x] System: Support docker by [srs-docker](https://hub.docker.com/r/ossrs/srs/tags).
- [x] System: Support multiple processes by ReusePort([CN](https://ossrs.net/lts/zh-cn/docs/v4/doc/reuse-port), [EN](https://ossrs.io/lts/en-us/docs/v4/doc/reuse-port)), [#775](https://github.com/ossrs/srs/issues/775).
- [x] System: Support include directive for config file, [#2878](https://github.com/ossrs/srs/pull/2878).
- [x] System: Support x86_64, armv7 and aarch64 docker image, [#3058](https://github.com/ossrs/srs/pull/3058).
- [x] System: [Experimental] Enhance HTTP Stream Server for HTTP-FLV, HTTPS, HLS etc. [#1657](https://github.com/ossrs/srs/issues/1657).
- [x] System: [Experimental] Support DVR in MP4 format, read [#738](https://github.com/ossrs/srs/issues/738).
- [x] System: [Experimental] Support loongarch, loongson CPU, [#2689](https://github.com/ossrs/srs/issues/2689).
- [x] System: [Experimental] Support Apple Silicon M1(aarch64), [#2747](https://github.com/ossrs/srs/issues/2747).
- [x] System: [Experimental] Support distributed tracing by Tencent Cloud APM.
- [x] API: Support HTTP API([CN](https://ossrs.net/lts/zh-cn/docs/v4/doc/http-api), [EN](https://ossrs.io/lts/en-us/docs/v4/doc/http-api)) for system management.
- [x] API: Support HTTP callback([CN](https://ossrs.net/lts/zh-cn/docs/v4/doc/http-callback), [EN](https://ossrs.io/lts/en-us/docs/v4/doc/http-callback)) for authentication and integration.
- [x] API: Support reuse HTTP Stream port for HTTP API, [#2881](https://github.com/ossrs/srs/issues/2881).
- [x] Live: Support Edge Cluster for live streaming, see ([CN](https://ossrs.net/lts/zh-cn/docs/v4/doc/edge), [EN](https://ossrs.io/lts/en-us/docs/v4/doc/edge)).
- [x] Live: Support Origin server for converting RTMP to HTTP-FLV([CN](https://ossrs.net/lts/zh-cn/docs/v4/doc/sample-http-flv), [EN](https://ossrs.io/lts/en-us/docs/v4/doc/sample-http-flv)) and HLS([CN](https://ossrs.net/lts/zh-cn/docs/v4/doc/delivery-hls), [EN](https://ossrs.io/lts/en-us/docs/v4/doc/delivery-hls)).
- [x] Live: Support Edge server for converting RTMP to HTTP-FLV([CN](https://ossrs.net/lts/zh-cn/docs/v4/doc/sample-http-flv), [EN](https://ossrs.io/lts/en-us/docs/v4/doc/sample-http-flv)).
- [x] Live: Support HLS with aac(h.264+aac) and mp3(h.264+mp3) codec, please read [bug #301](https://github.com/ossrs/srs/issues/301).
- [x] Live: Support transmux RTMP to HTTP-FLV/MP3/AAC/TS, please read wiki([CN](https://ossrs.net/lts/zh-cn/docs/v4/doc/delivery-http-flv), [EN](https://ossrs.net/lts/zh-cn/docs/v4/doc/delivery-http-flv)).
- [x] Live: Support timestamp correcting for long time(>4.6hours) publishing/playing.
- [x] Live: Support gop-cache([CN](https://ossrs.net/lts/zh-cn/docs/v4/doc/low-latency#gop-cache), [EN](https://ossrs.io/lts/en-us/docs/v4/doc/low-latency#gop-cache)) for player fast startup.
- [x] Live: High performance([CN](https://ossrs.net/lts/zh-cn/docs/v4/doc/performance), [EN](https://ossrs.io/lts/en-us/docs/v4/doc/performance)) RTMP/HTTP-FLV, 6000+ connections.
- [x] Live: Enhanced RTMP url which supports vhost in stream, read [#1059](https://github.com/ossrs/srs/issues/1059).
- [x] Live: Support origin cluster, please read [#464](https://github.com/ossrs/srs/issues/464), [RTMP 302](https://github.com/ossrs/srs/issues/92).
- [x] Live: Support NGINX HLS Cluster, see [CN](https://ossrs.net/lts/zh-cn/docs/v4/doc/sample-hls-cluster) or [EN](https://ossrs.io/lts/en-us/docs/v4/doc/sample-hls-cluster).
- [x] Live: [Experimental] Support MPEG-DASH, the future live streaming protocol, read [#299](https://github.com/ossrs/srs/issues/299).
- [x] Live: [Experimental] Support SRT server, read [#1147](https://github.com/ossrs/srs/issues/1147).
- [x] Live: [Experimental] Support Coroutine Native SRT over ST, [#3010](https://github.com/ossrs/srs/pull/3010).
- [x] RTC: [Experimental] Support playing stream by WebRTC, [#307](https://github.com/ossrs/srs/issues/307).
- [x] RTC: [Experimental] Support publishing stream by WebRTC, [#307](https://github.com/ossrs/srs/issues/307).
- [x] RTC: [Experimental] Support mux RTP/RTCP/DTLS/SRTP on one port for WebRTC, [#307](https://github.com/ossrs/srs/issues/307).
- [x] RTC: [Experimental] Support client address changing for WebRTC, [#307](https://github.com/ossrs/srs/issues/307).
- [x] RTC: [Experimental] Support transcode RTMP/AAC to WebRTC/Opus, [#307](https://github.com/ossrs/srs/issues/307).
- [x] RTC: [Experimental] Support AV1 codec for WebRTC, [#2324](https://github.com/ossrs/srs/issues/2324).
- [x] RTC: [Experimental] Support transmux RTC to RTMP, [#2093](https://github.com/ossrs/srs/issues/2093).
- [x] RTC: [Experimental] Support WebRTC over TCP directly, [#2852](https://github.com/ossrs/srs/issues/2852).
- [x] Other: Support ingesting([CN](https://ossrs.net/lts/zh-cn/docs/v4/doc/ingest), [EN](https://ossrs.io/lts/en-us/docs/v4/doc/ingest)) other protocols to SRS by FFMPEG.
- [x] Other: Support forwarding([CN](https://ossrs.net/lts/zh-cn/docs/v4/doc/forward), [EN](https://ossrs.io/lts/en-us/docs/v4/doc/forward)) to other RTMP servers.
- [x] Other: Support transcoding([CN](https://ossrs.net/lts/zh-cn/docs/v4/doc/ffmpeg), [EN](https://ossrs.io/lts/en-us/docs/v4/doc/ffmpeg)) by FFMPEG.
- [x] Other: All wikis are writen in [Chinese](https://ossrs.net) and [English](https://ossrs.io).
- [x] Other: Support valgrind and latest ARM by patching ST, read [ST#1](https://github.com/ossrs/state-threads/issues/1) and [ST#2](https://github.com/ossrs/state-threads/issues/2).
- [x] Other: Enhanced complex error code with description and stack, read [#913](https://github.com/ossrs/srs/issues/913).
- [x] Other: Support test coverage for core/kernel/protocol/service.
- [x] Other: Support a simple [mgmt console](http://ossrs.net/console/), please read [srs-console](https://github.com/ossrs/srs-console).
- [x] Other: Support dynamic forwarding by backend api, [#2799](https://github.com/ossrs/srs/pull/2799).
- [x] Other: Support write log to tencent cloud CLS.
- [x] Other: [Experimental] Support pushing MPEG-TS over UDP, please read [bug #250](https://github.com/ossrs/srs/issues/250).
- [x] Other: [Experimental] Support pushing FLV over HTTP POST, please read wiki([CN](https://ossrs.net/lts/zh-cn/docs/v4/doc/streamer#push-http-flv-to-srs), [EN](https://ossrs.io/lts/en-us/docs/v4/doc/streamer#push-http-flv-to-srs)).
- [ ] System: Support Windows/Cygwin 64bits, [#2532](https://github.com/ossrs/srs/issues/2532).
- [ ] System: Support H.265 over RTMP and HLS, [#465](https://github.com/ossrs/srs/issues/465).
- [ ] System: Support source cleanup for idle streams, [#413](https://github.com/ossrs/srs/issues/413).
- [ ] Live: Support HLS variant, [#463](https://github.com/ossrs/srs/issues/463).
- [ ] RTC: Support IETF-QUIC for WebRTC Cluster, [#2091](https://github.com/ossrs/srs/issues/2091).
- [ ] RTC: Improve RTC performance to 5K by multiple threading, [#2188](https://github.com/ossrs/srs/issues/2188).
- [ ] Other: Support push stream by GB28181, [#1500](https://github.com/ossrs/srs/issues/1500).
- [ ] Other: Support change user to run SRS, [#1111](https://github.com/ossrs/srs/issues/1111).
- [x] [Deprecated] Live: Support Adobe HDS(f4m), please read wiki([CN](https://ossrs.net/lts/zh-cn/docs/v4/doc/delivery-hds), [EN](https://ossrs.io/lts/en-us/docs/v4/doc/delivery-hds)) and [#1535](https://github.com/ossrs/srs/issues/1535).
- [x] [Deprecated] Other: Support bandwidth testing, please read [#1535](https://github.com/ossrs/srs/issues/1535).
- [x] [Deprecated] Other: Support Adobe FMS/AMS token traverse([CN](https://ossrs.net/lts/zh-cn/docs/v4/doc/drm#tokentraverse), [EN](https://ossrs.io/lts/en-us/docs/v4/doc/drm#tokentraverse)) authentication, please read [#1535](https://github.com/ossrs/srs/issues/1535).
- [x] [Removed] Other: Support pushing RTSP, please read [#2304](https://github.com/ossrs/srs/issues/2304#issuecomment-826009290).
- [x] [Removed] Other: Support HTTP RAW API, please read [#2653](https://github.com/ossrs/srs/issues/2653).
- [x] [Removed] Other: Support RTMP client library: [srs-librtmp](https://github.com/ossrs/srs-librtmp).

> Remark: About the milestone and product plan, please read ([CN](https://ossrs.net/lts/zh-cn/product), [EN](https://ossrs.io/lts/en-us/product)) wiki.
