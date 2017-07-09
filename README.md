# Asterisk Samples

## Sample 1

2 phones and 2 extensions

### Usage

Start Asterisk in debug mode:

```bash
$ asterisk -cvvv
```

Show connected phones:

```bash
CLI> sip show peers
```

* Type 12 on salon phone to call bureau phone
* Type 11 on bureau phone to call salon phone
