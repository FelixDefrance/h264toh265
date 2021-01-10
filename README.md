# h264toh265

Tool based on ffmpeg to convert videos in H264 format to H265. 
H265 is also known as x265 or HEVC. 

See https://x265.readthedocs.io or 'man ffmpeg-codecs'

FFmpeg options makes converted videos output in h265@10bits.

## Vars

LOGFILE             : The log file indeed !
LOGFILE_ERR         : List videos files that are failed to encode.
LISTLOG             : List processed video files
OVERRIDE_SRCFILE    : Replace source file by the converted file (default=false) 
                      **Make your backup first when activate**

## USAGE

Usage: h264toh265 ./directory_to_convert
       See progress with tail -f ~/h264toh265.bash-2021-01-06-18:46.log
