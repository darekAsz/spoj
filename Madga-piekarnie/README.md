https://pl.spoj.com/problems/PIEK/

Pani Magda bardzo lubi ciasteczka, i postanowiła że w wakacje zorganizuje wyprawę, której głównym celem jest skosztowanie wyrobów z każdej piekarni. Nasza bohaterka już długo męczy się nad znalezieniem minimalnej długości trasy, która przechodzi przez wszystkie piekarnie tylko raz i wraca do punktu początkowego. Sporządziła już tabelę odległości pomiędzy każdymi piekarniami. Ty jako dobry kolega postanowiłeś pomóc koleżance z tym problemem, i oto nasz cel należy napisać program który wyznaczy najkrótszą trasę, w zamian Magda wynagrodzi Cię ciasteczkami tym więcej im bardziej będzie zadowolona z twej trasy.

Przykład:

Mamy 4 piekarnie: 1,2,3,4.

Tabela odległości wygląda następująco:


1	2	3	4
1	0	4	7	3
2	4	0	5	8
3	7	5	0	6
4	3	8	6	0
Najkrótsza trasa to:18.

Przykładowa możliwość najkrótszej trasy :1->4->3->2->1

Wejście
W pierwszej linii liczba piekarni (n).

Następnie n linii każda składająca się z n liczb (które są　odległościami między piekarniami).

Wyjście
W pierwszej linii obliczona długość trasy.W drugiej linii (n+1) liczb oddzielonych spacjami (od 1 do n włącznie) przy czym pierwsza i ostatnia muszą być takie same, jest to kolejność odwiedzania piekarni.

n<=400

Przykład:
Wejście:
4
0 4 7 3
4 0 5 8
7 5 0 6
3 8 6 0
Wyjście:
18
1 4 3 2 1