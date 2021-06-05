FROM paulohaacke/okteto-dev-rust:1-buster

RUN sh -c "$(curl -sSfL https://release.solana.com/stable/install)"
ENV PATH=$HOME/.local/share/solana/install/active_release/bin:$PATH

# Smoke test
RUN . ~/.bashrc && solana --version

