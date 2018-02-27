# tardibot9000
Just so tired of you idiots, especially you Mike.

Trolls be trollin', and they love burning your time - fb is a sick addiction for many, so what better way to keep than busy than to leave them chatting endlessly to a bot!

Features;
- a delayed randomly-timed reply
- contextual replies
- ability to scan targets previous conversations for trigger points
- extra thread to deliver infinite "someone is typing" payload

Tech;
- docker
- webdriver
- tor proxy
- tensorflow machine learning 

## setup

```
git clone https://github.com/hook-s3c/tardibot9000
cd tardibot9000

sudo pip install requirements.txt
python ./letsgo.py
```

## docker

```
docker build . hook-s3c/tardibot9000
docker run -it --entrypoint letsgo.py hook-s3c/tardibot9000 

```
