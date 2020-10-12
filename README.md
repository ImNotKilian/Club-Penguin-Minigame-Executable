# Card-Jitsu Snow Server Emulator


## Installation

- This guide expects that you have a working instalation of <a href="https://github.com/solero/houdini-asyncio/tree/master/houdini">`houdini-asyncio`</a> and <a href="https://github.com/solero/dash">`dash`</a>

### Setup

> Let's go, first execute this command

```
cd Card Jitsu Snow
```

> Now that we are in the correct folder, let's install the required modules:

```
pip install -r requirements.txt
```

> We are almost done. Now, just run this command and you're done:

```
python app.py
```

## Adding New Tags

```py
@Instance.register("tagname")
def functionname(client, arg):
    client.sendLine("[TAG]|arg1|arg2")
```


## Contributing

> DM Kilian#6666 on Discord



## Team


| <a href="https://github.com/ImNotKilian" target="_blank">**Kilian**</a>



## Support

If you need any help just contact me!


- **Kilian**#6666

 > Remember that is my Discord Username!
