# Anteckningar 2022-02-13
Implementering av 8-bitars ALU för CPU-emulator.
ALU:ns syfte och arbetssätt samt implementering för aritmetiska operationer addition och subtraktion samt 
logiska operationer OR, AND och XOR demonstreras. Statusbitar SNZVC is CPU:ns statusregister uppdateras 
utefter beräknat resultat.

Diverse aritmetiska och logiska instruktioner samt villkorliga hoppinstruktioner implementeras också,
tillsammans med implementering av instruktioner CLR, LSL samt LSR.

I efterföljande del ska interrupt-implementering läggas till.

Samtliga .c- och .h-filer utgörs av processorn med färdig ALU samt att programkoden har uppdaterats 
för att testa ALU:n via bitvis AND samt bitvis OR.

Filen "alu.png" utgör en bild som demonstrerar ALU:ns arbetssätt visuellt samt via text.

Filen "alu_emulator.zip" utgör en ALU-emulator, som kan användas för att testa ALU:ns funktion från en terminal. Operation samt operander kan matas in från terminalen, följt av att resultatet skrivs ut både decimalt och binärt, tillsammans med statusbitar SNZVC. Fem exempelfall skrivas ut vid start, som demonstrerar när de olika statusbitarna ettställs.

Filen "alu.png" utgör en bild som demonstrerar ALU:ns arbetssätt visuellt samt via text.

Filen "alu_emulator.zip" utgör en ALU-emulator, som kan användas för att testa ALU:ns funktion från en terminal. Operation samt operander kan matas in från terminalen, följt av att resultatet skrivs ut både decimalt och binärt, tillsammans med statusbitar SNZVC. Fem exempelfall skrivas ut vid start, som demonstrerar när de olika statusbitarna ettställs.
