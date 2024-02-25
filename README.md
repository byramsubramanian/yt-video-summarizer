# YouTube Video Summarizer

## Overview

- `yt-video-summarizer-gemma2b.ipynb`: This jupyter notebook downloads and summarizes the transcript of a youtube video using Google Gemma's 2 billion parameters model running locally. Gemma is a new set of lightweight open models built by Google. Gemma was announced on Feb 21, 2024 (https://blog.google/technology/developers/gemma-open-models/) and is available in 2b and 7b parameter sizes.

## Pre-requisites

- Python 3.10 or above
- Ollama v0.1.27 or above (https://github.com/ollama/ollama/releases)
- Visual Studio Code (w/ Python & Jupyter extensions) or Jupyter Notebook / Lab

## Installation

1. Clone this repository.

```
$ git clone https://github.com/byramsubramanian/yt-video-summarizer.git
$ cd yt-video-summarizer
```

2. Set up & activate virtual environment.

```
$ python3 -m venv venv
$ source venv/bin/activate
```

3. Install the required packages.

```
$ pip3 install -r requirements.txt
```

4. Run Gemma 2B using Ollama (for `yt-video-summarizer-gemma2b.ipynb`)

```
$ ollama run gemma:2b
```

## Usage

1. Open the jupyter notebook using Visual Studio Code or Jupyter Lab / Notebook.
2. Execute the cells to download the video transcript and summarize it using langchain and local LLM model.