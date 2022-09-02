| État | DEL rouge | DEL verte | Utilisateur           | Remarque                                                                                               |
|------|-----------|-----------|-----------------------|--------------------------------------------------------------------------------------------------------|
| 1A   | éteinte   | éteinte   | N/A                   | Attente. Maximum dix (10) s                                                                            |
| 1B   | allumée   | éteinte   | N/A                   | Attente une (1) seconde                                                                                |
| 2A   | éteinte   | éteinte   | Un des boutons pressé | Correspond à la première lettre. Début compteur de temps.                                              |
| 2B   | éteinte   | éteinte   | Un des boutons pressé | Correspond à la deuxième lettre                                                                        |
| 2C   | éteinte   | éteinte   | Un des boutons pressé | Correspond à la troisième lettre                                                                       |
| 2D   | éteinte   | éteinte   | Un des boutons pressé | Correspond à la quatrième lettre                                                                       |
| 3A   | éteinte   | éteinte   | N/A                   | Code invalide. Si troisième tentative, aller en 4. Sinon, compteur incrémenté de 1 et retourner en 1A. |
| 3B   | éteinte   | allumée   | N/A                   | Serrure déverrouillée. Durée 5s                                                                        |