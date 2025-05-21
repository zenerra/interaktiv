# Interaktív vizsga jegyzet
Jegyzet az interaktív vizsgához

### Git Parancsok Jegyzetei

1. **git init**: Új Git tárolót inicializál az aktuális könyvtárban a verziókövetés megkezdéséhez.  

2. **git clone <repository>**: Letölt egy távoli tárolót a helyi gépre az összes fájllal és előzménnyel.  

3. **git add <file>**: A megadott fájlok változtatásait előkészíti a következő commit számára.  

4. **git commit -m "<message>"**: Az előkészített változtatásokat commitként menti egy leíró üzenettel.  

5. **git status**: Megmutatja a módosított, előkészített vagy követetlen fájlok aktuális állapotát.  

6. **git push <remote> <branch>**: Feltölti a helyi commitokat a megadott távoli ágra.  

7. **git pull <remote> <branch>**: Letölti és egyesíti a távoli ág frissítéseit a helyi ágba.  

8. **git branch**: Listázza az ágakat vagy új ágat hoz létre a `git branch <név>` paranccsal.  

9. **git checkout <branch>**: Átvált a megadott ágra vagy visszaállítja a fájlokat.  

10. **git merge <branch>**: A megadott ág változtatásait egyesíti az aktuális ágba.  

11. **git log**: Megjeleníti a commit előzményeket azonosítókkal, szerzőkkel, dátumokkal és üzenetekkel.  

12. **git diff**: Megmutatja a különbségeket a munkakönyvtár, előkészített fájlok vagy commitok között.  

13. **git stash**: Ideiglenesen menti a nem commitolt változtatásokat ágváltáshoz vagy más feladathoz.  

14. **git remote add <name> <url>**: Távoli tárolót kapcsol a helyi Git konfigurációhoz.  

15. **git fetch <remote>**: Letölti a távoli tároló frissítéseit anélkül, hogy egyesítené őket helyben.