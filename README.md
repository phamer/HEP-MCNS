# NAME

HEP::MCNS - converts HEP MC numbers into particle names

# VERSION

version 0.01

# SYNOPSIS

        use HEP::MCNS 'particle_name';
        my $electron_name = particle_name( 11 );
        my $bzero_name = particle_name( 511 );

# FUNCTIONS

## particle\_name()

takes the Monte Carlo number as input and prints the particle name 

# AUTHOR

Philipp Hamer <philha@cpan.org>

# COPYRIGHT AND LICENSE

This software is copyright (c) 2015 by Philipp Hamer.

This is free software; you can redistribute it and/or modify it under
the same terms as the Perl 5 programming language system itself.
