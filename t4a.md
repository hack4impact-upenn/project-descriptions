---
layout: project

summary:
    name: Transcribe4All
    tagline: self-hosted web application for painless speech-to-text transcription of audio files

team:
    - year: 2016
      semester: Spring
      pm: Anosha Minai
      tl: Ben Sandler
      developers:
          - Rachel Hong
          - Yoni Nachmany
          - Rodrigo Ornelas

project:
    problem: >
        "One of our greatest challenges in tracking topics is dealing with the sheer volume of content generated online. The most tedious of these are the audio and video because there is no effective way to quickly review the material without losing crucial detail."
    features:
        - Transcribe audio given an audio url and optional search word, using free Sphinx library or IBM Speech-To-Text API
        - Send transcription to given email
        - Perform concurrent transcriptions
        - Store audio files in the cloud after transcription is complete
        - Store transcription information (such as timestamps, confidence, and keywords)
    technologies:
        - Go (for concurrent transcription request)
        - Sphinx (to transcribe audio files for free)
        - Backblaze (to store audio files in the cloud after transcription is complete)
        - IBM Speech-To-Text API (to transcribe audio files)
        - MongoDB (to store transcription information (such as timestamps, confidence, and keywords)
    technical_challenges:
        - A big technical challenge was providing automated audio transcription and storage that is fast, accurate and customizable. We researched and tested different technologies to provide that functionality.
    impact: >
        The best-case usage scenario will allow organizations to feed the application audio and video content stored on hosts like YouTube, SoundCloud, and other sources of audio and video (in a variety of formats) in order to generate transcriptions that can be fed into existing analytical engines.

code:
    github_repo_name: transcribe4all

keywords:
    social_impact_keywords:
        - automation 
        - research
        - data pipeline
    tech_keywords:
        - transcription
        - concurrency
        - search

media:
    screenshots:
        - screenshot_caption: Initial form
          screenshot_url: https://raw.githubusercontent.com/hack4impact/transcribe4all/master/examples/one.png
        - screenshot_caption: Task Started with audio url, email, and search words
          screenshot_url: https://raw.githubusercontent.com/hack4impact/transcribe4all/master/examples/two.png
---
