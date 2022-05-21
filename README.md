# Conditional object generation using pre-trained models and plug-in networks

Prowadzący: **Patryk Wielopolski**, Politechnika Wrocławska

Abstrakt: Modele generatywne przyciągnęły uwagę wielu praktyków uczenia maszynowego w ostatnich latach, co zaowocowało modelami takimi jak StyleGAN do generowania ludzkiej twarzy lub PointFlow do generowania chmur punktów 3D. Jednak domyślnie nie możemy kontrolować jego procesu próbkowania, tj. nie możemy wygenerować próbki z określonym zestawem atrybutów. Obecne podejście polega na przekwalifikowaniu modelu z dodatkowymi danymi wejściowymi i inną architekturą, co wymaga czasu i zasobów obliczeniowych.

Podczas tego praktycznego warsztatu omówimy metodę, która pozwala nam generować obiekty o danym zestawie atrybutów bez ponownego uczenia modelu bazowego. W tym celu wykorzystamy modele normalizing flows – Conditional Masked Autoregressive Flow i Conditional Real NVP oraz sieci Plugin, w wyniku których powstaje Flow Plugin Network.

Cel warsztatów:
 * Praktyczne zapoznanie się z modelami Normalizing Flows oraz biblioteką nflows
 * Praktyczne zapoznanie się z metodą Flow Plugin Network

Agenda:
 * Wstęp do modeli generatywnych
 * Praktyczny wstęp do Normalizing Flows z wykorzystaniem pakietu **nflows**.
 * Metoda Flow Plugin Network (FPN)
 * Wykorzystanie metody FPN do warunkowego generowania obrazów
 * Wykorzystanie metody FPN do warunkowego generowania chmur punktów
