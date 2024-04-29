# 1 : Create new Workspace:

**Preconditions:**

- Choisir la dimension (Hauteur et largeur)
- Choisir un nom de fichier
- Espace de stockage suffisant

**Postconditions:**

- Le Workspace est créé

|                                          | 1   | 2   | 3   | 4   | 5   | 6   | 7   | 8   |
| ---------------------------------------- | --- | --- | --- | --- | --- | --- | --- | --- |
| Choisir la dimension(Hauteur et Largeur) | T   | T   | T   | F   | T   | F   | F   | F   |
| Choisir un nom de fichier                | T   | T   | F   | T   | F   | T   | F   | F   |
| Espace de Stockage suffisant             | T   | F   | T   | T   | F   | F   | T   | F   |
| Postconditions                           |     |     |     |     |     |     |     |     |
| Le Workspace est créé                    | T   | F   | F   | F   | F   | F   | F   | F   |

# 2 : Use tool:

**Preconditions:**

- Un tool est choisi
- Un workspace est ouvert

**Postconditions:**

- Modifier le workspace (faire la peinture de tableau)

|                         | 1   | 2   | 3   | 4   |
| ----------------------- | --- | --- | --- | --- |
| Un tool est choisi      | T   | T   | F   | F   |
| Un Worskpace est ouvert | T   | F   | T   | F   |
| Postconditions          |     |     |     |     |
| Modifier le Workspace   | T   | F   | F   | F   |

# 3 : Transform Style:

**Preconditions:**

- Un Workspace est ouvert
- Un style est choisi

**Postconditions:**

- Le style de tableau est transformé

|                                    | 1   | 2   | 3   | 4   |
| ---------------------------------- | --- | --- | --- | --- |
| Un Workspace est ouvert            | T   | T   | F   | F   |
| Un style est choisi                | T   | F   | T   | F   |
| Postconditions                     |     |     |     |     |
| Le style de tableau est transformé | T   | F   | F   | F   |
