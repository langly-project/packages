Exemplo : Instalando Langly

cd /tmp

curl -L -o langly-0_1_11.tar.gz https://raw.githubusercontent.com/langly-project/packages/main/langly-0_1_11.tar.gz

tar -xzf langly-0_1_11.tar.gz
cd langly
 ./install-langly.sh

Altere para o python para 3.11 (Lembrando que este servidor será exclusivo para o Langly)

update-alternatives --config python

There are 3 programs which provide 'python'.

  Selection    Command
-----------------------------------------------
*  1           /usr/libexec/no-python
   2           /usr/bin/python3
 + 3           /usr/bin/python3.11

Enter to keep the current selection[+], or type selection number: 3


Basta executar langly e será encaminhado ao Langly

Obs: a key foi gerada por : https://console.groq.com
