FROM paulohaacke/okteto-dev-rust:1-buster

RUN sh -c "$(curl -sSfL https://release.solana.com/stable/install)" \
 && export PATH=~/.local/share/solana/install/active_release/bin:$PATH

RUN solana --version

