audiogrep-docker
================

dockerfile for audiogrep and pocketsphinx.

run the build script to build the container, and the run script to run it (you'll want to mount your home directory not mine)

Troubleshooting
---------------
run the pocketsphinx command manually:

```
pocketsphinx_continuous -infile LastKiss.mp3.temp.wav -time yes -vad_prespeech 10 -vad_postspeech 50
```
