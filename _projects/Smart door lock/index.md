---
layout: post
title: Serrure intelligente
description: Système de verrouillage numérique multi-authentification offrant une sécurité complète à l'utilisateur. Le dispositif permet le déverrouillage par quatre méthodes : code PIN à 4 chiffres modifiable, lecteur d'empreintes digitales, carte RFID sans contact, et bouton d'ouverture intérieur. Le traitement est effectué par une carte ESP32 avec affichage des statuts sur écran LCD.
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
      <li>Créer un système de contrôle d'accès sécurisé avec plusieurs méthodes d'authentification.</li>
      <li>Permettre la modification du code PIN par l'utilisateur.</li>
      <li>Développer un prototype fonctionnel avec composants embarqués temps réel.</li>
    </ul>

   <h2 class="text-2xl font-semibold mb-2">🛠️ Technologies & Outils</h2>
    <ul class="list-disc ml-6 mb-4">
      <li><strong>Hardware:</strong> ESP32, module RFID RC522, capteur d'empreintes, clavier matriciel, relais, écran LCD, LEDs</li>
      <li><strong>Software:</strong> Arduino IDE, C/C++, bibliothèques MFRC522 et Adafruit Fingerprint</li>
      <li><strong>Communication:</strong> Protocoles I2C et SPI, interface série pour configuration</li>
    </ul>

   <h2 class="text-2xl font-semibold mb-2">🧠 Fonctionnement</h2>
    <p class="mb-4">
      Le système utilise un microcontrôleur ESP32 qui gère quatre modes d'authentification en parallèle. L'utilisateur déverrouille la porte via code PIN, empreinte digitale, carte RFID ou bouton intérieur. Le microcontrôleur valide l'authentification et active le relais de déverrouillage. L'écran LCD affiche l'état de la serrure et les LEDs fournissent un retour visuel (vert = accès autorisé, rouge = refusé).
    </p>

   <h2 class="text-2xl font-semibold mb-2">⚙️ Processus de Développement</h2>
    <ol class="list-decimal ml-6 mb-4">
      <li>Analyse du cahier des charges et conception du schéma électrique.</li>
      <li>Développement modulaire du firmware pour chaque méthode d'authentification.</li>
      <li>Implémentation du système de gestion des utilisateurs avec stockage en EEPROM.</li>
      <li>Tests et optimisation des temps de réponse du système.</li>
      <li>Création d'une interface de configuration pour l'enregistrement des utilisateurs.</li>
    </ol>

  <h2 class="text-2xl font-semibold mb-2">📊 Résultats & Réalisations</h2>
    <ul class="list-disc ml-6 mb-4">
      <li>Système fonctionnel avec quatre méthodes d'authentification opérationnelles.</li>
      <li>Temps de réponse inférieur à 500ms pour toutes les méthodes.</li>
      <li>Architecture modulaire permettant l'ajout de fonctionnalités futures.</li>
      <li>Démonstration réussie avec retours positifs des enseignants.</li>
    </ul>

  <h2 class="text-2xl font-semibold mb-2">🌟 Apprentissages</h2>
    <p class="mb-4">
      Ce projet m'a permis d'acquérir une expérience pratique en conception de systèmes embarqués sécurisés, en intégration multi-capteurs et en programmation temps réel. J'ai également développé mes compétences en architecture logicielle modulaire et en implémentation de protocoles de communication (I2C, SPI, UART).
    </p>
  </div>
</section>
