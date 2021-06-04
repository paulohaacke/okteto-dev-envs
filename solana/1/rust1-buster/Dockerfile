FROM paulohaacke/okteto-dev-rust:1-buster

RUN sh -c "$(curl -sSfL https://release.solana.com/stable/install)"
RUN echo "export PATH=~/.local/share/solana/install/active_release/bin:\$PATH" >> ~/.bashrc

# Smoke test
RUN . ~/.bashrc && solana --version

