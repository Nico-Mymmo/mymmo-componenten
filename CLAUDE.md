# Mymmo Componenten

Dit project bevat enkel de WordPress-plugin **Mymmo Componenten**
(`wp-plugin/mymmo-cards`), de bouwstenen waarmee marketing pagina's zet op
syndicoach.be en openvme.be. Het staat apart van de Operations Manager (die is
prive) zodat de controles hier gratis blijven werken en er niets van de OM
openbaar staat.

**Lees eerst het regelboek: `wp-plugin/mymmo-cards/CLAUDE.md`.** Daar staat met
wie je praat (geen ontwikkelaars: gewone taal, geen vaktaal), hoe een component
gebouwd wordt, de huisstijl, de review (`/huisstijl-review`) en de stempel
(`bash wp-plugin/huisstijl/stempel.sh "..."`).

Van idee tot op de site: werk op een branch `component/<naam>`, zet de stempel
na de review, en push. De job "Naar de site" voegt samen en brengt uit; de
sites werken zich binnen enkele minuten bij
(`wp-plugin/mymmo-cards/includes/class-updates.php` haalt de releases van DIT
project).

Wat hier niet hoort: code, gegevens of sleutels van de Operations Manager. Dit
project is openbaar.
