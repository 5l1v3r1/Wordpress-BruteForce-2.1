# WordPress-BruteForce-2.1
Brute force wordpress XML-RPC thread

<b>Não ative as funções desativadas pois elas estão em manutenção e vão causar o mal funcionamento do script</b>

import _thread<br>
import json<br>
import requests<br>
import argparse as arg<br>
import sys<br>
import os<br>
import time<br>
import re<br>
import socket

[!] Brute/Scanner cms (wordpress)<br>
[!] Mass brute force<br>
[!] Desenvolvido por ./Cryptonking (B4l0x)

--lista - Lista de sites wordpress alvos<br>
--wordlist - Wordlist de senhas<br>
--usuario - <b>Somente use essa opção para brutar usuarios unicos, o script captura usuarios automaticamente.</b><br>
--reverse - <b>Use essa opção para pegar outros sites wordpress do mesmo servidor</b><br>
--sleep - Regule a velocidade dos threads, mas cuidado que isso pode atrapalhar <b>(melhor deixar padrão)</b>


