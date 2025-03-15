---
title: "Lineare Regression"
author: "Walter Gruber"
date: "2025-03-15"
description: "Einfache lineare Regression mit einem Prädiktor"
cover-image: "Images/Cover.png"
github-repo: wgruber/LineareRegression
site: bookdown::bookdown_site
output:
  bookdown::gitbook: default
bibliography: "bibliography.bib"
biblio-style: "apalike"
link-citations: true
---

# {-}

<center>

![](Images/TafelFormeln.jpg){ width=70% }

</center>



# Einfache Lineare Regression {-}

Dieses Skript basiert (großteils) auf der Literatur von Andy Field und Rand Wilcox [@FieldWilcox.2017], David Erceg-Hurn et.al. [@Hurn.2008], Mair [@Mair.2020] and Wilcox [@Wilcox.2012]. Teile des Inhaltes wurden direkt aus der genannten Literatur übernommen.

## Vorwort {-}

In einer Welt, die zunehmend von Daten geprägt ist, sind statistische Methoden unverzichtbare Werkzeuge, um Muster aufzudecken und fundierte Entscheidungen zu treffen. Die einfache lineare Regression ist eine der grundlegendsten, aber zugleich wirkungsvollsten Techniken in der Statistik. Sie ermöglicht es, den Zusammenhang zwischen zwei quantitativen Variablen zu modellieren und vorherzusagen, wie sich Änderungen in einer unabhängigen Variable auf eine abhängige Variable auswirken.

In diesem Kapitel werden wir die Grundlagen der einfachen linearen Regression erkunden: 

- Was bedeutet es, einen linearen Zusammenhang zwischen zwei Variablen zu postulieren? 
- Wie wird ein lineares Regressionsmodell aufgestellt und interpretiert? 
- Durch anschauliche Beispiele und Schritt-für-Schritt-Anleitungen werden wir die Schlüsselkonzepte und mathematischen Grundlagen dieser Methode erläutern. 

## Ziele {-}

Ziel ist es, Ihnen ein solides Verständnis für die einfache lineare Regression zu vermitteln, das als Basis für komplexere statistische Analysen dient.

- Regressionsmodelle verstehen und anwenden.
- Eigenschaften von Quadratsummen verstehen:
  - Totale Quadratsumme.
  - Fehler- oder Residualquadratsumme.
  - Modell Quadratsumme.
- Prüf- und Kenngrößen verstehen und interpretieren:
  - F-Werte.
  - Teststatistiken wie t-Werte.
  - Konfidenzintervalle.
  - b-Gewichte und standardisierte Gewichte ($\beta$).
  - $R^2$ (Determinationskoeffizient, Bestimmtheitsmaß).
- Voraussetzungen und deren Überprüfung bei LM.
- Regression verstehen und anwenden können.
- Interpretation von Ergebnissen und APA-konforme Berichterstattung.
- Problembereiche der einfachen Regression verstehen und erkennen können.
