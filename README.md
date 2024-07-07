Pliki CSV zawierające informacje na temat białek ludzkiego proteomu z bazy AlphaFold. 
W pliku 'plddt_for_human_proteome.csv' kolumny oznaczają:

-path - identyfikator UniProt

-group - grupa, do której zakwalifikowane zostało białko w wyniku analizy opisywanej w pracy licencjackiej,

-before_cumulation - rozkład prawdopodobieństw typów węzłów w białku na podstawie wielomianu Alexandera

-length - długość białka

-plDDT - średnia miara jakości przewidywanej struktury.


W pliku 'no_leader_cumulation_with_threshold_48.csv' przedstawione są jedynie struktury zakwalifikowane do grupy NoLeader, dla których stosowany był algorytm kumulacji prawdopodobieństw. 
Zawiera on dodatkowo kolumnę 'after_cumulation' przedstawiającą wyniki działania algorytmu.
