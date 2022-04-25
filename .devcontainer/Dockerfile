# See here for image contents: https://github.com/microsoft/vscode-dev-containers/tree/v0.231.6/containers/ubuntu/.devcontainer/base.Dockerfile

# [Choice] Ubuntu version (use hirsuite or bionic on local arm64/Apple Silicon): hirsute, focal, bionic
# ARG VARIANT="hirsute"
FROM perl:5.34.1-buster

# [Optional] Uncomment this section to install additional OS packages.
# RUN apt-get update && export DEBIAN_FRONTEND=noninteractive \
#     && apt-get -y install --no-install-recommends <your-package-list-here>
RUN cpan -f Test::Needs
RUN cpan -f Package::Stash
RUN cpan -f Class::Load
RUN cpan -f Class::Refresh
RUN cpan -f Moose
RUN cpan -f Perl::LanguageServer
