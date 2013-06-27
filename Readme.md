Tacape Dns Tool
=============

This tool has only one usage for now (feel free to add more!), it is a availability name checking script, so you can make a list of possible domains you bring up at a brainstorming session and quickly run through them for a scan.

So create a '~/names.txt' and put a lot of names in it:
```
google
yahoo
abc123qwer
starbucks
crazyyellowunmbrella
```

```bash
 $ tacape dns check_names
```

The first time you use, you will be asked something about your preferences, like which domain suffixes you want to check. Just remember to use ',' on your array answers, like: '.com,.com.br,.io,.us'

Tacape tools
============

This is a work in progrees, I would wait until I have the testing suite implemented to publish this but time is slipping away from me, maybe you can help!

Just fork, add your tool, and make a pull request.

You can test your tools locally just throwing them at the `~/.tacape/tools` folder.

Take a look at the code of the tools already implemented.

All I did was to get the code of scripts I made for myself and put them togheter in a better organized way, this is not the kind of code you should publish, but I believe this is gonna force me to make it better.

Have fun!

This repo is used by [Tacape](https://github.com/lucasmartins/tacape)

Contribute
==========

Have any scripts laying around that you could be sharing? 

Just fork [Tacape Tools](https://github.com/lucasmartins/tacape-tools), add your tool, and make a pull request.

Support
=======

This is an opensource project so don't expect premium support, but don't be shy, post any troubles you're having in the [Issues](https://github.com/lucasmartins/tacape/issues) page and we'll do what we can to help.

License
=======

Tacape Tools is free software under the [MIT license](http://lucasmartins.mit-license.org).