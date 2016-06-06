##corewar

###Assembleur

Prend un fichier .s et le compile en bytecode .cor

**Option**
- [-n] Décompile le bytecode .cor en .s

###Machine Virtuelle

Fait office d'arène dans laquelle les "champions" (.cor) s'executent.
Le champion gagnant et annoncé quand tous les processus sont mort.

**Options**
- [-v] Active le viewer, permettant de voir la mémoire de la machine, les processus en cours, les champions encore en vie, le cycle en cours et d'autres informations utiles.
- [-dump nbr_cycle] Fait un dump de la mémoire au cycle indiqué.
- [-n number] Assigne le numéro indiqué au champion qui suit.
- [-s] Mode silence, inhibe les messages des fonctions live et aff.

Projet réalisé à 3.
