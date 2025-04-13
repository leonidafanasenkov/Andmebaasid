## Andmetüüpid
1. **Teksti või sümboolid** - VARCHAR(50), CHAR(3), TEXT                                         
Näited: nimi, nimetus, telefoniNumber, isikukood - VARCHAR(11)
3. **ARVULISED** - int, bigint, smallint, decimal(5,2) - 5 kokku, 2 - peale komat                                         
Näited: vanus, palk, temperatuur, kaal, pikkus jne
4. **Kuupäeva** - date, time, date/time
5. **Logilised** - bit, bool, boolean

## Piirangud - ограничения
1. Primary Key - ei anna võimalust lisada topelt väärtused
2. UNIQUE - unikaalsus
3. NOT NULL - ei lubata tühjad väärtused
4. Foreign Key - saab kasutada ainult teise tabeli väärtused
5. CHECK - saab sisestada ainult check määratid väärtused CHECK (mees, naine)
