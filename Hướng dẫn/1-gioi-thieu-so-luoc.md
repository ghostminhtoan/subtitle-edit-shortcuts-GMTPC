# 1. Giới thiệu sơ lược về Subtitle Edit

Nguồn gốc nội dung: [Nikse - Subtitle Edit](https://www.nikse.dk/subtitleedit)

# Subtitle Edit

### Overview

Subtitle Edit is a free (open source) editor for video subtitles - a subtitle editor :)

With SE you can easily adjust a subtitle if it is out of sync with the video in [several different ways](https://www.nikse.dk/SubtitleEdit/Help#sync). You can also use SE for making new subtitles from scratch (do use the time-line/waveform/spectrogram) or translating subtitles. For a list of features see below or check out the [Subtitle Edit Help](https://www.nikse.dk/SubtitleEdit/Help) page. On [my blog](https://www.nikse.dk/) you can download latest beta version and read about/discuss new features.

Also, you can [watch a few videos](https://www.nikse.dk/SubtitleEdit/Video) about installing and using Subtitle Edit.

A Subtitle Edit dll (LibSe.dll) is available for programmers (BSD New/Simplified license). Compile it from source code or use the [NuGet package](https://www.nuget.org/packages/libse/).

[Download latest version of Subtitle Edit](https://github.com/SubtitleEdit/subtitleedit/releases)

Note: SE requires Microsoft .NET Framework Version 4.8

Get the [full C# source code](https://github.com/SubtitleEdit/subtitleedit) - [GPL](https://www.gnu.org/licenses/gpl.txt) or [LGPL](https://www.gnu.org/licenses/lgpl-3.0.txt) license.

Blu-ray sup reading [code](https://forum.doom9.org/showthread.php?t=145277) is under the Apache License and Matroska subtitle parsing uses [zlib code](http://www.componentace.com/zlib_.NET.htm) with a BSD style license.

### Features

- Create/adjust/sync/translate subtitle lines
- Convert between SubRib, MicroDVD, Advanced Sub Station Alpha, Sub Station Alpha, D-Cinema, SAMI, youtube sbv, and many more (300+ different formats!)
- Cool audio visualizer control - can display wave form and/or spectrogram
- Video player uses [mpv](https://mpv.io/), DirectShow, or [VLC media player](https://www.videolan.org/vlc/)
- Visually sync/adjust a subtitle (start/end position and speed)
- Speech to text (speech recognition) via Whisper
- Text to speech via e.g. via ElevenLabs, Azure, Google or local TTS engines installed on your pc
- Auto Translation via Google translate, DeepL, local LLMs like Ollama and LM Studio, and many more AIs.
- Rip subtitles from a (decrypted) dvd
- Import and OCR VobSub sub/idx binary subtitles
- Import and OCR Blu-ray .sup files - bd sup reading is based on Java code from [BDSup2Sub](https://forum.doom9.org/showthread.php?t=145277) by 0xdeadbeef
- Can open subtitles embedded inside [Matroska](https://www.matroska.org/) files
- Can open subtitles (text, closed captions, VobSub) embedded inside mp4/mv4 files
- Can open/OCR XSub subtitles embedded inside divx/avi files
- Can open/OCR DVB and teletext subtitles embedded inside `.ts`/`.m2ts` (Transport Stream) files
- Can open/OCR Blu-ray subtitles embedded inside `.m2ts` (Transport Stream) files
- Can read and write both UTF-8 and other unicode files and ANSI (support for all languages/encodings on the pc!)
- Sync: Show texts earlier/later + point synchronization + synchronization via other subtitle
- Merge/split subtitles
- Adjust display time
- Fix common errors wizard
- Spell checking via [Libre Office dictionaries](https://extensions.libreoffice.org/?Tags%5B%5D=50) (many dictionaries available)
- Remove text for hear impaired (HI)
- Renumbering
- Effects: Typewriter and karaoke
- History/undo manager (`Undo=Ctrl+z`, `Redo=Ctrl+y`)
- Compare subtitles
- Multiple search and replace
- Change casing using names dictionary
- Merge short lines/split long lines
- Export to PNG images (+bdn xml), Adobe Encore FAB image script, VobSub, Blu-ray sup, EBU stl, PAC, and plain text
- Generate video with burned-in subtitles or on transparent video

Subtitle Edit is available in [32+ languages](https://github.com/SubtitleEdit/subtitleedit/tree/main/src/ui/Languages). [Read more about how to translate Subtitle Edit](https://www.nikse.dk/SubtitleEdit/Help#translate).

Subtitle Edit can read, write, and convert between more than 300 subtitle formats, like:

- [SubRip](https://www.nikse.dk/subtitleedit/formats/subrip) (`*.srt`)
- ABC iView
- Adobe Encore
- [Advanced Sub Station Alpha](https://www.nikse.dk/subtitleedit/formats/assa)
- AQTitle
- Avid
- CapMaker Plus (`*.cap`, binary)
- Captionate
- Cavena890 (`*.890`, binary)
- Cheetah Caption (`*.cap`, binary)
- D-Cinema (Cinecanvas, both interop and smpte)
- Dvd Studio Pro
- Dvd Subtitle
- EBU Subtitling data exchange format (`*.stl`, binary)
- F4 (several variations)
- Flash xml
- Json (two variations, for use with JavaScript)
- MicroDvd
- MPlayer2
- OpenDvt
- PAC (`*.pac`, binary)
- Pinnacle Impression
- QuickTime Text
- RealTime Text
- Scenarist
- Sony DVD Architect
- Sub Station Alpha
- SubViewer 1.0
- SubViewer 2.0
- Sami (`*.smi`)
- Son (`*.son`, import only)
- Subtitle Editor Project
- Timed Text 1.0 (`*.xml`), also know as [TTML](https://www.w3.org/TR/ttaf1-dfxp/) or DFXP
- Timed Text Draft (`*.xml`)
- TMPlayer
- TTXT
- TurboTitle
- Ulead Subtitle Format
- Ultech (`*.cap`, binary, only read)
- UTX
- [WebVTT](https://www.w3.org/community/texttracks/)
- YouTube Annotations
- YouTube Sbv
- Zero G
- Xml
- Csv
- VobSub (`*.sub/*.idx`, binary - can also be read from Matroska/mp4 files)
- DVD Vob (`*.vob`, binary, read only)
- Blu-ray sup (`*.sup`, binary, can also be read from Matroska files)
- Bdn xml (`*.xml + png images`, read+write)
- Transport Stream subtitles (`*.ts`)
- + several formats of unknown name

<small>Subtitle Edit can also convert subtitles via command line or the batch-convert-ui.</small>

### Subtitle Edit main window

![Subtitle Edit main window](https://www.nikse.dk/assets/SubtitleEdit/subtitle-edit.png)

### Main window with dark theme

![Main window with dark theme](https://www.nikse.dk/assets/SubtitleEdit/se2.jpg)

### Awards

| Award | Image |
| --- | --- |
| [Softpedia.com](https://www.softpedia.com/get/Multimedia/Video/Other-VIDEO-Tools/Subtitle-Edit.shtml) | ![Softpedia award](https://www.softpedia.com/base_img/softpedia_free_award_f.gif) |
| [Windows 10 Download](https://www.windows10download.com/subtitle-edit/) | ![Windows 10 Download](https://www.windows10download.com/img/awards/award_5.png) |
| [Windows 8 Downloads - Editor's Pick](https://www.windows8downloads.com/win8-subtitle-edit-sztxdajh/) | ![Windows 8 Downloads - Editor's Pick](https://www.windows8downloads.com/img/awards/award_pick.png) |
| [Download Subtitle Edit - 5 Stars award](http://subtitle-edit.win7dwnld.com/) | ![5 Stars award](https://www.nikse.dk/assets/SubtitleEdit/rated_5.png) |
| [Best Freeware Download](http://www.bestfreewaredownload.com/freeware/k-subtitle-edit-t-free-subtitle-edit-freeware-syisoivb.html) | ![Best Freeware Download](http://www.bestfreewaredownload.com/images/BFD_award5.png) |
| [Bravofiles](http://subtitle-edit1.software.informer.com/) | ![Bravofiles](https://www.nikse.dk/assets/SubtitleEdit/rated_5.png) |
| [Programosy](http://www.programosy.pl/program,subtitle-edit.html) | ![Programosy](http://www.programosy.pl/img/stars.png) |
| [Digital Digest Editors Pick](http://www.digital-digest.com/software/category-22.html) | ![Digital Digest](http://www.digital-digest.com/images/awards/editor.gif) |
| [INSTALKI.pl](http://www.instalki.pl/programy/download/Windows/multimedia_inne/Subtitle_Edit.html) | ![INSTALKI.pl](https://www.instalki.pl/wp-content/uploads/2023/08/Logo-Instalki-2023.webp) |
| [Subtitle Edit scored 4.5 out of 5 at komputerswiat.pl](http://download.komputerswiat.pl/muzyka-i-wideo/napisy-do-filmow/subtitle-edit) | ![Komputerswiat](https://download.komputerswiat.pl/static/gfx/logo/dl_logo.png) |
| [filecluster](http://www.filecluster.com/Audio-Video/Video-Utilities-Codecs/Download-Subtitle-Edit.html) | ![filecluster](https://www.nikse.dk/assets/SubtitleEdit/rated_5.png) |
| [Top 4 Download](http://www.top4download.com/subtitle-edit/joqsipbq.html) | ![Top 4 Download](http://www.top4download.com/templates/T4D/images/award_5.gif) |
| [FileHorse.com](https://www.filehorse.com/download-subtitle-edit/) | ![FileHorse](https://www.nikse.dk/assets/SubtitleEdit/filehorse-award-5star.png) |
| [bytesin.com](https://www.bytesin.com/software/Subtitle-Edit/) | ![bytesin.com](https://www.nikse.dk/assets/SubtitleEdit/bytesin_rated_5.png) |
| [freeappsforme.com](https://freeappsforme.com/subtitle-edit-software-review/) | ![freeappsforme.com](https://www.nikse.dk/assets/SubtitleEdit/freeappsforme.png) |

### How to display subtitles

Save the subtitle file in the same folder as the video/audio file and give it the same name as the video/audio file (not the extension).

To play video with subtitles, you need a video player with good subtitle support like [Media Player Classic - Home cinema](https://github.com/clsid2/mpc-hc/releases), [VLC media player](http://www.videolan.org/vlc/), or [mpv](https://mpv.io).

Read more on [the Subtitle Edit help/FAQ](https://www.nikse.dk/subtitleedit/help) page.
