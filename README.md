Alfred Workflow: Authy
======================

An Alfred workflow for Authy that generates TOTP and copies them to the clipboard.


Installation
------------

Create a `~/.config/authy` file with your secrets:

```ini
[Google]
secret=xxxxxxxxxxxxxxxxxx

[Evernote]
secret=yyyyyyyyyyyyyyyyyy
```

A `~/.authy` file still works if there isn't one in `~/.config`.

[Download](https://github.com/stevelacey/alfred-authy/raw/main/Authy.alfredworkflow) and import to Alfred


Dependencies
------------

- Alfred with PowerPack
- Python3


Development
-----------

After modifying files locally, run `bundle.sh` to update the workflow file, and
commit the workflow file update to this repository.

Run the tests with `python3 -m unittest discover -s tests`.


Acknowledgment
--------------

- Forked from [Alfred Workflow: Google Authenticator](https://github.com/moul/alfred-workflow-gauth)
  - [Manfred Touron](https://github.com/moul)
  - Licensed under MIT
- Original alarm clock icon
  - [Alex Auda Samora from The Noun Project](http://thenounproject.com/razerk/)
  - Licensed under Creative Commons Attribution
- Status & signs icons
  - [Hereldar Terkenya](http://hereldar.deviantart.com/)
  - Licensed under a Creative Commons Attribution-Share Alike 3.0 License
- Original source code
  - [Manfred Touron](https://github.com/moul)
- Serial contributor
  - [Gilberto Olimpio](https://github.com/golimpio)


License
-------

MIT
