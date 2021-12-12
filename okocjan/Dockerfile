FROM alpine:3.15
 
RUN apk update
RUN apk add bash
RUN apk add wget
 
COPY .bashrc /root
 
RUN wget -O /root/runme https://github.com/aszadzinski/SMCEBI-TLM/blob/ab0217fc3f2d9472867e0789c5db3227429bdf1e/%C5%9Arodowiska_i_narz%C4%99dzia_wytwarzania_oprogramowania/Zaj%C4%99cia_4/runme
RUN chmod +x /root/runme
 
ENTRYPOINT ["/root/runme", "-v"]
