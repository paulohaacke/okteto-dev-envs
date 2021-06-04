FROM paulohaacke/okteto-dev-rust:1-buster

RUN sh -c "$(curl -sSfL https://release.solana.com/stable/install)" && . ~/.profile

# Smoke test
RUN solana --version

