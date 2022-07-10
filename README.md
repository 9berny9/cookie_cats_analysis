# A/B Test: Cookie Cats
## Zadání
Task sa zaoberá hrou cookie cats v oblasti puzzle games, kde hráč za účelom výhry a
prejdenia do ďalšieho levelu musí posunúť a následne spojiť 3 a viac prvkov do jedného, aby
dané prvky zmizli a on následne utŕžil určité body. (Cookie Cats - Make Buster Go Away By
Throwing Some Cookies (iOS/iPad Gameplay) - YouTube) Ako hráči postupujú v hre sú
vystavení určitým bránam - "gateom", aby urobili transakciu v hre, prípadne zhliadli reklamu.
V tomto projekte bola posunutá jedna z takýchto brán z levelu 30, na level 40 a radi by sme
zanalyzovali vplyv na samotných hráčov a rozhodli o vhodnejšej variante pre cookie cats.

Daný dataset obsahuje atribúty:

* **userid** - A unique number that identifies each player.
* **version** - Whether the player was put in the control group (gate_30 - a gate at level 30) or the
* **group** with the moved gate (gate_40 - a gate at level 40).
* **sum_gamerounds** - The number of game rounds played by the player during the first 14 days
after install.
* **retention_1** - Did the player come back and play 1 day after installing?
* **retention_7** - Did the player come back and play 7 days after installing?
