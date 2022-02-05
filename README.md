# deepgram-podcast-srt

A quick & dirty script for getting srt files from podcasts (https://podcast.designmasterclass.fr).

## Install

```sh
git clone https://github.com/avetisk/deepgram-podcast-srt
cd deepgram-podcast-srt
npm link
echo 'DEEPGRAM_API_KEY=REPLACE_WITH_YOUR_DEEPGRAM_API_KEY' > .env
```

## Usage

```sh
deepgram-podcast-srt URL_1 [...URL_N]
```

This will create an `output` directory with all the `.srt` transcript files in it.
