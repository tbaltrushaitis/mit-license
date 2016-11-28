# A permalink for MIT License

You can send a full JSON file to the API, not *just* the copyright, so this works too:

```bash
curl -d'{ "copyright": "Tomas", "url": "http://tbaltrushaitis.com", "email": "tomas@baltrushaitis.com", "format": "txt" }' http://tbaltrushaitis.mit-license.org
```

## The user.json file

Available fields:

* copyright (required)
* url
* email
* format
* gravatar
* version
* theme

### copyright

This file contains a JSON object containing at least a
`copyright` property:

```json
{
  "copyright": "Tomas, http://tbaltrushaitis.com"
}
```
Means I can now link to: http://tbaltrushaitis.mit-license.org.

### url

```json
{
  "copyright": "Tomas, http://tbaltrushaitis.com",
  "url": "http://tbaltrushaitis.com"
}
```

### email

```json
{
  "copyright": "Tomas, http://tbaltrushaitis.com",
  "url": "http://tbaltrushaitis.com",
  "email": "tomas@baltrushaitis.com"
}
```

### format

And if you want your license to appear as plain text, just add the
`format` property (currently only `txt` and `html` are supported):

```json
{
  "copyright": "Tomas, http://tbaltrushaitis.com",
  "url": "http://tbaltrushaitis.com",
  "format": "txt"
}
```

### gravatar

```json
{
  "copyright": "Tomas, http://tbaltrushaitis.com",
  "url": "http://tbaltrushaitis.com",
  "email": "tomas@baltrushaitis.com",
  "gravatar": true
}
```

### Themes

```json
{
  "copyright": "Tomas, http://tbaltrushaitis.com",
  "url":  "http://tbaltrushaitis.com",
  "theme": "afterdark"
}
```

Current available themes:

* default - [preview](http://mit-license.org) (by
  [@remy](http://github.com/remy),
  [@raphaelbastide](http://github.com/raphaelbastide) &
  [@evertton](http://github.com/evertton))
* flesch - [preview](http://jsbin.com/ufefid/3) (by
  [@flesch](http://github.com/flesch))
* eula-modern - [preview](http://jsbin.com/ExiVida/1/) (by [@sauerlo](http://github.com/lsauer))  
* afterdark - [preview](http://jsbin.com/ivufon/4) (by [@rmartindotco](http://github.com/rmartindotco))
* orange - [preview](http://jsbin.com/uzubos/2) (by [@kirbylover4000](http://github.com/kirbylover4000))
* plaintext - [preview](http://jsbin.com/uzubos/4) (by [@barberboy](https://github.com/barberboy))
* double-windsor - [preview](http://jsbin.com/uzubos/5/) (by [@desandro](https://github.com))
* cherry - [preview](http://jsbin.com/ufefid/5/) (by [@mustafa-x](https://github.com/mustafa-x))
* white cherry - [preview](http://jsbin.com/uzezas/2/) (by [@mustafa-x](https://github.com/mustafa-x))
* blackwood - [preview](http://jsbin.com/uzezas/) (by [@mustafa-x](https://github.com/mustafa-x))
* hipster-gray - [preview](http://jsbin.com/ivufon/10) (by [@noformnocontent](https://github.com/noformnocontent))
* xtansia - [preview](http://jsbin.com/ereren/1/) (by [@tomass1996](https://github.com/tomass1996))
* magic-mint - [preview](http://jsbin.com/obibot/1/) (by [@ekhager](http://github.com/ekhager))
* default-dark - [preview](http://jsbin.com/uhagaw/10) (by
  [@remy](http://github.com/remy),
  [@raphaelbastide](http://github.com/raphaelbastide) &
  [@evertton](http://github.com/evertton))
* black-beauty - [preview](http://jsbin.com/dovivu) (by [@evertton](http://github.com/evertton))
* silver-style - [preview](http://jsbin.com/erezijI/2) (by [@dev-dipesh](https://github.com/Dev-Dipesh))
* friendly - [preview](http://jsbin.com/hilula) (by [@evertton](http://github.com/evertton))
* opensans - [preview](http://jsbin.com/UfepUvah) (by [@pburtchaell](http://github.com/pburtchaell))
* solarized - [preview](http://jsbin.com/yimax/1) (by [@anmoljagetia](http://github.com/anmoljagetia))
* willpower - [preview](http://jsbin.com/piheyicoyi/1) (by [@willpowerart](http://github.com/willpowerart))
* rokkitt - [preview](http://jsbin.com/zudayiqeco/1) (by [@luizpicolo](http://github.com/luizpicolo))
* material - [preview](http://ahaasler.github.io/mit-license-material-theme/) (by [@ahaasler](https://github.com/ahaasler)). *Available colours: blue gray (default), red, pink, purple, deep purple, indigo, blue, light blue, cyan, teal, green, light green, lime, yellow, amber, orange, deep orange, brown and grey. To use a specific colour, add it as a dash-separated suffix on the theme name, such as `material-deep-orange`.*

## License

And of course:

MIT: http://tbaltrushaitis.mit-license.org
