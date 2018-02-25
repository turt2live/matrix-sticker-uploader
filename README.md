# matrix-sticker-uploader
A script to upload stickers into matrix media repo.

# Requirements

* Python 3 environment
* Windows (if using this fork)

```
virtualenv env
./env/Scripts/activate
pip install -r requirements.txt
```

# Running

```
python --homeserver https://t2bot.io --token <your_token> <image file names...>
```

# Output

```
[
    {
        "filename": "images/test.png",
        "mxc": "mxc://t2bot.io/totally_not_a_fake_id",
        "mimetype": "image/png"
    }
]
```
