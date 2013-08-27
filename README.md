# NAME

Voson::Plugin::View::Xslate - A plugin for Voson that provides template mechanism

# SYNOPSIS

    use Voson plugins => [
        'View::Xslate' => +{
            syntax => 'Kolon',
            path   => [ qw/ view / ],
        },
    ];
    

    app {
        [200, [], render('index.html', { name => 'myapp' })];
    };

# DESCRIPTION

Voson::Plugin::View::Xslate provides render DSL for rendering template.

# DSL

## render $template\_file \[, $hashref\];

Returns rendered content.

# LICENSE

Copyright (C) ytnobody.

This library is free software; you can redistribute it and/or modify
it under the same terms as Perl itself.

# AUTHOR

ytnobody <ytnobody@gmail.com>
