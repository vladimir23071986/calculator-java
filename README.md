Analiza je izvrsena Sonarlint alatom u okviru Visual Studio Code[{
	"resource": "/c:/Users/vesna/OneDrive/Desktop/calculator-java-main/Calculator.java",
	"owner": "sonarlint
	"code": "java:S1118",
	"severity": 4,
	"message": "Add a private constructor to hide the implicit public one.",
	"source": "sonarlint",
	"startLineNumber": 4,
	"startColumn": 14,
	"endLineNumber": 4,
	"endColumn": 24
},{
	"resource": "/c:/Users/vesna/OneDrive/Desktop/calculator-java-main/Calculator.java",
	"owner": "sonarlint",
	"code": "java:S1845",
	"severity": 4,
	"message": "Rename method \"ToString\" to prevent any misunderstanding/clash with method \"toString\" defined in superclass \"java.lang.Object\".",
	"source": "sonarlint",
	"startLineNumber": 18,
	"startColumn": 30,
	"endLineNumber": 18,
	"endColumn": 38
},{
	"resource": "/c:/Users/vesna/OneDrive/Desktop/calculator-java-main/Calculator.java",
	"owner": "sonarlint",
	"code": "java:S1220",
	"severity": 2,
	"message": "Move this file to a named package.",
	"source": "sonarlint",
	"startLineNumber": 1,
	"startColumn": 1,
	"endLineNumber": 1,
	"endColumn": 1
},{
	"resource": "/c:/Users/vesna/OneDrive/Desktop/calculator-java-main/Calculator.java",
	"owner": "sonarlint",
	"code": "java:S100",
	"severity": 2,
	"message": "Rename this method name to match the regular expression '^[a-z][a-zA-Z0-9]*$'.",
	"source": "sonarlint",
	"startLineNumber": 18,
	"startColumn": 30,
	"endLineNumber": 18,
	"endColumn": 38
},{
	"resource": "/c:/Users/vesna/OneDrive/Desktop/calculator-java-main/Calculator.java",
	"owner": "sonarlint",
	"code": "java:S100",
	"severity": 2,
	"message": "Rename this method name to match the regular expression '^[a-z][a-zA-Z0-9]*$'.",
	"source": "sonarlint",
	"startLineNumber": 24,
	"startColumn": 26,
	"endLineNumber": 24,
	"endColumn": 29
},{
	"resource": "/c:/Users/vesna/OneDrive/Desktop/calculator-java-main/Calculator.java",
	"owner": "sonarlint",
	"code": "java:S1488",
	"severity": 2,
	"message": "Immediately return this expression instead of assigning it to the temporary variable \"textResult\".",
	"source": "sonarlint",
	"startLineNumber": 70,
	"startColumn": 29,
	"endLineNumber": 70,
	"endColumn": 56
},{
	"resource": "/c:/Users/vesna/OneDrive/Desktop/calculator-java-main/Calculator.java",
	"owner": "sonarlint",
	"code": "java:S100",
	"severity": 2,
	"message": "Rename this method name to match the regular expression '^[a-z][a-zA-Z0-9]*$'.",
	"source": "sonarlint",
	"startLineNumber": 74,
	"startColumn": 25,
	"endLineNumber": 74,
	"endColumn": 34
},{
	"resource": "/c:/Users/vesna/OneDrive/Desktop/calculator-java-main/Calculator.java",
	"owner": "sonarlint",
	"code": "java:S3626",
	"severity": 2,
	"message": "Remove this redundant jump.",
	"source": "sonarlint",
	"startLineNumber": 183,
	"startColumn": 13,
	"endLineNumber": 183,
	"endColumn": 20
}]
Koristeci Codalyze alat u Visual Studio Code, dobijeni su sledeci podatci

koristeći Codalyze alat u okviru Visal Studio Code dobijeni su podaci: metoda evaluateExtpresion- 
ova metoda se nalazi na 28 liniji koda i je do 72 linije koda, ciklomatska kompleksnost ove metode je 12, 
ima 33 linije koda i ima 1 parametar. metoda Calculate- ova metoda se nalazi na 74 liniji koda i do 186 linije koda, 
ciklomatska kompleksnost je 12, ima 77 linija koda i ima 2 parametra. -Kognitivna složenost kao i u većini slučajeva 
i ovde je slična ciklomatskoj složenosti. Na osnovu analize ove dve metode, posmatrajući prve if blokove i if blokove 
unutar njih kao i naredne nivoe gnežđenja dobijena je kompleksna složenost za metodu evaluateExtpresion 11, a metoda Calculate 15.

Posmatrajuci celokupni fajl ovaj kod nije kompleksan, nema puno velikih gresaka, tri greske od osam su ukazivale na problem naziva
same metode.

