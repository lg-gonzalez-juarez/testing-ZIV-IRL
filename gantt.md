gantt
        dateFormat  YYYY-MM-DD
        title Cronograma Pruebas Homologación ZIV-IRL

section Sobreintensidad
Bloqueo Armonicos :done, 2017-07-24, 90d 
50 (PH)   :done, t50P, 2017-07-24, 2017-09-29
50 (N)   :done, 2017-08-04, 2017-09-29
50 (Q)   :done, 2017-08-07, 2017-11-03
50 (NS)   :done, 2017-08-10, 2017-10-06
51 (PH)   :done,  2017-08-09, 2017-10-11
51 (N)   :done,  2017-08-22, 2017-10-18
51(Q)    :done,  2017-10-16, 2017-10-18
51(NS)  :done,  2017-10-16, 2017-10-17
50/51 (V)   :done,  2017-10-26, 2017-10-27
51 NS EPTR_C  :done,  2017-10-06, 2017-10-31

51  NI/C           :done, crit,  2017-08-20, 30d 

50 (BF)               :active,   t50BF, 2017-08-06, 4d 
50 (FD)               : active, after t50BF, 4d 
85 (esq teleprotección) :active, after t50BF, 10d

section Direccional
67 fase :done,  2017-07-27, 2017-10-10
67NS  :done,  2017-10-19, 2017-10-25
67N   :done,  2017-10-10, 2017-10-11
67NI/C :done,  2017-10-18, 2017-10-25
67Q         :crit,  3d
67 sec pos   :crit, 5d
32P/Q :crit, active, 2017-11-07,2017-11-09

section Tensión Frecuencia
27     :done,2017-11-06,1d
59  :done,  2017-11-06, 1d
59N    :done,  2017-11-07, 1d
59V/Hz  :crit, 3d
47  : ¡active, 2017-11-06,1d
81M  :active, crit, 2d
81m  :active, crit, 2d
81D :active, crit, 2d

section Varios
RPSL1 :crit, 2017-12-12, 4d
46      :active,2017-11-15,1d
37 : active, 2017-11-15,1d

49 :crit, 2017-12-12, 4d
78 :4d
CLP:4d
87NL:4d

60 :done, 2017-11-13,1d
60VT :done, 2017-11-14,1d
60CT:crit, 2d

25 :done, 2017-11-21,2017-11-23 

79:crit, 2017-12-14,4d
Coord seq:4d
sup bobinas:4d
CBCM:4d
21FL:4d
Discrepancia polos:4d
SCBR1:4d
RDEL1:4d
PHSTCRT1:4d
RSTM1:4d
PTRC:4d

        Create tests for renderer           :2d
        Add to mermaid                      :1d
