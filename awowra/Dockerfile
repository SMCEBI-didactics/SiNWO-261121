FROM alpine:3.15

RUN apk update
RUN apk add bash
RUN apk add wget
COPY ./.bashrc /root/
ADD https://raw.githubusercontent.com/aszadzinski/SMCEBI-TLM/tmp/%C5%9Arodowiska_i_narz%C4%99dzia_wytwarzania_oprogramowania/Zaj%C4%99cia_4/runme ./runme
RUN chmod +x ./runme
ENTRYPOINT ["./runme"]
CMD ["-v"]
