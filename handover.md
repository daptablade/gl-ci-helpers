# gl-ci-helpers

This repository is a fork of [gl-ci-helpers](https://github.com/pyvista/gl-ci-helpers).

This is a small setup script to help manage visualisation toolboxes in CI
(visualisation toolboxes often expect a screen...).

## Motivation

We forked this as we use this script in our CI setup for MASCOTs Work Package 3.2
you can see the dependency on it at [line 51 of our config](https://github.com/daptablade/mascots_wp3_2/blob/9283c3eb987038c8b905c946dbc5f9d43ae74a43/.circleci/config.yml#L51).

## Development History

We forked it to fix a minor problem where the program would wait for us to type
"yes" which in CI is difficult.

## Limitations

N/A

## Assumptions

N/A

## Lessons Learnt

N/A

## Development Roadmap

N/A

### Current Status

It does what we need it to.

### Future Development

None: ideally we should PR this back to the original repository to contribute.
