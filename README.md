# Multi-Language Translator for Canada

This project is a multi-language translator application built using the HuggingFace Transformers API and Gradio. It translates English text into six widely spoken languages in Canada: French, Mandarin, Arabic, Spanish, Italian, and German.

## Features

- Translates English text into:
  - French
  - Mandarin
  - Arabic
  - Spanish
  - Italian
  - German
- Simple web interface powered by Gradio
- Uses state-of-the-art HuggingFace translation models

## Requirements

- Python 3.7+
- [transformers](https://pypi.org/project/transformers/)
- [gradio](https://pypi.org/project/gradio/)
- [indic-transliteration](https://pypi.org/project/indic-transliteration/)
- [unidecode](https://pypi.org/project/Unidecode/)
- [pyarabic](https://pypi.org/project/PyArabic/)
- [arabic-reshaper](https://pypi.org/project/arabic-reshaper/)
- [deep_translator](https://pypi.org/project/deep-translator/)

Install dependencies with:

```sh
pip install transformers gradio indic-transliteration unidecode pyarabic arabic-reshaper deep_translator
```

## Usage

1. Open and run the notebook:  
   `MultiLanguage Translator -Fathima Khadija Ramzi.ipynb`

3. The Gradio interface will launch. Enter English text to see translations in all supported languages.

## Files

- [MultiLanguage Translator -Fathima Khadija Ramzi.ipynb]: Main Jupyter notebook with code and instructions.
- `Multilanguage Translator Report - Fathima Khadija Ramzi.pdf`: Project report.

## Author

Fathima Khadija Ramzi  


** Note: some traslators work better than others, due to hugging face having few models that can translate languages like "arabic" effectively. This also could be becasue of different language translating criteria that may apply to different languages - where direct translation does not give the most accurate result.
