# FFmpeg Merge Command

This really simple website generates a FFmpeg script that permits to merge a
video and audio file together, by allowing also custom metadata (if passed as a
txt file). Nothing more, I just needed this and I thought that spending 20
minutes writing a HTML page was better than spending 1 minute writing commands
manually :)

Website URL: https://dinoosauro.github.io/ffmpeg-merge-command/

## Options

When you open the webpage, you will be prompted:

- If you want to remove the last square brackets from the output file name. The
  reason for this is that I needed it, nothing else.
- The output extension of the file. You can choose whatever you want, as long as
  the container actually supports both the video and the audio codec. Keeping
  `mkv` is a safe option.
- The file path of the selected files: for example, if they are on
  `/Users/HelloWorld/Downloads/`, write this path so that FFmpeg can find them
  even if you are not in the same folder in the terminal.

Then, select the files and the script will be generated. You can copy the output
with the button.

## Privacy

Everything is elaborated locally.
