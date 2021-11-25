FROM alpine:3.15

RUN apk update
RUN apk add bash
RUN apk add wget

#tutaj docker nie łapał ~/.bashrc, także sobie go przeniosłem do obecnego katalogu
COPY .bashrc /root

RUN wget -O /root/runme https://raw.githubusercontent.com/aszadzinski/SMCEBI-TLM/tmp/%C5%9Arodowiska_i_narz%C4%99dzia_wytwarzania_oprogramowania/Zaj%C4%99cia_4/runme
RUN chmod +x /root/runme

ENTRYPOINT ["/root/runme", "-v"]
