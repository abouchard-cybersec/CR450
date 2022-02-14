# CR450 - Detection et reponses aux Cyber incidents (BLUE TEAM)

Quelques outils que j'ai cree durant le cours. La nomenclature des outils est la suivante:

"blue|red" "phase du processus" "description"

# Le Processus de reponse aux Cyber Incidents

1. Preparation
   - Mise en place de politiques
   - Mise en place du processus de reponse
   - Determiner les SLA et RACI
   - Mise en place du kit de demarrage
   
2. Identification
   - Detection
   - Analyse
3. Confinement
4. Eradication
5. Retablissement
6. Lessons Learned

## Identification

### Detection

### Analyse

#### blue_analyze_sniffnmap (tcpdump --> nmap --> wireshark)
Un script simple qui automatise les taches pour l'analyse du traffic avec un host destination dans Wireshark. 
```bash
sudo ./blue_analyze_sniffnmap.sh -t targetlist -o outputpcapfile -V

# requiert sudo pour tcpdump
# -V  pour le mode verbose
# -h  pour afficher l'aide
```
