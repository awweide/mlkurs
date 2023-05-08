# Kodebase for mini-kurs i maskinlæring

# Setup
Installer miniconda, et minimalt miljø for å kunne jobbe med Python-kode: typisk https://repo.anaconda.com/miniconda/Miniconda3-latest-Windows-x86_64.exe

Last ned kildekoden i dette Github-repository'et og plasser den et sted du finner den igjen.

Start "Anaconda Powershell Prompt (miniconda3): typisk start-knapp, skriv Anaconda og velg fra autofullfør.

Bruk < cd >-kommandoen til å navigere til den nedlastede koden, for eksempel < cd C:\Users\akeid\Downloads\mlkurs > 

Skriv < conda create env create -n mlkurs -f environment.yml >

Dette vil ta tid og laste ned noen GB fra internett. Mens du venter: last ned vektene til Segment Anything og legg dem sammen med den øvrige koden: https://dl.fbaipublicfiles.com/segment_anything/sam_vit_h_4b8939.pth

Hvis ingen feilmeldinger: skriv < jupyter notebook >. Du vil få opp et nettleser-vindu: vi kan gjøre resten av arbeidet her ifra.

Noen av kodefilene vil automatisk laste ned relativt små filer (~100MB) når de kjøres første gang.
