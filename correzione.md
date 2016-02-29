### Correzione compito Ingegneria del Software del 26/02/2016

Federico Maria Teotini  
Matricola 5306916

### Esercizio 1
Il class diagram che descrive come vengono composti i pattern Composite e Builder è il seguente.

![Class Diagram](/ClassDiagram1.jpg)

Il Builder pattern è composto da:
- __ExprParser__ (Director)
- __ExprBuilder__ (ConcreteBuilder)
- __*ExprComponent*__ (Product)

Il Composite pattern è composto da:
- __*ExprComponent*__ (*Component*)
- __VarComponent__ (Leaf)
- __*ExprAggregate*__ (*Composite*)
- __AndComponent__, __OrComponent__, __ParenthesisComponent__ (ConcreteComposite)

Nel caso specifico della rappresentazione dell'espressione `(X AND Y) OR Z`, l'object diagram del Composite è

![Composite Object Diagram](/ClassDiagram2.jpg)
