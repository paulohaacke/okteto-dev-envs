FROM paulohaacke/okteto-dev-rust:1-buster

RUN sh -c "$(curl -sSfL https://release.solana.com/stable/install)" && source ~/.profile

# Smoke test
RUN solana --version

