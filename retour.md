
[lXX]: Ligne XX

# Hosts

Farpait.

# playbook1

Bravo !

3 remarque:
  1. [l29]: peut-etre probablement rendu plus lisible.
  2. [l37]: dommage d'avoir effacer `.bashrc` la consigne demander de charger `alias` dans `.bashrc`.
  3. [l3]: que fait cette ligne ? pourquoi root ?

Sinon c'est un tres bon travaille et tu aurai pu le montrer en correction.

# Playbook 1 retour

Excellent !
Petite questions:
`insertafter=EOF` <= c'est quoi `EOF` ?
`regexp='^{{ item.username }} .*'` <= `regexp` tu sais ce que sais ?

# Part2

Propre !

Dans le playbook_nginx, C'est treees bien jouer d'avoir changer la page par default pour verifier la
config.

Les reste des playbook est nickel !
(peut-etre un nom plus clair pour les clef mais details).

Tiens: `acme-staging` :p (c'est pas grave mais du coup les certif sont pas totalement valid si je ne
m'abuse)

# Part3

Pffffiou, rien qu'en voyant the one playbook, tu peux vraiment etre fiere de toi. C'est des notions
que je ne vous est pas forcer a voir. Bravo !
Je cherche des remarque constructive, mais sur ce fichier la, nickel.


Dans l'ensemble beau travaille.
Si je n'ai qu'une remarque a faire, c'est pas mal de template, alors que tu aurais pus profiter de
la force de jinja (avec des `{% if ssl is defined %}{% else %}`). Mais sinon Good Job !
