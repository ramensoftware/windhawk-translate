# Windhawk translation

To translate Windhawk, pick one of the
[YAML](https://en.wikipedia.org/wiki/YAML) files (for example, [en.yml](en.yml)
for English), and translate the text on the right side of the colon.

For example, here's an excerpt from the English translation file:

```yml
app:
  appHeader:
    home: "Home"
    explore: "Explore"
    settings: "Settings"
    about: "About"
```

In this excerpt, the "Home", "Explore", "Settings", and "About" are the strings
that need to be translated.

## Contributing via GitHub

If you're familiar with GitHub, you can contribute a translation by submitting a
pull request.

## Contributing via email

If you're not familiar with GitHub, you can [download the translation
files](https://github.com/ramensoftware/windhawk-translate/archive/refs/heads/main.zip),
translate one of the files, and [send it via
email](https://ramensoftware.com/contact).

## Ampersand (`&`) prefixes in program translation

Some of the strings in the program language files contain the ampersand symbol
([example](https://github.com/ramensoftware/windhawk-translate/blob/05348552fd2e48b3fdc344a6a45b7c872a55af67/en.yml#L16)).

The ampersand symbol is used to designate an access key shortcut. You can read
more about it
[here](https://learn.microsoft.com/en-us/dotnet/desktop/winforms/controls/how-to-create-access-keys?view=netdesktop-8.0).

While translating, you can omit the ampersand symbols, but keeping them in your
translation will ease the usage of the program in your language.
