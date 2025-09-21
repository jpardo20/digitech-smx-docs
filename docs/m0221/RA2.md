# RA2 — Mesures elèctriques i fonts d'alimentació

## Objectius específics
- Utilitzar el **multímetre** de manera segura per mesurar tensió, intensitat i resistència en equips informàtics.
- Calcular consums i **potència** dels components i dimensionar una **PSU** adequada amb marge de seguretat.
- Verificar **connectors d'alimentació** (ATX 24-pin, EPS 8-pin, PCIe, SATA) i identificar avaries bàsiques.
- Aplicar procediments de **PRL** (absència de tensió, ordre i neteja) en les mesures i intervencions.

## Continguts clau
- Magnituds: V, A, Ω; llei d'Ohm (V = I·R) i potència (P = V·I).
- Tipus de corrent: **CC** (PC intern) i **CA** (mains); polaritat i riscos.
- Multímetre: rangs, precisió, mode continuïtat, prova de díodes.
- Fonts d'alimentació: **ATX** (estàndard, eficiència 80 PLUS, rails +12V/+5V/+3.3V), **PSU modular**.
- Connectors i pinouts habituals: ATX 24, EPS 8, PCIe 6/8, SATA, Molex.
- Càlcul de càrrega i **marge** (headroom) per a PSU.

## Procediment bàsic de mesura amb multímetre
1. **PRL**: desconnectar de la xarxa, descarregar càrregues, comprovar absència de tensió.
2. Inspecció visual de **cables i connectors** (danys, pins torts, olor a cremat).
3. Configuració del multímetre:
   - Tensió **CC** per aixetes internes, **CA** per presa mural.
   - Continuïtat / Ω per verificar cables i fusibles.
4. Mesures típiques:
   - **5V/12V** a connectors SATA/Molex (amb adaptador/prova sense risc).
   - **Standby 5VSB** amb la PSU en espera.
   - Test de continuïtat en cablejat del panell frontal.
5. Registre de lectures i conclusions; accions correctives.

## Activitats proposades
- **A1. Posada a punt del multímetre** (15’): identificació de funcions i rangs; prova en una pila de 1,5V.
- **A2. Mesures segures** (30’): simulació de mesura de 5V i 12V sobre maqueta/cable de pràctiques.
- **A3. Continuïtat i pinouts** (30’): verificar cable SATA i panell frontal; dibuixar pinout bàsic.
- **A4. Càlcul de potència** (45’): donats components, calcular **TDP total**, afegir 30% de marge i **proposar PSU**.
- **A5. Diagnosi d’alimentació** (30’): casos curts (PC que s’apaga, no arrenca, ventilador PSU a salts); decidir proves i causa probable.

## Evidències i instruments d'avaluació
- Full de **lectures del multímetre** (pes 25%).
- Exercici de **dimensionament PSU** (pes 35%). 
- **Qüestionari curt** de seguretat i pinouts (pes 20%).
- **Actitud i PRL** (pes 20%).

## Riscos i PRL
- Electrocució (CA), curtcircuits i dany de components. Treballar sempre sense tensió i utilitzar eines adequades.
- Evitar sondes relliscoses; estabilitzar la peça i utilitzar puntes amb fundes.

## Recursos
- Annexos: full de fórmules, pinouts i plantilla de càlcul de PSU.
- Apunts visuals: esquemes de connectors i exemples de càlcul.

_Darrera actualització: 2025-09-21_
