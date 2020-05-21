---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---


- Domínguez-Jiménez, J. A., Dante A., Agbossou K, Henao H., Cardenas A, Sousso K., Campillo J. (2020). Optimal charging scheduling of electric vehicles using PCA and convex optimization. International symposium of industrial electronics (ISIE), In-press.IEEE.

- Domínguez-Jiménez, J. A., Campo-Landines, K. C., Martínez-Santos, J. C., Delahoz, E. J., & Contreras-Ortiz, S. H. (2020). A machine learning model for emotion recognition from physiological signals. Biomedical Signal Processing and Control, 55, 101646.

- Dominguez-Jimenez, J. A., & Campillo, J. (2020). Increasing driving range for electric vehicles at sub-zero temperatures by optimizing a hybrid storage configuration using supercapacitors. In Journal of Physics: Conference Series (Vol. 1448, p. 012014).

- Valdes-Burgos, L., Contreras-Ojeda, S. L., Domínguez-Jiménez, J. A., Lopez-Bueno, J., & Contreras-Ortiz, S. H. (2020, January). Analysis and classification of lung tissue in ultrasound images for pneumonia detection. In 15th International Symposium on Medical Information Processing and Analysis (Vol. 11330, p. 1133003). International Society for Optics and Photonics.

- Dominguez-Jimenez, J. A., Campo-Landines, K. C., & Contreras-Ortiz, S. H. (2019, October). A Methodology for Driving Behavior Recognition in Simulated Scenarios Using Biosignals. In Workshop on Engineering Applications (pp. 357-367). Springer, Cham.

- Campillo, J., Domínguez-Jimenez, J. A., & Cabrera, J. (2019, March). Sustainable Boat Transportation Throughout Electrification of Propulsion Systems: Challenges and Opportunities. In 2019 2nd Latin American Conference on Intelligent Transportation Systems (ITS LATAM) (pp. 1-6). IEEE.

- Contreras-Ojeda, S. L., Sierra-Pardo, C., Dominguez-Jimenez, J. A., Lopez-Bueno, J., & Contreras-Ortiz, S. H. (2019, April). Texture analysis of ultrasound images for pneumonia detection in pediatric patients. In 2019 XXII Symposium on Image, Signal Processing and Artificial Vision (STSIVA) (pp. 1-4). IEEE.

- Domínguez-Jiménez, J. A., Campo-Landines, K. C., Martínez-Santos, J. C., & Contreras-Ortiz, S. H. (2018, December). Emotion detection through biomedical signals: a pilot study. In 14th International Symposium on Medical Information Processing and Analysis (Vol. 10975, p. 1097506). International Society for Optics and Photonics.

- Dominguez-Jimenez, J. A., & Campillo, J. (2018, September). Object-oriented mathematical modeling for estimating electric vehicle’s range using modelica. In Colombian Conference on Computing (pp. 444-458). Springer, Cham.

- Mercado-Aguirre, I. M., Mercado-Medina, E. L., Chavarro-Hernandez, Z. D., Dominguez-Jimenez, J. A., & Contreras-Ortiz, S. H. (2017). A wearable system for biosignal monitoring in weightlifting. Sports Engineering, 20(1), 73-80.

- Mercado-Medina, E. L., Chavarro-Hernández, Z. D., Dominguez-Jimenez, J. A., & Contreras-Ortiz, S. H. (2014, October). Design of an electronic system for monitoring muscle activity in weight-lifting. In 2014 III International Congress of Engineering Mechatronics and Automation (CIIMA) (pp. 1-4). IEEE.

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
