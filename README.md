# Google-Home-on-Raspberry-Pi

How to install google assistant to your raspberry pi, also known as google home. this is a early adoption of intergrading google home to our raspberry pi, more tutorials will follow soon. thanks for the view!!

parts:

USB Microphone ► http://amzn.to/2qCx4zY

Raspberry Pi 3 ► http://amzn.to/2oquADd

websites:

developer console

https://console.cloud.google.com/cloud-resource-manager

google assistant tutoral

https://developers.google.com/assistant/sdk/prototype/getting-started-pi-python/config-dev-project-and-account

command line:

    sudo apt-get install python3-dev python3-venv

    sudo apt-get install portaudio19-dev libffi-dev libssl-dev

    python3 -m venv env

    env/bin/python -m pip install pip setuptools –upgrade

    source env/bin/activate

    python -m pip install google-assistant-sdk[samples]

    python -m googlesamples.assistant
