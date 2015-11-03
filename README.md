# Youtube Video Info



Retrieves information about Youtube Videos.
        Requires youtube-dl
        Args:
            - video_id: Youtube video identifier (11 str code)
        Return:
            - duration: [Integer] length of the video in seconds.
            - resolution: [String] video resolution (WxH).
            - bitrate: [Integer] sum of VidBitRate & AudioBitRate.
            - fps: [Integer] frame per second rate of the video.

Requirements
------------
 1. youtube-dl to download videos (https://github.com/rg3/youtube-dl/)
