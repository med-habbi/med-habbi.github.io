---
layout: post
title: Serrure intelligente
description: "Système de verrouillage intelligent multi-authentification offrant une sécurité renforcée par combinaison de technologies. Le dispositif intègre quatre méthodes d'authentification : code PIN à 4 chiffres personnalisable, lecteur d'empreintes digitales biométrique, carte RFID sans contact, et bouton de déverrouillage intérieur. Le système permet également la modification du code d'accès par l'utilisateur autorisé, garantissant une flexibilité et une sécurité optimales pour le contrôle d'accès résidentiel."
skills: 
  - Arduino
  - ESP32
  - C#
  - Systèmes Embarqués
main-image: /smdl.png
---

<section class="p-10 bg-gray-100 text-gray-800">
  <div class="max-w-5xl mx-auto">

  <h2 class="text-2xl font-semibold mb-2">🎯 Objectifs</h2>
    <ul class="list-disc ml-6 mb-4">
      <li>Développer un système de contrôle d'accès sécurisé multi-authentification pour usage résidentiel.</li>
      <li>Intégrer plusieurs technologies d'identification (biométrie, RFID, code PIN) dans un dispositif unique.</li>
      <li>Créer une interface utilisateur intuitive permettant la gestion des codes d'accès.</li>
      <li>Concevoir un système embarqué fiable et évolutif basé sur des composants modernes.</li>
    </ul>

   <h2 class="text-2xl font-semibold mb-2">🛠️ Technologies & Outils</h2>
    <ul class="list-disc ml-6 mb-4">
      <li><strong>Hardware:</strong> Carte ESP32, module RFID RC522, capteur d'empreintes digitales, clavier matriciel 4x4, relais électronique, écran LCD I2C, LEDs indicateurs</li>
      <li><strong>Software:</strong> Arduino IDE, bibliothèques MFRC522 et Adafruit Fingerprint, programmation C/C++, protocoles I2C et SPI</li>
      <li><strong>Communication:</strong> Interface série pour configuration, Wi-Fi ESP32 pour gestion à distance, stockage EEPROM pour codes et empreintes</li>
    </ul>

   <h2 class="text-2xl font-semibold mb-2">🧠 Fonctionnement du Système</h2>
    <p class="mb-4">
      Le système utilise un microcontrôleur ESP32 qui gère simultanément quatre modes d'authentification. L'utilisateur peut déverrouiller la porte en saisissant un code PIN à 4 chiffres sur le clavier, en scannant son empreinte digitale enregistrée, en présentant sa carte RFID autorisée, ou en actionnant le bouton intérieur. Chaque tentative d'accès est validée par le microcontrôleur qui active le relais de déverrouillage en cas de succès. Le système affiche l'état de la serrure et les messages d'erreur sur l'écran LCD, tandis que les LEDs fournissent un retour visuel immédiat (vert pour accès autorisé, rouge pour refus).
    </p>

  <h2 class="text-2xl font-semibold mb-2">⚙️ Processus de Développement</h2>
    <ol class="list-decimal ml-6 mb-4">
      <li>Analyse du cahier des charges et définition de l'architecture matérielle et logicielle du système.</li>
      <li>Conception du schéma électrique et sélection des composants adaptés aux contraintes de sécurité.</li>
      <li>Développement modulaire du firmware : modules d'authentification RFID, biométrique et code PIN indépendants.</li>
      <li>Implémentation du système de gestion des utilisateurs avec stockage sécurisé en EEPROM.</li>
      <li>Tests unitaires de chaque module d'authentification puis tests d'intégration du système complet.</li>
      <li>Optimisation de la consommation énergétique et des temps de réponse du système.</li>
      <li>Développement d'une interface de configuration pour l'enregistrement des utilisateurs et la modification des codes.</li>
    </ol>

  <h2 class="text-2xl font-semibold mb-2">📊 Résultats & Réalisations</h2>
    <ul class="list-disc ml-6 mb-4">
      <li>Système fonctionnel offrant quatre méthodes d'authentification avec un taux de reconnaissance d'empreintes de 98%.</li>
      <li>Temps de réponse inférieur à 500ms pour toutes les méthodes d'authentification.</li>
      <li>Interface utilisateur intuitive permettant la modification des codes sans reprogrammation.</li>
      <li>Architecture modulaire facilitant l'ajout de fonctionnalités supplémentaires (notifications, logs d'accès).</li>
      <li>Prototype validé avec démonstration réussie auprès des enseignants et proposition d'amélioration pour version commerciale.</li>
    </ul>

  <h2 class="text-2xl font-semibold mb-2">🌟 Compétences Développées</h2>
    <p class="mb-4">
      Ce projet m'a permis d'acquérir une expérience approfondie en conception de systèmes embarqués sécurisés, en intégration multi-capteurs et en programmation temps réel. J'ai développé mes compétences en architecture logicielle modulaire, en gestion de la mémoire embarquée, et en implémentation de protocoles de communication (I2C, SPI, UART). Le projet m'a également formé aux bonnes pratiques de sécurité pour les systèmes de contrôle d'accès et à la gestion de projet technique avec respect de contraintes strictes.
    </p>
  </div>
</section>
