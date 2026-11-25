# Ievade
1. Pajautāt spēlētājam skaitli no 1-10
2. Nolasīt spēlētāja skaitli
# Apstrāde
3. Ģenerēt nejaušu skaitli no 1 līdz 10
4. Salīdzināt spēlētāja skaitli ar ģenerēto skaitli 
# Izvade
5.  Ja skaitļi sakrīt, parādīt "Tu uzvarēji"
6. Ja skaitļi nesakrīt, parādīt "Tu zaudēji"
7. Parādīt pareizo skaitli

| Mainīgā vārds      | datu tips| ko glabā                      |
| :----------------  | :------: | ----:                         |
|nejaušais_skaitlis  |   int    |datora ģenerēto skaitli        |
|speletaja_skaitlis  |   int    |spēlētyāja ieadīto skaitli     |
|starpība            |  int     |starpību starp abiem skaitļiem |

starpība=abs(spēlētāja skaitlis-nejaušais skaitlis)

spēlētāja_skaitlis- tiek ievadīts ar input().
nejaušais_skaitlis- tiek nejauši ģenerēts.
starpība- tiek aprēķināta ar formulu.
Ja starpība ir 0, spēlētās uzvar. Citādi spēlētājs zaudē

Mazi skaitļi:
starpība= abs (1-2)=1
Vidēji skaitļi:
starpība=abs(5-5)=0
Lieli skaitļi:
starpība=abs(10-8)=2


