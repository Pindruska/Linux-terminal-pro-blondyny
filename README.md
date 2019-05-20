# Linux-terminal-pro-blondyny

Ctrl+alt+T – spustí terminál
příkaz exit – ukončí
clear – vymaže terminál
TAB - pomáhá dokončovat (např cd Doc TAB doplní na Documents)
Ctrl+C - ukončí akci v terminálu
	Ctrl+Z - když nefunguje předchozí

aktivace virtualniho prostredi: source ~/naucse-python/venv/bin/activate
	na EN klavesnici je to alt gr a tlacitko se zavorkami u Enteru
	na české je to pravý alt+A :-)


pwd – ve kterém jsem adresáři (path)
ls – vypíše soubory v adresáři (ls -a I ty skryté)
	ls -lah - vypíše včetně velikosti
cd – samo cd přepne do home
	cd .. - o úroveň výš (bacha na tu mezeru!)
	cd jmenoadresare – do adresare, pokud ma viceslovny nazev, musi se dat “\”

mkdir – vytvoří adresář, pokud víceslovný, pak zase s “\”
rmdir – odstraní adresář(prázdný)
rm – odstraní adresář i se soubory!!
touch - vytvoří nový soubor (touch test.py)

locate slovo - vyhledá soubory obsahující slovo
	locate -i slovo - nebude hledět na velikost písmen ve slově
	locate *slovo*jineslovo*jestejineslovo - hledá soubor, kde se objevují všechna slova,
		oddělujeme *
cat soubor - zobrazí content souboru

sudo - SuperUserDo
sudo apt-get (install) co - instaluje packages
INSTALACE PYTHONNICH MODULU: sudo apt-get install python3-modul


du soubor - diskUsage
df složka - to samé pro složku

zip, unzip - zazipovat, odzipovat
