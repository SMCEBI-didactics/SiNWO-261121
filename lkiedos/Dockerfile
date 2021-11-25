From alpine:3.15
Run apk update 
Run apk add bash
Run apk add wget

Copy .bashrc /root/

Run wget -O /root/plik https://github.com/aszadzinski/SMCEBI-TLM/blob/fed581d6b5efb6b8be07214678ce8cbd89456fcb/%C5%9Arodowiska_i_narz%C4%99dzia_wytwarzania_oprogramowania/Zaj%C4%99cia_4/runme
Run chmod +x /root/plik
ENTRYPOINT ["/root/plik", "-v"]
