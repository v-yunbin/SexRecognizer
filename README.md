# RozpoznawaniePlci
Zadanie na KCK, sygnały

- Metoda HPS (Harmonic Product Spectrum)
- Metoda DEC2 i DEC3 (Decimate) - można wymnożyć sygnały (?)

Szukanie lokalnych maksimów w wielokrotnościach np. 125 Hz

Po zrobieniu fft można po prostu wywołać w pętli kolejno DEC2, DEC3, ..., DEC7 i wymnożyć. Powinien zostać jeden słupek. 
Na każdej kopii sygnału kolejno wywołać DEC2, DEC3, ... i potem wymnożyć.

Współczynnik autokorelacji 

Do 3 stycznia