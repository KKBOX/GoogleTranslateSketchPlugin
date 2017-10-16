# Google Translate Sketch Plugin

Google Translate Sketch Plugin is orignally an internal tool in
KKBOX. The tool helps you to translate selected text layers into
desired language using Google Cloud Translate API, in order to improve
the work flow of our app/web design.

To start using, an API key is required. You can obtain an API key by
following Google's instruction: [Translation API Quickstart](https://cloud.google.com/translate/docs/getting-started)

## About

KKBOX provides streaming service in not only Taiwan but also other
contries/areas such as Hong Kong, Singapore, Maylaysia and
Japan. Working with localization/multi-languages is a must but always
painful.

Since KKBOX is a Taiwan based company and Taiwan, we work on inital
designs using Traditional Chinese, and then ask our oversea crews to
help strings into other languages.

The Chinese strings are always shorter than strings in other
languages, and we may often find that the translate text is overflow
on our designs. We may chnage the design, or request a shorter
translation, but the schedule for development and release is effected.

So, we need to be able to preview what our designs may look like in
the earlier periods. Since we use Sketch as our design tool and it
supports a plugin system, we create a simple plugin to bridge Google
Translate API.

## Requirement

A Mac computer with Sketch intalled. The plugin is tested on Sketch 43
and 45.

## Installation

- Download the [plugin package](https://github.com/KKBOX/GoogleTranslateSketchPlugin/archive/master.zip)。
- Unzip the downloaded file.
- Double click on `Google Translate.sketchplugin`.

## Usage

- Launch Sketch. Choose "設定" (settings) in the Google Translate
  Plugin menu, and input your API key,
- Select any text layer in your Sketch document.
- You can select layer groups as well.
- Choose what you want to do in Plugins->Google Translate, such as "中
  翻英" (Chinse to English), "中翻日" (Chinese to Japanse) "中翻馬來"
  (Chinese to Malay).
