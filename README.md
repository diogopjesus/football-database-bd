# Football Database
Project developed for the 'Databases' course. Written in TSQL database-wise and c# interface-wise.


# Notes

- We dont create the table Person because a person is mandatory to be either one and only one of the following: Player, Coach, Referee
- In team stat, primary key is gameID and home_team BIT, to only be possible to add 2 instances to 1 game
- Only club based database, not national teams


# TRIGGERS:

    JOGOS À MESMA HORA NO MESMO ESTÁDIO
    JOGOS À MESMA HORA DA MESMA EQUIPA
