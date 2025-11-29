# Sensor Simulator

Un simulateur de capteurs pour générer des mesures réalistes à partir de trajectoires définies. Le simulateur prend en charge plusieurs types de capteurs : IMU (Inertial Measurement Unit), odomètre, baromètre et magnétomètre.

## Description

Sensor Simulator permet de générer des données de capteurs simulées à partir d'une trajectoire définie par l'utilisateur. Cette trajectoire peut être :
- **Simulée** : définie manuellement ou générée par l'utilisateur
- **Réelle** : importée à partir de données de trajectoires réelles (fonctionnalité prévue)

Les mesures générées incluent le bruit, les dérives et autres caractéristiques réalistes des capteurs pour permettre le développement et le test d'algorithmes de navigation, de filtrage et de fusion de données.

## Développement

### Contribution

Les contributions sont les bienvenues ! N'hésitez pas à ouvrir une issue ou une pull request.

## License

Ce projet est sous licence **GNU General Public License v3.0 (GPLv3)** avec une restriction importante : **l'utilisation de ce logiciel comme base pour des projets non ouverts (avec ou sans modifications) est interdite**.

Voir le fichier [LICENSE](LICENSE) pour plus de détails.

## Roadmap

- [x] Structure de base du projet
- [ ] Implémentation du simulateur IMU
- [ ] Implémentation du simulateur odomètre
- [ ] Implémentation du simulateur baromètre
- [ ] Implémentation du simulateur magnétomètre
- [ ] Support des trajectoires réelles
- [ ] Export des données dans différents formats
- [ ] Visualisation des trajectoires et mesures
- [ ] Documentation API complète

## Auteur

**Bruno DOKPOMIWA**  
Ingénieur Géodésien, spécialiste GNSS, navigation inertielle et fusion de capteurs  
Contact : brunodkp.pro+git@gmail.com

Développé pour faciliter le développement et les tests d'algorithmes de navigation et de fusion de données de capteurs.

