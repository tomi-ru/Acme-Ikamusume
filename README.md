# NAME

Acme::Ikamusume - The invader comes from the bottom of the sea!

# SYNOPSIS

    use Acme::Ikamusume;
    use utf8;
    Acme::Ikamusume->geso('イカ娘です。あなたもperlで侵略しませんか？');
    # => イカ娘でゲソ。お主もperlで侵略しなイカ？

# DESCRIPTION

Acme::Ikamusume module converts text to Ikamusume like talk.
Ikamusume, meaning "Squid-Girl", she is a cute Japanese comic/manga
character ([http://www.ika-musume.com/](http://www.ika-musume.com/)).

Try this module here: [http://ika.koneta.org/](http://ika.koneta.org/). enjoy!

# METHODS

- Acme::Ikamusume->geso( $text )

    About how the conversion, please see [Acme::Ikamusume::Rule](http://search.cpan.org/perldoc?Acme::Ikamusume::Rule) and t/01\_geso.t.

# AUTHOR

Naoki Tomita <tomita@cpan.org>

# LICENSE

This library is free software; you can redistribute it and/or modify
it under the same terms as Perl itself.
