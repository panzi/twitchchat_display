# Synopsis

A python app designed for the Raspberry Pi that displays twitchchat and youtube chat

# Usage

You can try and grab depedencies using `try_get_dependencies.py`, getting pygame installed can be a fun time sometimes.

Fill in the supplied `config_example.txt` with your values then rename it config.txt

If you are using youtubechat you will have to supply the `oauth_creds` file generated using the python-youtubechat project

Now you can just run `main.py`, `-d` for debug messages, `-t` to subscribe to featured channels for testing

# Dependencies

 * [python-twitchchat](https://github.com/shughes-uk/python-twitchchat)
 * [python-twitchevents](https://github.com/shughes-uk/python-twitchevents)
 * [python-youtubechat](https://github.com/shughes-uk/python-youtubechat)
 * pygame
 * fonttools
 * webcolors
 * yaml
 * pillow
 * pyyaml
