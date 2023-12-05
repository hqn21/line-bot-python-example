# line-bot-python-example

## About The Project

It is an echo bot using line-bot-sdk-python.  
This branch is specifically designed for Vercel.  
The main branch is [here](https://github.com/henry753951/line-bot-python-example)

## Usage

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2Fhenry753951%2Fline-bot-python-example%2Ftree%2Fvercel&env=access_token,channel_secret,google_generativeai_token)

### Requirements

- Python >= 3.8
- Flask==3.0.0
- line_bot_sdk==3.5.0
- python-dotenv==1.0.0
- google-generativeai==0.2.2

### Installation

1. Install requirements

```sh
pip install -r requirements.txt
```

2. Rename `config.example.py` to `config.py`
3. Change the content in `config.py` to your own information
4. Run the program

```sh
python echo.py
```

```sh
python text.py
```

```sh
python chat.py
```

## License

Distributed under the MIT License. See [LICENSE](LICENSE) for more information.
