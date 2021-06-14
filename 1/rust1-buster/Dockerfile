FROM paulohaacke/okteto-dev-rust:1-buster

RUN curl -sSfL https://release.solana.com/stable/install -o install.sh && chmod +x install.sh && ./install.sh --no-modify-path --data-dir /opt/solana/install stable && rm -f install.sh
ENV PATH="/opt/solana/install/active_release/bin:$PATH"

# Smoke test
RUN solana --version

