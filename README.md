# Advanced_Sales_Analytics

- Wie hoch ist die Kunenabwanderung pro Jahr / Monat?
- Zahlt sich Kundenloyalität aus?
- Warum verlieren wir Kunden?
- Welche Kunden haben ein Absprunrisiko von >50%?

Detailierte Erläuterung:

- Wie hoch ist die Kunenabwanderung pro Jahr / Monat?
Berechnung in Tableau mit einem Calculated Field. Das funktioniert häufig - Alternativ, je nach Kundenbedürfnis kann diese Berechnung
extrem kompliziert werden.

- Zahlt sich Kundenloyalität aus?
Eine einfache Kohortenanalyse. 

- Warum verlieren wir Kunden?
Basierend auf einem Random-Forest Algorithmus, Feature Importance. Häufig bekommen wir dadurch verlässliche Resultate - aber, es ist
keine Garantie. Manchmal sind die Kundenabgänge stochastisch und das Modell funktioniert nicht.

- Welche Kunden haben ein Absprunrisiko von >50%?
Machine Learning Algorithmus trainiert.
