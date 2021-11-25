From alpine:3.15
Run apk update
Run apk add bash
Run apk add wget

COPY .bashrc /root/

RUN wget -O /root/plik https://raw.githubusercontent.com/aszadzinski/SMCEBI-TLM/tmp/%C5%9Arodowiska_i_narz%C4%99dzia_wytwarzania_oprogramowania/Zaj%C4%99cia_4/runme
RUN chmod +x /root/plik
ENTRYPOINT ["/root/plik", "-v"] 
