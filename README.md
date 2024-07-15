# Text-to-Speech (TTS) Application

## Overview

This application is a Text-to-Speech (TTS) tool that uses Google Cloud's Text-to-Speech API to convert copied text to speech. It allows users to select different voices, adjust the speaking speed and volume, and bind a hotkey for quick text-to-speech conversion.

Requires a Google Cloud key that can be registered for and downloaded free from Google. 

## Important
Program uses clipboard to read text. Make sure to select text you want before either using binding or Read Text ♪ button. Program will automatically copy selected text to clipboard to read. If using Read Text ♪ button then it will return to last active window after pressing button and copy selected text.

## Features

- Select from various voices provided by Google Cloud TTS. Currently all natural sounding Wavenet GB & US voices are listed.
- Adjust the speaking speed and volume of the synthesized speech.
- Bind a hotkey to trigger the TTS functionality.
- Test the selected voice and speed with a sample text.

## Requirements

- Python 3.6 or higher
- Google Cloud SDK
- Google Cloud Text-to-Speech API
- The following Python packages:
  - `google-cloud-texttospeech`
  - `pyperclip`
  - `keyboard`
  - `pygame`
  - `tkinter`
