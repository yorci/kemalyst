FROM drujensen/crystal:0.20.0

WORKDIR /app/user

ADD . /app/user

RUN crystal deps

CMD ["crystal", "spec"]

