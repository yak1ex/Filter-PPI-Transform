# NAME

Filter::PPI::Transform - Tiny adapter module from PPI::Transform to source filter

# VERSION

version v0.0.2

# SYNOPSIS

    use Filter::PPI::Transform 'PPI::Transform::UpdateCopyright', name => 'Yasutaka ATARSHI';
    # source filter by PPI::Transform::UpdateCopyright is enabled here

# DESCRIPTION

Source filter has unlimited power to enhance Perl.
[PPI](http://search.cpan.org/perldoc?PPI) enables us to modify Perl document easily and it provides [PPI::Transform](http://search.cpan.org/perldoc?PPI::Transform) interface for document transformation.
This module is a tiny adapter from PPI::Transform to source filter.

# OPTION

The first option MUST be a name of subclass of `PPI::Transform`. Rest of the options are passed to the transform class `new`.

# SEE ALSO

- [https://github.com/yak1ex/Filter-PPI-Transform](https://github.com/yak1ex/Filter-PPI-Transform) - Github repository
- [Filter::PPI](http://search.cpan.org/perldoc?Filter::PPI) - Another PPI based source filtering. [PPI::Document](http://search.cpan.org/perldoc?PPI::Document) is used.
- [Filter::Simple](http://search.cpan.org/perldoc?Filter::Simple)

# AUTHOR

Yasutaka ATARASHI <yakex@cpan.org>

# COPYRIGHT AND LICENSE

This software is copyright (c) 2012 by Yasutaka ATARASHI.

This is free software; you can redistribute it and/or modify it under
the same terms as the Perl 5 programming language system itself.
