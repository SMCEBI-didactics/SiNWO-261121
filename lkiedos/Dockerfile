From alpine:3.15
Run apk update 
Run apk add bash
Run apk add wget

COPY .bashrc /root/

Run wget -O /root/plik https://raw.githubusercontent.com/aszadzinski/SMCEBI-TLM/tmp/Środowiska_i_narzędzia_wytwarzania_oprogramowania/Zajęcia_4/runme
Run chmod +x /root/plik
ENTRYPOINT ["/root/plik", "-v"]

