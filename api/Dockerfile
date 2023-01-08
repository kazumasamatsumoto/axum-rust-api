FROM rust:1.57
WORKDIR /api
COPY . .

RUN cargo build --release
RUN cargo install --path .

CMD ["api"]