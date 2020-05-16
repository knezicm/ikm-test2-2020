# Uputstvo za izradu testa

## Part 1
Nakon logovanja na *Raspberry Pi* trebate da predjete u direktorijum pod nazivom *ikm-test-2020*. U njemu se nalazi program ciji je naziv *serial*. Potrebno je u jednom terminalu pokrenuti izvrsavanje ovog programa. Iz drugog terminala poslati inicijale (prva dva slova imena) studenta bez *newline* karaktera, a zatim posmatrati sta ce program koji se izvrsava printati na konzoli. Printanu vrijednost poslati privatnom porukom preko slack-a.

## Part 2
Nakon logovanja na *Raspberry Pi* trebate da predjete u direktorijum pod nazivom *ikm-test-2020*. U njemu se nalazi program ciji je naziv *serial*. Podesiti osciloskop tako da se mjeri signal na prvom kanalu. Nakon sto je osciloskop na *Raspberry Pi* podesen i aktiviran, pokrenuti izvrsavanje programa *serial*. Eksperimentisati sa podesavanjima osciloskopa sve dok se ne dobije upotrebljiv talasni oblik. Na osnovu talasnog oblika procijeniti bitsku brzinu serijske komunikacije i odrediti koji podatak (u heksadecimalnom obliku) se salje u ovom slucaju. Ocitane informacije poslati privatnom porukom preko slack-a, a sliku preuzetog talasnog oblika sa naznacenim start bitom, bitima podataka i stop bitom poslati email-om.

## Part 3
Nakon logovanja na *Raspberry Pi* trebate da predjete u direktorijum pod nazivom *ikm-test-2020*. U njemu se nalazi program ciji je naziv *spi*. Podesiti osciloskop tako da se mjeri signal na oba kanala. Nakon sto je osciloskop na *Raspberry Pi* podesen i aktiviran, pokrenuti izvrsavanje programa *spi*. Eksperimentisati sa podesavanjima osciloskopa sve dok se ne dobiju upotrebljivi talasni oblici. Na osnovu talasnih oblika procijeniti brzinu i mode SPI komunikacije, te odrediti koji podatak (u heksadecimalnom obliku) se prenosi u datom slucaju. Ocitane informacije poslati privatnom porukom preko slack-a, a sliku preuzetog talasnog oblika poslati email-om.

## Part 4
Modifikovati program sa laboratorijskih vjezbi tako da se citaju vrijednosti registara OFSX, OFSY i OFSZ preko I2C interfejsa. Procitane vrijednosti treba printati u konzoli. Napisani program pokrenuti na *Raspberry Pi* platformi, a ocitane vrijednosti poslati privatnom porukom preko slack-a. Takodje, podesiti osciloskop i "uhvatiti" kompletnu I2C transakciju kojom se citaju ove vrijednosti (oba kanala). Sliku talasnog oblika i izvorni kod napisanog programa poslati email-om.

Srecan rad!
