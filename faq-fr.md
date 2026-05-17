---
layout: default
title: Foire aux questions — Baisse-loyer
description: Toutes les réponses sur la baisse de loyer, la demande, les courriers de suivi et la conciliation en Suisse. Confidentialité, tarification, protection contre les résiliations.
lang: fr-CH
permalink: /faq-fr.html
---

<div class="lang-switch">
  <a href="faq-de.html">DE</a>
  <span class="active" aria-current="page">FR</span>
  <a href="faq-it.html">IT</a>
  <a href="faq-en.html">EN</a>
</div>

# Toutes les questions fréquentes sur Baisse-loyer

Tu trouves ici les réponses à tous les sujets autour de l'app : calculer le droit, envoyer la lettre, courriers de suivi, procédure de conciliation, protection des données, coûts, protection contre les résiliations selon l'art. 271a CO, et plus.

<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "FAQPage",
  "mainEntity": [
    {
      "@type": "Question",
      "name": "Quand ai-je droit à une baisse de loyer ?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Dès que le taux d'intérêt de référence a baissé depuis ta dernière adaptation de loyer ou le début de ton bail (art. 270a CO). La baisse n'est pas automatique. Tu dois la demander à ta·ton bailleur·eresse. Baisse-loyer vérifie pour toi si un droit existe actuellement et calcule le montant dès que tu as saisi ton loyer net et la date de la dernière adaptation."
      }
    },
    {
      "@type": "Question",
      "name": "Comment l'app calcule-t-elle le droit ?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Baisse-loyer applique l'ordonnance sur le bail à loyer OBLF (art. 13) et le Code des obligations CO (art. 269a). Trois facteurs entrent dans le calcul : (1) Baisse du taux de référence, pour chaque baisse de 0.25 % du taux, le loyer diminue de 2.91 % (valeur minimale prudente selon l'OBLF) ; en cas de plusieurs paliers, on applique l'inverse de la hausse cumulée. (2) Hausse générale des coûts, 0.5 % par année depuis la dernière adaptation, que ta·ton bailleur·eresse peut opposer à la baisse. (3) Compensation du renchérissement, 40 % de la variation de l'IPC (indice des prix à la consommation) depuis la dernière adaptation, également à charge de la baisse. Le droit net est : baisse du taux moins hausse des coûts moins renchérissement. Si le résultat est négatif, tu n'as pas de droit, même si le taux a baissé. Pour un calcul contraignant, contacte l'association des locataires."
      }
    },
    {
      "@type": "Question",
      "name": "D'où viennent les données du taux de référence et du renchérissement ?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Le taux de référence est publié par l'Office fédéral du logement OFL (mise à jour trimestrielle, parfois prolongée sans changement). L'indice des prix à la consommation (IPC) pour le renchérissement provient de l'Office fédéral de la statistique OFS (publication mensuelle, vers le 6 du mois suivant). Les deux sources sont juridiquement contraignantes. Baisse-loyer télécharge les valeurs actuelles à chaque démarrage depuis le serveur (pas depuis le fichier d'installation), et nous les mettons à jour dès chaque publication OFL ou OFS. Si nos données ne sont pas à jour, tu vois un avertissement discret sur le tableau de bord. Tu peux vérifier les données brutes sur bwo.admin.ch et bfs.admin.ch."
      }
    },
    {
      "@type": "Question",
      "name": "Pourquoi l'app affiche-t-elle parfois « pas de droit à la baisse » alors que le taux a baissé ?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Pour les baux de longue durée (par ex. 10 ans depuis la dernière adaptation), le renchérissement cumulé (~1 % par an) et la hausse des coûts (0.5 % par an) peuvent être opposés par ta·ton bailleur·eresse à ta demande de baisse. Résultat : taux baissé + compensations accumulées = aucun droit net. Baisse-loyer te montre ce cas honnêtement, pour t'éviter d'envoyer une lettre que ta·ton bailleur·eresse pourrait refuser à juste titre. Si tu as des doutes, ou si la hausse des coûts a déjà été compensée par une baisse antérieure, clarifie avec l'association des locataires."
      }
    },
    {
      "@type": "Question",
      "name": "Qu'en est-il des baux indexés ou échelonnés ?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Pour ces types de bail, une baisse fondée sur le taux d'intérêt de référence est exclue pendant la durée du contrat. Baisse-loyer ne détecte pas automatiquement le type de bail, à toi de vérifier brièvement.  Comment reconnaître le type de bail dans ton contrat :  - Bail ordinaire (le plus fréquent, env. 90-95% des baux d'habitation suisses) : le loyer est un montant fixe en CHF par mois, sans indexation et sans hausses prédéfinies. Exemple : \"Loyer net CHF 1500 par mois\". → Demande de baisse selon art. 270a CO possible. - Bail indexé : le loyer est explicitement lié à l'indice suisse des prix à la consommation (IPC) et augmente avec le renchérissement. Mots-clés au contrat : \"loyer indexé\", \"indexation IPC\", \"adaptation à l'indice national\". Condition préalable : un bail d'au moins 5 ans de durée fixe (art. 269b CO). → Pas de baisse fondée sur le taux de référence. - Bail à loyers échelonnés : le loyer augmente selon un plan fixé au contrat, par ex. \"Année 1 CHF 1500, année 2 CHF 1550, année 3 CHF 1600\". Mots-clés : \"loyer échelonné\", \"échelonnement convenu\". Condition préalable : une durée minimale de 3 ans (art. 269c CO). → Pas de baisse fondée sur le taux de référence.  En cas de doute, l'ASLOCA de ton canton (asloca.ch) peut vérifier ton contrat."
      }
    },
    {
      "@type": "Question",
      "name": "Puis-je demander la baisse rétroactivement ?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Non. La baisse prend effet uniquement à partir du prochain terme de résiliation après ta demande. Les sommes payées en trop ne sont plus récupérables. C'est précisément pour cela que Baisse-loyer propose l'alerte taux : nous te prévenons dès que le taux de référence baisse. Tu ne manques plus aucune baisse."
      }
    },
    {
      "@type": "Question",
      "name": "Comment retrouver la date de la dernière adaptation ?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Regarde ton bail et toutes les communications ultérieures de ta·ton bailleur·eresse (souvent sur le formulaire officiel). La dernière adaptation peut être le début du bail s'il n'y en a jamais eu. En cas de doute, choisis « Je ne sais pas exactement » dans l'assistant. Baisse-loyer calcule alors de façon prudente avec une estimation."
      }
    },
    {
      "@type": "Question",
      "name": "À partir de quand le nouveau loyer plus bas s'applique-t-il ?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "La baisse prend effet au prochain terme de résiliation après le délai de résiliation contractuel (en général 3 mois). Si tu déposes assez tôt, elle s'applique à cette date. Baisse-loyer utilise par défaut les 4 échéances trimestrielles suisses courantes (31.03 / 30.06 / 30.09 / 31.12) et inscrit automatiquement la prochaine date possible dans la lettre."
      }
    },
    {
      "@type": "Question",
      "name": "Quand la lettre doit-elle arriver chez ma·mon bailleur·eresse ?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "La lettre doit arriver avant le début du délai de résiliation. Exemple : pour une baisse au 1er juillet avec un délai de trois mois, la lettre doit être reçue fin mars. Envoie-la en recommandé comme preuve de réception. Baisse-loyer insère automatiquement la prochaine date possible ; c'est toi qui choisis quand poster."
      }
    },
    {
      "@type": "Question",
      "name": "Ma·mon bailleur·eresse doit-elle·il répondre ?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Oui. Ta·ton bailleur·eresse doit prendre position par écrit dans les 30 jours. En cas d'accord, le loyer est adapté. La lettre générée par Baisse-loyer mentionne le délai de 30 jours ainsi que les bases légales (art. 270a Code des obligations CO, art. 13 ordonnance sur le bail à loyer OBLF), pour que la demande soit formellement correcte."
      }
    },
    {
      "@type": "Question",
      "name": "Comment dois-je envoyer la lettre ?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "De préférence en recommandé. Tu disposes ainsi d'une preuve de réception en cas de litige. Baisse-loyer crée le PDF et tu peux l'envoyer directement depuis l'app comme lettre standard ou en recommandé. Tu peux aussi télécharger un PDF ou Word, l'imprimer et le déposer toi-même à la poste. Conserve toujours une copie pour tes dossiers."
      }
    },
    {
      "@type": "Question",
      "name": "Comment envoyer une lettre directement depuis l'app ?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Crée la lettre dans l'assistant, ouvre l'aperçu et tape sur « Envoyer la lettre » ou « Envoyer en recommandé ». La première fois, nous te demandons ta signature (dessinée une seule fois sur l'appareil). Ensuite, Baisse-loyer transmet la lettre au service d'impression suisse Pingen, qui l'imprime physiquement et la poste à ton·a bailleur·esse. Tu reçois une notification dès que la lettre est remise à La Poste, avec un envoi recommandé, en plus le jour de la distribution."
      }
    },
    {
      "@type": "Question",
      "name": "Comment savoir si ma lettre est bien arrivée ?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Dès que Pingen (le service d'envoi de courrier suisse basé à Zurich, pingen.com) remet ta lettre à La Poste, Baisse-loyer t'envoie une notification (« Lettre en route »). Avec un envoi recommandé (CHF 7.90 supplémentaires), tu reçois en plus, le jour de la distribution effective, une seconde notification (« Lettre distribuée le DD.MM. »), et le numéro de suivi de La Poste suisse apparaît dans la fiche de la lettre. Un envoi standard ne fournit par définition aucune preuve de distribution (c'est une caractéristique du système postal suisse, pas une limite de l'app). Si tu as besoin d'une certitude juridique sur l'arrivée, par exemple parce que tu envisages la conciliation, choisis le recommandé."
      }
    },
    {
      "@type": "Question",
      "name": "Combien coûte l'envoi ?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "L'envoi de la lettre est directement inclus dans l'achat de la lettre (sans supplément). Aucun frais supplémentaire, distribution en règle générale en 2 jours ouvrables. Le recommandé coûte CHF 7.90 de plus par lettre (supplément, hors abonnement), payable via l'App Store / Play Store. Le prix couvre l'affranchissement, la preuve de dépôt et l'impression. Au guichet postal, un recommandé coûte environ CHF 5.70 plus ton déplacement. Le recommandé est juridiquement recommandé pour les demandes de baisse, car il fournit une preuve de réception."
      }
    },
    {
      "@type": "Question",
      "name": "Puis-je annuler une lettre déjà envoyée ?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Oui, dans les 30 minutes environ après l'envoi, tant que Pingen n'a pas encore imprimé la lettre. Une pastille « Annuler » apparaît sur la carte de la lettre dans le tableau de bord. Touche-la, la lettre est supprimée chez Pingen et repasse en brouillon dans l'app. Tu peux ensuite corriger par exemple l'adresse du·de la destinataire et l'envoyer à nouveau. Si la lettre est déjà imprimée, l'app affiche « Annulation impossible », il faut alors attendre que la lettre revienne (en recommandé) ou considérer l'envoi comme expérience."
      }
    },
    {
      "@type": "Question",
      "name": "J'ai marqué la lettre comme déposée moi-même mais ne l'ai pas déposée. Que faire ?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Touche l'icône crayon sur la carte de la lettre dans le tableau de bord. Dans la feuille qui s'ouvre apparaît un bouton « Annuler l'envoi personnel ». Confirme : la lettre repasse à l'état brouillon, la date d'envoi et un éventuel statut de réponse sont supprimés. Tu peux ensuite la renvoyer ou la télécharger en Word."
      }
    },
    {
      "@type": "Question",
      "name": "Comment récupérer une procédure archivée ?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Dans l'onglet Plus sous « Archives » tu trouves toutes les procédures clôturées. Pour chaque groupe il y a une icône « Réactiver la procédure » (flèche circulaire) à côté de l'icône de suppression. Tape → dialogue de confirmation → les lettres de cette procédure réapparaissent dans le tableau de bord actif, le statut actuel (acceptée/partielle/refusée) est conservé. Utile si tu veux p.ex. mener une procédure clôturée jusqu'à la conciliation après tout."
      }
    },
    {
      "@type": "Question",
      "name": "Ma lettre est revenue (non distribuable). Que faire ?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Dans le tableau de bord apparaît un hero « Envoi échoué » indiquant un possible problème d'adresse. Tape sur « Vérifier l'adresse » → tu arrives directement dans le formulaire bailleur·esse. Corrige l'adresse, sauvegarde, retourne à la lettre et renvoie. Note : « non distribuable » n'apparaît qu'avec le recommandé, car La Poste suisse ne suit pas les envois standards. Pour une preuve de réception juridique, recommande l'upgrade recommandé (+ CHF 7.90)."
      }
    },
    {
      "@type": "Question",
      "name": "Puis-je envoyer plusieurs lettres de rappel ?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Oui. Si ton·a bailleur·esse reste silencieux·se malgré le premier rappel, tu peux envoyer une deuxième (ou troisième) lettre de rappel. Touche le CTA rappel comme d'habitude, l'app affiche un dialogue « Déjà envoyée le DD.MM., renvoyer ? » et tu confirmes l'achat (CHF 6.90 par lettre de suivi). Souvent pertinent juridiquement comme dernière étape avant la demande de conciliation, car les rappels multiples documentent la procédure. Même logique pour la demande de pièces."
      }
    },
    {
      "@type": "Question",
      "name": "L'autorité de conciliation accepte-t-elle ma lettre depuis Baisse-loyer, ou ai-je besoin d'un formulaire cantonal ?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "La lettre de conciliation générée par Baisse-loyer est conforme à l'art. 202 al. 2 CPC : elle contient la désignation de la partie adverse, la conclusion et l'objet du litige ainsi que ta signature. Elle doit donc être acceptée par toutes les autorités de conciliation suisses en matière de bail. Il n'existe pas d'obligation fédérale d'utiliser un formulaire cantonal.  Certains cantons (par exemple Zurich, Berne) proposent leurs propres formulaires de conciliation pour accélérer le traitement interne. Ces formulaires sont une recommandation, pas une exigence. Si ton autorité de conciliation te demande un formulaire : tu peux le remettre ultérieurement, ta saisie initiale reste valide dans le délai (la date de la lettre Baisse-loyer compte pour le délai de 30 jours selon l'art. 273 CO).  Si tu préfères le formulaire cantonal : contacte l'autorité de conciliation compétente de ton domicile. Les adresses se trouvent sur bwo.admin.ch sous \"Schlichtungsbehörden / Autorités de conciliation\". Dans ce cas, télécharge la lettre de conciliation depuis Baisse-loyer au format Word et reprends les calculs et la liste des annexes dans le formulaire."
      }
    },
    {
      "@type": "Question",
      "name": "Comment suivre l'audience de conciliation dans l'app ?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Dès que tu as envoyé la lettre de demande de conciliation, une carte « Déroulement de la procédure » apparaît sous la lettre avec trois phases. (1) Convocation reçue: touche-la et saisis la date de réception de la convocation de l'autorité de conciliation. (2) Date d'audience: la date de l'audience elle-même. (3) Résultat: après l'audience, choisis « Accord trouvé », « Transaction conclue » ou « Procédure devant le tribunal ». Tu as ainsi documenté le déroulement dans l'app, parallèlement à tes dossiers officiels de l'autorité."
      }
    },
    {
      "@type": "Question",
      "name": "Puis-je modifier le texte de la lettre ?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Oui, télécharge la lettre au format Word (aperçu → icône de téléchargement en haut à droite → Word). Important : dès que tu modifies le texte dans le fichier Word, tu ne peux plus envoyer la lettre via Baisse-loyer. Il faut alors l'imprimer et la poster toi-même. L'envoi intégré ne fonctionne qu'avec le texte original de l'app, car la lettre est transmise au service d'impression avant que tu puisses y apporter des modifications."
      }
    },
    {
      "@type": "Question",
      "name": "Ma signature dans l'app est-elle juridiquement valable ?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Oui, pour toutes les lettres de Baisse-loyer elle suffit. Le droit suisse du bail (art. 270a CO) ne prescrit aucune forme particulière pour les demandes de baisse ou les lettres de suivi. Ta signature dessinée au doigt respecte le standard pratique et est acceptée par les bailleur·eresses. La signature est stockée uniquement localement sur ton appareil et transmise au service d'impression seulement lors de l'envoi."
      }
    },
    {
      "@type": "Question",
      "name": "La signature au doigt sur le smartphone est-elle juridiquement valable ?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "La demande de baisse de loyer n'est soumise à aucune forme selon l'art. 270a CO : aucune forme écrite, aucune signature manuscrite n'est exigée. La signature au doigt dans Baisse-loyer va donc bien au-delà de ce qui est juridiquement requis et suffit largement. Le Tribunal fédéral a confirmé dans l'ATF 144 III 81 qu'une signature électronique simple est équivalente à une signature manuscrite pour les actes juridiques non soumis à une forme (cf. aussi art. 13/14 CO sur la forme écrite simple comme valeur par défaut pour les actes formels). En cas de procédure de conciliation, Baisse-loyer assure déjà l'identification nécessaire grâce à tes données personnelles enregistrées (nom, adresse)."
      }
    },
    {
      "@type": "Question",
      "name": "Tous les locataires doivent-ils signer ?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Juridiquement non, le droit suisse du bail ne prescrit aucune forme. En pratique, c'est fortement recommandé : un·e bailleur·eresse peut refuser une demande déposée par une seule personne sans l'accord des autres. Avec plusieurs parties au contrat, Baisse-loyer te propose deux voies : signer ensemble sur l'appareil (l'assistant passe l'appareil entre les parties) et envoyer via l'app, ou télécharger la lettre, la faire signer sur papier et la poster toi-même."
      }
    },
    {
      "@type": "Question",
      "name": "Baisse-loyer propose-t-elle aussi des lettres de suivi ?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Oui. Sous « Tes lettres » dans le tableau de bord tu trouves, à côté de la demande principale, trois lettres de suivi : « Lettre de rappel » (si ta·ton bailleur·eresse ne répond pas du tout, ce qui arrive souvent), « Demande de justification et de pièces » (si elle·il refuse en invoquant un forfait de coûts, l'usage local/de quartier ou le rendement) et « Demander une conciliation » (si après rappel la réponse reste absente ou insuffisante). Toutes les lettres sont préremplies avec tes données et disponibles en PDF et document Word éditable."
      }
    },
    {
      "@type": "Question",
      "name": "Ma·mon bailleur·eresse ne répond pas, que faire ?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Très fréquent. Beaucoup de bailleur·eresses (surtout privé·e·s) ne réagissent pas à une demande de baisse. Après 30 jours de silence tu peux juridiquement saisir directement l'autorité de conciliation. Mais souvent il vaut la peine d'envoyer d'abord un rappel amical avec un dernier délai. Sous « Tes lettres » tu trouves pour cela la lettre « Lettre de rappel » : elle confirme la date de ton envoi initial, fixe un nouveau délai de 14 jours et annonce la saisine de l'autorité. Souvent cela suffit pour obtenir une réponse et éviter l'escalade."
      }
    },
    {
      "@type": "Question",
      "name": "Que peut m'opposer ma·mon bailleur·eresse en compensation ?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Deux éléments : 40 % du renchérissement accumulé ainsi que les hausses générales de coûts (entretien, administration, taxes, impôts fonciers, assurances). Selon le Tribunal fédéral, la hausse de coûts doit être prouvée par un calcul comparatif. En pratique, beaucoup d'autorités de conciliation acceptent des forfaits si les locataires ne les contestent pas. Si tu contestes, ton·a bailleur·esse doit prouver les coûts réels sur des moyennes de 3 ou 5 ans. Si on t'oppose un tel forfait : sous « Tes lettres » tu trouveras la lettre de suivi « Demande de justification et de pièces » (CHF 6.90) qui exige formellement les pièces justificatives. Baisse-loyer calcule volontairement sans ces déductions. Ton droit net peut donc être plus bas."
      }
    },
    {
      "@type": "Question",
      "name": "Que faire si ma demande est refusée ?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Tu peux saisir l'autorité de conciliation de ton arrondissement dans les 30 jours suivant la réponse. Si ta·ton bailleur·eresse ne répond pas ou répond en retard, tu as 60 jours dès l'envoi de la demande initiale. La procédure est gratuite. Motifs de refus fréquents (souvent insoutenables) : rendement insuffisant, défaut d'usage local ou de quartier, forfaits de coûts excessifs. Sous « Tes lettres » tu peux créer les lettres de suivi adaptées : « Demande de justification et de pièces » si on t'oppose l'un de ces motifs, « Demander une conciliation » pour la saisie. En cas de doute, l'association des locataires peut t'aider. Baisse-loyer ne prend pas en charge la conciliation."
      }
    },
    {
      "@type": "Question",
      "name": "Baisse-loyer me rappelle si rien ne se passe ?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Oui. Après l'envoi de la lettre, Baisse-loyer te recontacte automatiquement après 14, 30 et 60 jours si la·le bailleur·euse n'a pas réagi. Tu peux alors définir le statut en un tap (accepté / partiel / refusé / pas encore de réponse) et l'app propose directement la lettre de suivi adaptée. Pas besoin de noter quoi que ce soit dans ton calendrier. Nous te rappelons jusqu'à ce que tu dises que ton dossier est terminé."
      }
    },
    {
      "@type": "Question",
      "name": "Que stocke l'app sur mon appareil et mes données sont-elles en sécurité ?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Toutes tes saisies, locataire, bailleur·eresse, bail, courriers et signature, restent localement sur ton appareil, dans une base de données chiffrée (AES-256). La clé est dans le Keychain (iOS) ou le Keystore (Android) et ne quitte jamais l'appareil. Lors de l'envoi du courrier, seul le PDF final est transmis à Pingen (service d'impression suisse, contrat AVV signé). Pas de compte, pas de synchronisation cloud, pas d'identifiants publicitaires. Tu peux tout effacer à tout moment depuis Réglages → Confidentialité → « Effacer toutes mes données »."
      }
    },
    {
      "@type": "Question",
      "name": "Combien coûte Baisse-loyer ?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Tu paies par lettre, tout est inclus, un tap. Vérifier ton droit + alerte taux sont gratuits. Pour envoyer la lettre de baisse, tu paies une fois entre CHF 9.90 et 29.90 par lettre. Le prix dépend de ton économie mensuelle (environ 30 % de la première économie, plancher 9.90, plafond 29.90). Inclus : génération de la lettre, impression, envoi automatique de la lettre via Pingen (service d'envoi de courrier suisse, pingen.com), notification dès que la lettre est en route, rappels automatiques après 14/30/60 jours si aucune réponse n'arrive. Pas d'abonnement, pas de paiements récurrents. Recommandé en option : + CHF 7.90, et tu reçois une seconde notification le jour de la distribution. Lettres de suivi : CHF 6.90 chacune si ton·a bailleur·esse ne répond pas. Le rappel et la demande de pièces partent automatiquement via Pingen ; l'annonce de conciliation est elle aussi envoyée par l'app depuis la v1.0.x : tu prends une photo du bail (annexe obligatoire) et éventuellement d'autres correspondances, l'app joint automatiquement les copies de tes lettres précédentes, et l'envoi part en recommandé (CHF 7.90 supplémentaires) à l'autorité de conciliation. Tu peux aussi continuer à télécharger la lettre en Word et la déposer toi-même à la poste."
      }
    },
    {
      "@type": "Question",
      "name": "Dois-je payer chaque mois ou chaque année ?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Non. Baisse-loyer n'est pas un abonnement. Tu paies une fois par lettre. Et uniquement quand tu veux vraiment en créer une. Aucun accès récurrent à ton compte, pas de résiliation à gérer. Si dans quelques années tu as à nouveau droit à une baisse (nouvelle baisse du taux de référence), tu peux acheter une nouvelle lettre. À nouveau à l'unité, sans rien qui tourne en arrière-plan."
      }
    },
    {
      "@type": "Question",
      "name": "Que faire si j'installe Baisse-loyer sur un nouvel appareil ?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Si tu as réinstallé Baisse-loyer ou changé d'appareil, tu peux retrouver tes achats via Réglages → Restaurer mes achats. Apple et Google fournissent la liste de tes achats antérieurs. Baisse-loyer les ré-enregistre localement."
      }
    },
    {
      "@type": "Question",
      "name": "Puis-je annuler un achat ou demander un remboursement ?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Les courriers sont des services numériques fournis immédiatement : après avoir appuyé sur \"Envoyer\", la lettre part au service d'impression et est produite physiquement. Une rétractation après envoi n'est donc pas possible. Si tu as payé mais pas encore envoyé (par exemple, app fermée avant l'envoi), tu peux demander un remboursement via ton App Store dans les 14 jours. iOS : reportaproblem.apple.com → Baisse-loyer → achat → \"Signaler un problème\". Android : play.google.com → Commandes → Baisse-loyer → \"Demander un remboursement\". Apple et Google décident du remboursement. Baisse-loyer ne gère pas directement les paiements et ne peut pas annuler un achat de son côté."
      }
    },
    {
      "@type": "Question",
      "name": "Que deviennent mes données si je supprime et réinstalle l'application ?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Tes courriers, données de bail et signature sont chiffrés en AES-256 et stockés uniquement sur ton appareil. La clé se trouve dans le trousseau iOS ou le Keystore Android et est liée à l'installation. Si tu supprimes Baisse-loyer, la clé est également supprimée et la base de données chiffrée devient illisible, y compris pour les créateurs de l'app. C'est intentionnel : pas de cloud, pas de compte, pas de traces. Après une réinstallation, tu peux uniquement restaurer tes achats (Apple/Google) ; tes courriers et saisies doivent être recréés. Astuce : télécharge les courriers importants en Word ou PDF et sauvegarde-les dans ton cloud ou par e-mail à toi-même. Tu conserves ainsi ton historique d'envoi même après un changement d'appareil."
      }
    },
    {
      "@type": "Question",
      "name": "Dois-je continuer à payer l'ancien loyer pendant la procédure ?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Oui. Jusqu'à ce que ta·ton bailleur·eresse accepte la baisse ou que l'autorité de conciliation tranche, tu continues à payer le loyer actuel. Le nouveau loyer ne devient dû qu'à partir de la date d'effet. Une retenue de ta propre initiative peut entraîner une résiliation immédiate."
      }
    },
    {
      "@type": "Question",
      "name": "Mon·ma bailleur·eresse peut-il·elle me résilier parce que je dépose une demande de baisse ?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Non, tu es protégé·e par la loi. Une résiliation en réaction à ta demande de baisse est annulable selon l'art. 271a al. 1 let. a Code des obligations (CO) (congé de représailles). La charge de la preuve incombe au bailleur : il·elle doit pouvoir démontrer que le congé n'est PAS motivé par ta demande de baisse. Dans la pratique, les bailleurs·esses y parviennent rarement. L'autorité de conciliation déclare alors le congé nul.  Protection supplémentaire : Pendant trois ans à compter de la fin d'une procédure de conciliation ou judiciaire, ton·ta bailleur·eresse ne peut pas te résilier de manière ordinaire (art. 271a al. 1 let. e CO). Une résiliation \"en temps inopportun\" (pendant une procédure en cours ou peu après) est également nulle (art. 271a al. 1 let. d CO).  La demande de baisse est une procédure légale ordinaire. Une adaptation du loyer au niveau actuel du marché. Les baisses de loyer font partie du quotidien des baux suisses, et non pas d'un acte de confrontation."
      }
    },
    {
      "@type": "Question",
      "name": "Que faire si je reçois quand même une résiliation après la demande de baisse ?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Agis immédiatement. Tu n'as que 30 jours dès réception de la résiliation pour la contester auprès de l'autorité de conciliation (art. 273 CO). Étape par étape :  1. Note la date à laquelle tu as reçu la résiliation. Conserve l'enveloppe avec le tampon postal. 2. Sauvegarde la lettre de résiliation + ton historique de courriers. Dans Baisse-loyer sous Réglages → \"Exporter mes données\", télécharge tout le bundle. 3. Contacte l'ASLOCA de ton canton (asloca.ch). Tu y reçois gratuitement ou à faible coût l'aide pour la demande de conciliation. Si tu n'es pas encore membre : adhère maintenant, environ CHF 60 à 100 par an, couvre conseil + accompagnement à la conciliation. 4. Dépose la demande de conciliation auprès de l'autorité compétente. Les adresses des autorités cantonales se trouvent sur bwo.admin.ch. Motif : \"Contestation pour congé de représailles selon l'art. 271a CO\". 5. Demande une prolongation (art. 272 CO) : jusqu'à quatre ans de prolongation du bail pour les logements, même si la résiliation elle-même serait valable. 6. Vérifie ta protection juridique. Beaucoup de polices couvrent intégralement les procédures de conciliation et les demandes de prolongation.  Baisse-loyer ne remplace pas un conseil juridique et n'intervient pas comme ta représentation dans la procédure de conciliation. En cas de réaction agressive du bailleur : ASLOCA ou avocat·e."
      }
    },
    {
      "@type": "Question",
      "name": "Ma demande de baisse est-elle un conflit avec mon·ma bailleur·eresse ?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Non. C'est un droit légal que tu as en tant que locataire si le taux d'intérêt de référence a baissé depuis ta dernière adaptation. Personne ne \"gagne\" ou ne \"perd\". Les bailleurs·esses sont tenu·e·s de prendre position par écrit sur ta demande dans les 30 jours (art. 270a CO).  Pour des adaptations justifiées, ils·elles le font généralement sans discussion : la baisse leur coûte certes de l'argent à court terme, mais elle est juridiquement saine et fait partie du bail normal. De nombreux·ses bailleurs·esses et régies suisses calculent les baisses de loyer de routine, sans que les locataires aient à les exiger activement.  Dans certains cas (surtout chez les petits ou conservateurs bailleurs·esses), une demande de baisse peut être perçue comme désagréable. Si l'ambiance du bail change sensiblement ou si des réparations sont soudainement refusées : l'ASLOCA de ton canton t'aide à coût modeste à évaluer si c'est pertinent et juridiquement actionnable."
      }
    },
    {
      "@type": "Question",
      "name": "Baisse-loyer garantit-elle une baisse effective ?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Non. Baisse-loyer est un outil, pas un conseil juridique ni une garantie d'obtenir une baisse. Le calcul est prudent et s'appuie sur l'art. 270a Code des obligations CO et l'art. 13 ordonnance sur le bail à loyer OBLF, mais il est indicatif. Ta·ton bailleur·eresse n'est pas tenu·e d'accepter la demande sans discussion. Elle·il peut invoquer des contre-arguments (renchérissement, hausse de coûts, rendement insuffisant, usage local et de quartier). Le droit est évalué au cas par cas, et en cas de litige par l'autorité de conciliation. Les créateurs·trices de Baisse-loyer n'assument aucune responsabilité quant à l'issue de ta procédure. Pour des renseignements contraignants, contacte l'association des locataires ou un·e spécialiste."
      }
    }
  ]
}
</script>

## idAnspruch

<h3 id="quand-ai-je-droit-une-baisse-de-loyer">Quand ai-je droit à une baisse de loyer ?</h3>

Dès que le taux d'intérêt de référence a baissé depuis ta dernière adaptation de loyer ou le début de ton bail (art. 270a CO). La baisse n'est pas automatique. Tu dois la demander à ta·ton bailleur·eresse. <strong>Baisse-loyer</strong> vérifie pour toi si un droit existe actuellement et calcule le montant dès que tu as saisi ton loyer net et la date de la dernière adaptation.

<h3 id="comment-l-app-calcule-t-elle-le-droit">Comment l'app calcule-t-elle le droit ?</h3>

<strong>Baisse-loyer</strong> applique l'<strong>ordonnance sur le bail à loyer OBLF</strong> (art. 13) et le <strong>Code des obligations CO</strong> (art. 269a). Trois facteurs entrent dans le calcul : (1) <strong>Baisse du taux de référence</strong>, pour chaque baisse de 0.25 % du taux, le loyer diminue de 2.91 % (valeur minimale prudente selon l'OBLF) ; en cas de plusieurs paliers, on applique l'inverse de la hausse cumulée. (2) <strong>Hausse générale des coûts</strong>, 0.5 % par année depuis la dernière adaptation, que ta·ton bailleur·eresse peut opposer à la baisse. (3) <strong>Compensation du renchérissement</strong>, 40 % de la variation de l'IPC (indice des prix à la consommation) depuis la dernière adaptation, également à charge de la baisse. Le droit net est : baisse du taux moins hausse des coûts moins renchérissement. Si le résultat est négatif, tu n'as pas de droit, même si le taux a baissé. Pour un calcul contraignant, contacte l'association des locataires.

<h3 id="d-o-viennent-les-donn-es-du-taux-de-r-f-rence-et-du-rench-rissement">D'où viennent les données du taux de référence et du renchérissement ?</h3>

Le taux de référence est publié par l'<strong>Office fédéral du logement OFL</strong> (mise à jour trimestrielle, parfois prolongée sans changement). L'indice des prix à la consommation (IPC) pour le renchérissement provient de l'<strong>Office fédéral de la statistique OFS</strong> (publication mensuelle, vers le 6 du mois suivant). Les deux sources sont juridiquement contraignantes. <strong>Baisse-loyer</strong> télécharge les valeurs actuelles à chaque démarrage depuis le serveur (pas depuis le fichier d'installation), et nous les mettons à jour dès chaque publication OFL ou OFS. Si nos données ne sont pas à jour, tu vois un avertissement discret sur le tableau de bord. Tu peux vérifier les données brutes sur bwo.admin.ch et bfs.admin.ch.

<h3 id="pourquoi-l-app-affiche-t-elle-parfois-pas-de-droit-la-baisse-alors-que-le-taux-a">Pourquoi l'app affiche-t-elle parfois « pas de droit à la baisse » alors que le taux a baissé ?</h3>

Pour les baux de longue durée (par ex. 10 ans depuis la dernière adaptation), le renchérissement cumulé (~1 % par an) et la hausse des coûts (0.5 % par an) peuvent être opposés par ta·ton bailleur·eresse à ta demande de baisse. Résultat : taux baissé + compensations accumulées = aucun droit net. <strong>Baisse-loyer</strong> te montre ce cas honnêtement, pour t'éviter d'envoyer une lettre que ta·ton bailleur·eresse pourrait refuser à juste titre. Si tu as des doutes, ou si la hausse des coûts a déjà été compensée par une baisse antérieure, clarifie avec l'association des locataires.

<h3 id="qu-en-est-il-des-baux-index-s-ou-chelonn-s">Qu'en est-il des baux indexés ou échelonnés ?</h3>

Pour ces types de bail, une baisse fondée sur le taux d'intérêt de référence est <strong>exclue</strong> pendant la durée du contrat. <strong>Baisse-loyer</strong> ne détecte pas automatiquement le type de bail, à toi de vérifier brièvement.

<strong>Comment reconnaître le type de bail dans ton contrat :</strong>

- <strong>Bail ordinaire</strong> (le plus fréquent, env. 90-95% des baux d'habitation suisses) : le loyer est un montant fixe en CHF par mois, sans indexation et sans hausses prédéfinies. Exemple : "Loyer net CHF 1500 par mois". → <strong>Demande de baisse selon art. 270a CO possible.</strong>
- <strong>Bail indexé :</strong> le loyer est explicitement lié à l'indice suisse des prix à la consommation (IPC) et augmente avec le renchérissement. Mots-clés au contrat : "loyer indexé", "indexation IPC", "adaptation à l'indice national". Condition préalable : un bail d'au moins 5 ans de durée fixe (art. 269b CO). → <strong>Pas de baisse fondée sur le taux de référence.</strong>
- <strong>Bail à loyers échelonnés :</strong> le loyer augmente selon un plan fixé au contrat, par ex. "Année 1 CHF 1500, année 2 CHF 1550, année 3 CHF 1600". Mots-clés : "loyer échelonné", "échelonnement convenu". Condition préalable : une durée minimale de 3 ans (art. 269c CO). → <strong>Pas de baisse fondée sur le taux de référence.</strong>

En cas de doute, l'ASLOCA de ton canton (asloca.ch) peut vérifier ton contrat.

<h3 id="puis-je-demander-la-baisse-r-troactivement">Puis-je demander la baisse rétroactivement ?</h3>

Non. La baisse prend effet uniquement à partir du prochain terme de résiliation après ta demande. Les sommes payées en trop ne sont plus récupérables. C'est précisément pour cela que <strong>Baisse-loyer</strong> propose l'alerte taux : nous te prévenons dès que le taux de référence baisse. Tu ne manques plus aucune baisse.

<h3 id="comment-retrouver-la-date-de-la-derni-re-adaptation">Comment retrouver la date de la dernière adaptation ?</h3>

Regarde ton bail et toutes les communications ultérieures de ta·ton bailleur·eresse (souvent sur le formulaire officiel). La dernière adaptation peut être le début du bail s'il n'y en a jamais eu. En cas de doute, choisis « Je ne sais pas exactement » dans l'assistant. <strong>Baisse-loyer</strong> calcule alors de façon prudente avec une estimation.


## idBriefVersand

<h3 id="partir-de-quand-le-nouveau-loyer-plus-bas-s-applique-t-il">À partir de quand le nouveau loyer plus bas s'applique-t-il ?</h3>

La baisse prend effet au prochain terme de résiliation après le délai de résiliation contractuel (en général 3 mois). Si tu déposes assez tôt, elle s'applique à cette date. <strong>Baisse-loyer</strong> utilise par défaut les 4 échéances trimestrielles suisses courantes (31.03 / 30.06 / 30.09 / 31.12) et inscrit automatiquement la prochaine date possible dans la lettre.

<h3 id="quand-la-lettre-doit-elle-arriver-chez-ma-mon-bailleur-eresse">Quand la lettre doit-elle arriver chez ma·mon bailleur·eresse ?</h3>

La lettre doit arriver avant le début du délai de résiliation. Exemple : pour une baisse au 1er juillet avec un délai de trois mois, la lettre doit être reçue fin mars. Envoie-la en recommandé comme preuve de réception. <strong>Baisse-loyer</strong> insère automatiquement la prochaine date possible ; c'est toi qui choisis quand poster.

<h3 id="ma-mon-bailleur-eresse-doit-elle-il-r-pondre">Ma·mon bailleur·eresse doit-elle·il répondre ?</h3>

Oui. Ta·ton bailleur·eresse doit prendre position par écrit dans les 30 jours. En cas d'accord, le loyer est adapté. La lettre générée par <strong>Baisse-loyer</strong> mentionne le délai de 30 jours ainsi que les bases légales (art. 270a Code des obligations CO, art. 13 ordonnance sur le bail à loyer OBLF), pour que la demande soit formellement correcte.

<h3 id="comment-dois-je-envoyer-la-lettre">Comment dois-je envoyer la lettre ?</h3>

De préférence en recommandé. Tu disposes ainsi d'une preuve de réception en cas de litige. <strong>Baisse-loyer</strong> crée le PDF et tu peux l'envoyer directement depuis l'app comme lettre standard ou en recommandé. Tu peux aussi télécharger un PDF ou Word, l'imprimer et le déposer toi-même à la poste. Conserve toujours une copie pour tes dossiers.

<h3 id="comment-envoyer-une-lettre-directement-depuis-l-app">Comment envoyer une lettre directement depuis l'app ?</h3>

Crée la lettre dans l'assistant, ouvre l'aperçu et tape sur « Envoyer la lettre » ou « Envoyer en recommandé ». La première fois, nous te demandons ta signature (dessinée une seule fois sur l'appareil). Ensuite, <strong>Baisse-loyer</strong> transmet la lettre au service d'impression suisse Pingen, qui l'imprime physiquement et la poste à ton·a bailleur·esse. Tu reçois une notification dès que la lettre est remise à La Poste, avec un envoi recommandé, en plus le jour de la distribution.

<h3 id="comment-savoir-si-ma-lettre-est-bien-arriv-e">Comment savoir si ma lettre est bien arrivée ?</h3>

Dès que <strong>Pingen</strong> (le service d'envoi de courrier suisse basé à Zurich, pingen.com) remet ta lettre à La Poste, <strong>Baisse-loyer</strong> t'envoie une notification (« Lettre en route »). Avec un <strong>envoi recommandé</strong> (CHF 7.90 supplémentaires), tu reçois en plus, le jour de la distribution effective, une seconde notification (« Lettre distribuée le DD.MM. »), et le numéro de suivi de La Poste suisse apparaît dans la fiche de la lettre. Un envoi standard ne fournit par définition aucune preuve de distribution (c'est une caractéristique du système postal suisse, pas une limite de l'app). Si tu as besoin d'une certitude juridique sur l'arrivée, par exemple parce que tu envisages la conciliation, choisis le recommandé.

<h3 id="combien-co-te-l-envoi">Combien coûte l'envoi ?</h3>

L'<strong>envoi de la lettre</strong> est directement inclus dans l'achat de la lettre (sans supplément). Aucun frais supplémentaire, distribution en règle générale en 2 jours ouvrables. Le <strong>recommandé</strong> coûte CHF 7.90 de plus par lettre (supplément, hors abonnement), payable via l'App Store / Play Store. Le prix couvre l'affranchissement, la preuve de dépôt et l'impression. Au guichet postal, un recommandé coûte environ CHF 5.70 plus ton déplacement. Le recommandé est juridiquement recommandé pour les demandes de baisse, car il fournit une preuve de réception.

<h3 id="puis-je-annuler-une-lettre-d-j-envoy-e">Puis-je annuler une lettre déjà envoyée ?</h3>

Oui, <strong>dans les 30 minutes environ après l'envoi</strong>, tant que Pingen n'a pas encore imprimé la lettre. Une pastille « Annuler » apparaît sur la carte de la lettre dans le tableau de bord. Touche-la, la lettre est supprimée chez Pingen et repasse en brouillon dans l'app. Tu peux ensuite corriger par exemple l'adresse du·de la destinataire et l'envoyer à nouveau. Si la lettre est déjà imprimée, l'app affiche « Annulation impossible », il faut alors attendre que la lettre revienne (en recommandé) ou considérer l'envoi comme expérience.

<h3 id="j-ai-marqu-la-lettre-comme-d-pos-e-moi-m-me-mais-ne-l-ai-pas-d-pos-e-que-faire">J'ai marqué la lettre comme déposée moi-même mais ne l'ai pas déposée. Que faire ?</h3>

Touche l'icône crayon sur la carte de la lettre dans le tableau de bord. Dans la feuille qui s'ouvre apparaît un bouton <strong>« Annuler l'envoi personnel »</strong>. Confirme : la lettre repasse à l'état brouillon, la date d'envoi et un éventuel statut de réponse sont supprimés. Tu peux ensuite la renvoyer ou la télécharger en Word.

<h3 id="comment-r-cup-rer-une-proc-dure-archiv-e">Comment récupérer une procédure archivée ?</h3>

Dans l'onglet Plus sous <strong>« Archives »</strong> tu trouves toutes les procédures clôturées. Pour chaque groupe il y a une icône <strong>« Réactiver la procédure »</strong> (flèche circulaire) à côté de l'icône de suppression. Tape → dialogue de confirmation → les lettres de cette procédure réapparaissent dans le tableau de bord actif, le statut actuel (acceptée/partielle/refusée) est conservé. Utile si tu veux p.ex. mener une procédure clôturée jusqu'à la conciliation après tout.

<h3 id="ma-lettre-est-revenue-non-distribuable-que-faire">Ma lettre est revenue (non distribuable). Que faire ?</h3>

Dans le tableau de bord apparaît un hero <strong>« Envoi échoué »</strong> indiquant un possible problème d'adresse. Tape sur « Vérifier l'adresse » → tu arrives directement dans le formulaire bailleur·esse. Corrige l'adresse, sauvegarde, retourne à la lettre et renvoie. <strong>Note :</strong> « non distribuable » n'apparaît qu'avec le recommandé, car La Poste suisse ne suit pas les envois standards. Pour une preuve de réception juridique, recommande l'upgrade recommandé (+ CHF 7.90).

<h3 id="puis-je-envoyer-plusieurs-lettres-de-rappel">Puis-je envoyer plusieurs lettres de rappel ?</h3>

Oui. Si ton·a bailleur·esse reste silencieux·se malgré le premier rappel, tu peux envoyer une <strong>deuxième (ou troisième) lettre de rappel</strong>. Touche le CTA rappel comme d'habitude, l'app affiche un dialogue « Déjà envoyée le DD.MM., renvoyer ? » et tu confirmes l'achat (CHF 6.90 par lettre de suivi). Souvent pertinent juridiquement comme dernière étape avant la demande de conciliation, car les rappels multiples documentent la procédure. Même logique pour la demande de pièces.

<h3 id="l-autorit-de-conciliation-accepte-t-elle-ma-lettre-depuis-baisse-loyer-ou-ai-je-">L'autorité de conciliation accepte-t-elle ma lettre depuis Baisse-loyer, ou ai-je besoin d'un formulaire cantonal ?</h3>

La lettre de conciliation générée par <strong>Baisse-loyer</strong> est conforme à l'<strong>art. 202 al. 2 CPC</strong> : elle contient la désignation de la partie adverse, la conclusion et l'objet du litige ainsi que ta signature. Elle doit donc être acceptée par <strong>toutes les autorités de conciliation suisses</strong> en matière de bail. Il n'existe pas d'obligation fédérale d'utiliser un formulaire cantonal.

<strong>Certains cantons (par exemple Zurich, Berne) proposent leurs propres formulaires de conciliation</strong> pour accélérer le traitement interne. Ces formulaires sont une recommandation, pas une exigence. Si ton autorité de conciliation te demande un formulaire : tu peux le remettre ultérieurement, ta saisie initiale reste valide dans le délai (la date de la lettre Baisse-loyer compte pour le délai de 30 jours selon l'art. 273 CO).

Si tu préfères le formulaire cantonal : contacte l'autorité de conciliation compétente de ton domicile. Les adresses se trouvent sur bwo.admin.ch sous "Schlichtungsbehörden / Autorités de conciliation". Dans ce cas, télécharge la lettre de conciliation depuis <strong>Baisse-loyer</strong> au format Word et reprends les calculs et la liste des annexes dans le formulaire.

<h3 id="comment-suivre-l-audience-de-conciliation-dans-l-app">Comment suivre l'audience de conciliation dans l'app ?</h3>

Dès que tu as envoyé la lettre de demande de conciliation, une carte <strong>« Déroulement de la procédure »</strong> apparaît sous la lettre avec trois phases. (1) <strong>Convocation reçue</strong>: touche-la et saisis la date de réception de la convocation de l'autorité de conciliation. (2) <strong>Date d'audience</strong>: la date de l'audience elle-même. (3) <strong>Résultat</strong>: après l'audience, choisis « Accord trouvé », « Transaction conclue » ou « Procédure devant le tribunal ». Tu as ainsi documenté le déroulement dans l'app, parallèlement à tes dossiers officiels de l'autorité.

<h3 id="puis-je-modifier-le-texte-de-la-lettre">Puis-je modifier le texte de la lettre ?</h3>

Oui, télécharge la lettre au format Word (aperçu → icône de téléchargement en haut à droite → Word). Important : <strong>dès que tu modifies le texte dans le fichier Word, tu ne peux plus envoyer la lettre via Baisse-loyer</strong>. Il faut alors l'imprimer et la poster toi-même. L'envoi intégré ne fonctionne qu'avec le texte original de l'app, car la lettre est transmise au service d'impression avant que tu puisses y apporter des modifications.

<h3 id="ma-signature-dans-l-app-est-elle-juridiquement-valable">Ma signature dans l'app est-elle juridiquement valable ?</h3>

Oui, pour toutes les lettres de <strong>Baisse-loyer</strong> elle suffit. Le droit suisse du bail (art. 270a CO) ne prescrit aucune forme particulière pour les demandes de baisse ou les lettres de suivi. Ta signature dessinée au doigt respecte le standard pratique et est acceptée par les bailleur·eresses. La signature est stockée uniquement localement sur ton appareil et transmise au service d'impression seulement lors de l'envoi.

<h3 id="la-signature-au-doigt-sur-le-smartphone-est-elle-juridiquement-valable">La signature au doigt sur le smartphone est-elle juridiquement valable ?</h3>

La demande de baisse de loyer n'est soumise à <strong>aucune forme selon l'art. 270a CO</strong> : aucune forme écrite, aucune signature manuscrite n'est exigée. La signature au doigt dans <strong>Baisse-loyer</strong> va donc bien au-delà de ce qui est juridiquement requis et suffit largement. Le Tribunal fédéral a confirmé dans l'<strong>ATF 144 III 81</strong> qu'une signature électronique simple est équivalente à une signature manuscrite pour les actes juridiques non soumis à une forme (cf. aussi art. 13/14 CO sur la forme écrite simple comme valeur par défaut pour les actes formels). En cas de procédure de conciliation, <strong>Baisse-loyer</strong> assure déjà l'identification nécessaire grâce à tes données personnelles enregistrées (nom, adresse).

<h3 id="tous-les-locataires-doivent-ils-signer">Tous les locataires doivent-ils signer ?</h3>

Juridiquement non, le droit suisse du bail ne prescrit aucune forme. En pratique, c'est fortement recommandé : un·e bailleur·eresse peut refuser une demande déposée par une seule personne sans l'accord des autres. Avec plusieurs parties au contrat, <strong>Baisse-loyer</strong> te propose deux voies : signer ensemble sur l'appareil (l'assistant passe l'appareil entre les parties) et envoyer via l'app, ou télécharger la lettre, la faire signer sur papier et la poster toi-même.


## idFolgebrief

<h3 id="baisse-loyer-propose-t-elle-aussi-des-lettres-de-suivi">Baisse-loyer propose-t-elle aussi des lettres de suivi ?</h3>

Oui. Sous <strong>« Tes lettres »</strong> dans le tableau de bord tu trouves, à côté de la demande principale, trois lettres de suivi : « Lettre de rappel » (si ta·ton bailleur·eresse ne répond pas du tout, ce qui arrive souvent), « Demande de justification et de pièces » (si elle·il refuse en invoquant un forfait de coûts, l'usage local/de quartier ou le rendement) et « Demander une conciliation » (si après rappel la réponse reste absente ou insuffisante). Toutes les lettres sont préremplies avec tes données et disponibles en PDF et document Word éditable.

<h3 id="ma-mon-bailleur-eresse-ne-r-pond-pas-que-faire">Ma·mon bailleur·eresse ne répond pas, que faire ?</h3>

Très fréquent. Beaucoup de bailleur·eresses (surtout privé·e·s) ne réagissent pas à une demande de baisse. Après 30 jours de silence tu peux juridiquement saisir directement l'autorité de conciliation. Mais souvent il vaut la peine d'envoyer d'abord un rappel amical avec un dernier délai. Sous <strong>« Tes lettres »</strong> tu trouves pour cela la lettre « Lettre de rappel » : elle confirme la date de ton envoi initial, fixe un nouveau délai de 14 jours et annonce la saisine de l'autorité. Souvent cela suffit pour obtenir une réponse et éviter l'escalade.

<h3 id="que-peut-m-opposer-ma-mon-bailleur-eresse-en-compensation">Que peut m'opposer ma·mon bailleur·eresse en compensation ?</h3>

Deux éléments : 40 % du renchérissement accumulé ainsi que les hausses générales de coûts (entretien, administration, taxes, impôts fonciers, assurances). Selon le Tribunal fédéral, la hausse de coûts doit être prouvée par un calcul comparatif. En pratique, beaucoup d'autorités de conciliation acceptent des forfaits si les locataires ne les contestent pas. Si tu contestes, ton·a bailleur·esse doit prouver les coûts réels sur des moyennes de 3 ou 5 ans. Si on t'oppose un tel forfait : sous <strong>« Tes lettres »</strong> tu trouveras la lettre de suivi « Demande de justification et de pièces » (CHF 6.90) qui exige formellement les pièces justificatives. <strong>Baisse-loyer</strong> calcule volontairement sans ces déductions. Ton droit net peut donc être plus bas.

<h3 id="que-faire-si-ma-demande-est-refus-e">Que faire si ma demande est refusée ?</h3>

Tu peux saisir l'autorité de conciliation de ton arrondissement dans les 30 jours suivant la réponse. Si ta·ton bailleur·eresse ne répond pas ou répond en retard, tu as 60 jours dès l'envoi de la demande initiale. La procédure est gratuite. Motifs de refus fréquents (souvent insoutenables) : rendement insuffisant, défaut d'usage local ou de quartier, forfaits de coûts excessifs. Sous <strong>« Tes lettres »</strong> tu peux créer les lettres de suivi adaptées : « Demande de justification et de pièces » si on t'oppose l'un de ces motifs, « Demander une conciliation » pour la saisie. En cas de doute, l'association des locataires peut t'aider. <strong>Baisse-loyer</strong> ne prend pas en charge la conciliation.

<h3 id="baisse-loyer-me-rappelle-si-rien-ne-se-passe">Baisse-loyer me rappelle si rien ne se passe ?</h3>

Oui. Après l'envoi de la lettre, <strong>Baisse-loyer</strong> te recontacte automatiquement après 14, 30 et 60 jours si la·le bailleur·euse n'a pas réagi. Tu peux alors définir le statut en un tap (accepté / partiel / refusé / pas encore de réponse) et l'app propose directement la lettre de suivi adaptée. Pas besoin de noter quoi que ce soit dans ton calendrier. Nous te rappelons jusqu'à ce que tu dises que ton dossier est terminé.


## idAppDaten

<h3 id="que-stocke-l-app-sur-mon-appareil-et-mes-donn-es-sont-elles-en-s-curit">Que stocke l'app sur mon appareil et mes données sont-elles en sécurité ?</h3>

Toutes tes saisies, locataire, bailleur·eresse, bail, courriers et signature, restent <strong>localement sur ton appareil</strong>, dans une base de données chiffrée (AES-256). La clé est dans le Keychain (iOS) ou le Keystore (Android) et ne quitte jamais l'appareil. Lors de l'envoi du courrier, seul le PDF final est transmis à Pingen (service d'impression suisse, contrat AVV signé). <strong>Pas de compte</strong>, pas de synchronisation cloud, pas d'identifiants publicitaires. Tu peux tout effacer à tout moment depuis Réglages → Confidentialité → « Effacer toutes mes données ».

<h3 id="combien-co-te-baisse-loyer">Combien coûte Baisse-loyer ?</h3>

<strong>Tu paies par lettre, tout est inclus, un tap.</strong> Vérifier ton droit + alerte taux sont gratuits. Pour envoyer la lettre de baisse, tu paies une fois entre <strong>CHF 9.90 et 29.90</strong> par lettre. Le prix dépend de ton économie mensuelle (environ 30 % de la première économie, plancher 9.90, plafond 29.90). Inclus : génération de la lettre, impression, envoi automatique de la lettre via <strong>Pingen</strong> (service d'envoi de courrier suisse, pingen.com), notification dès que la lettre est en route, rappels automatiques après 14/30/60 jours si aucune réponse n'arrive. Pas d'abonnement, pas de paiements récurrents. <strong>Recommandé en option</strong> : + CHF 7.90, et tu reçois une seconde notification le jour de la distribution. <strong>Lettres de suivi</strong> : CHF 6.90 chacune si ton·a bailleur·esse ne répond pas. Le rappel et la demande de pièces partent automatiquement via Pingen ; <strong>l'annonce de conciliation</strong> est elle aussi envoyée par l'app depuis la v1.0.x : tu prends une photo du bail (annexe obligatoire) et éventuellement d'autres correspondances, l'app joint automatiquement les copies de tes lettres précédentes, et l'envoi part en recommandé (CHF 7.90 supplémentaires) à l'autorité de conciliation. Tu peux aussi continuer à télécharger la lettre en Word et la déposer toi-même à la poste.

<h3 id="dois-je-payer-chaque-mois-ou-chaque-ann-e">Dois-je payer chaque mois ou chaque année ?</h3>

Non. <strong>Baisse-loyer</strong> n'est pas un abonnement. Tu paies une fois par lettre. Et uniquement quand tu veux vraiment en créer une. Aucun accès récurrent à ton compte, pas de résiliation à gérer. Si dans quelques années tu as à nouveau droit à une baisse (nouvelle baisse du taux de référence), tu peux acheter une nouvelle lettre. À nouveau à l'unité, sans rien qui tourne en arrière-plan.

<h3 id="que-faire-si-j-installe-baisse-loyer-sur-un-nouvel-appareil">Que faire si j'installe Baisse-loyer sur un nouvel appareil ?</h3>

Si tu as réinstallé Baisse-loyer ou changé d'appareil, tu peux retrouver tes achats via <strong>Réglages → Restaurer mes achats</strong>. Apple et Google fournissent la liste de tes achats antérieurs. <strong>Baisse-loyer</strong> les ré-enregistre localement.

<h3 id="puis-je-annuler-un-achat-ou-demander-un-remboursement">Puis-je annuler un achat ou demander un remboursement ?</h3>

Les courriers sont des services numériques fournis immédiatement : après avoir appuyé sur "Envoyer", la lettre part au service d'impression et est produite physiquement. Une rétractation après envoi n'est donc pas possible. Si tu as payé mais pas encore envoyé (par exemple, app fermée avant l'envoi), tu peux demander un remboursement via ton App Store dans les 14 jours. <strong>iOS :</strong> reportaproblem.apple.com → Baisse-loyer → achat → "Signaler un problème". <strong>Android :</strong> play.google.com → Commandes → Baisse-loyer → "Demander un remboursement". Apple et Google décident du remboursement. <strong>Baisse-loyer</strong> ne gère pas directement les paiements et ne peut pas annuler un achat de son côté.

<h3 id="que-deviennent-mes-donn-es-si-je-supprime-et-r-installe-l-application">Que deviennent mes données si je supprime et réinstalle l'application ?</h3>

Tes courriers, données de bail et signature sont <strong>chiffrés en AES-256 et stockés uniquement sur ton appareil</strong>. La clé se trouve dans le trousseau iOS ou le Keystore Android et est liée à l'installation. Si tu supprimes <strong>Baisse-loyer</strong>, la clé est également supprimée et la base de données chiffrée devient illisible, y compris pour les créateurs de l'app. C'est intentionnel : pas de cloud, pas de compte, pas de traces. Après une réinstallation, tu peux uniquement restaurer tes <strong>achats</strong> (Apple/Google) ; tes courriers et saisies doivent être recréés. Astuce : télécharge les courriers importants en <strong>Word ou PDF</strong> et sauvegarde-les dans ton cloud ou par e-mail à toi-même. Tu conserves ainsi ton historique d'envoi même après un changement d'appareil.

<h3 id="dois-je-continuer-payer-l-ancien-loyer-pendant-la-proc-dure">Dois-je continuer à payer l'ancien loyer pendant la procédure ?</h3>

Oui. Jusqu'à ce que ta·ton bailleur·eresse accepte la baisse ou que l'autorité de conciliation tranche, tu continues à payer le loyer actuel. Le nouveau loyer ne devient dû qu'à partir de la date d'effet. Une retenue de ta propre initiative peut entraîner une résiliation immédiate.


## idRecht

<h3 id="mon-ma-bailleur-eresse-peut-il-elle-me-r-silier-parce-que-je-d-pose-une-demande-">Mon·ma bailleur·eresse peut-il·elle me résilier parce que je dépose une demande de baisse ?</h3>

Non, tu es protégé·e par la loi. Une résiliation en réaction à ta demande de baisse est annulable selon <strong>l'art. 271a al. 1 let. a Code des obligations (CO)</strong> (congé de représailles). La charge de la preuve incombe au bailleur : il·elle doit pouvoir démontrer que le congé n'est PAS motivé par ta demande de baisse. Dans la pratique, les bailleurs·esses y parviennent rarement. L'autorité de conciliation déclare alors le congé nul.

<strong>Protection supplémentaire :</strong> Pendant <strong>trois ans</strong> à compter de la fin d'une procédure de conciliation ou judiciaire, ton·ta bailleur·eresse ne peut pas te résilier de manière ordinaire (art. 271a al. 1 let. e CO). Une résiliation "en temps inopportun" (pendant une procédure en cours ou peu après) est également nulle (art. 271a al. 1 let. d CO).

La demande de baisse est une procédure légale ordinaire. Une adaptation du loyer au niveau actuel du marché. Les baisses de loyer font partie du quotidien des baux suisses, et non pas d'un acte de confrontation.

<h3 id="que-faire-si-je-re-ois-quand-m-me-une-r-siliation-apr-s-la-demande-de-baisse">Que faire si je reçois quand même une résiliation après la demande de baisse ?</h3>

Agis immédiatement. Tu n'as que <strong>30 jours</strong> dès réception de la résiliation pour la contester auprès de l'autorité de conciliation (art. 273 CO). Étape par étape :

1. <strong>Note la date</strong> à laquelle tu as reçu la résiliation. Conserve l'enveloppe avec le tampon postal.
2. <strong>Sauvegarde la lettre de résiliation + ton historique de courriers</strong>. Dans <strong>Baisse-loyer</strong> sous Réglages → "Exporter mes données", télécharge tout le bundle.
3. <strong>Contacte l'ASLOCA</strong> de ton canton (asloca.ch). Tu y reçois gratuitement ou à faible coût l'aide pour la demande de conciliation. Si tu n'es pas encore membre : adhère maintenant, environ CHF 60 à 100 par an, couvre conseil + accompagnement à la conciliation.
4. <strong>Dépose la demande de conciliation</strong> auprès de l'autorité compétente. Les adresses des autorités cantonales se trouvent sur bwo.admin.ch. Motif : "Contestation pour congé de représailles selon l'art. 271a CO".
5. <strong>Demande une prolongation</strong> (art. 272 CO) : jusqu'à <strong>quatre ans de prolongation</strong> du bail pour les logements, même si la résiliation elle-même serait valable.
6. <strong>Vérifie ta protection juridique</strong>. Beaucoup de polices couvrent intégralement les procédures de conciliation et les demandes de prolongation.

<strong>Baisse-loyer ne remplace pas un conseil juridique</strong> et n'intervient pas comme ta représentation dans la procédure de conciliation. En cas de réaction agressive du bailleur : ASLOCA ou avocat·e.

<h3 id="ma-demande-de-baisse-est-elle-un-conflit-avec-mon-ma-bailleur-eresse">Ma demande de baisse est-elle un conflit avec mon·ma bailleur·eresse ?</h3>

Non. C'est un droit légal que tu as en tant que locataire si le taux d'intérêt de référence a baissé depuis ta dernière adaptation. Personne ne "gagne" ou ne "perd". Les bailleurs·esses sont tenu·e·s de prendre position par écrit sur ta demande dans les 30 jours (art. 270a CO).

Pour des adaptations justifiées, ils·elles le font généralement sans discussion : la baisse leur coûte certes de l'argent à court terme, mais elle est juridiquement saine et fait partie du bail normal. De nombreux·ses bailleurs·esses et régies suisses calculent les baisses de loyer de routine, sans que les locataires aient à les exiger activement.

Dans certains cas (surtout chez les petits ou conservateurs bailleurs·esses), une demande de baisse peut être perçue comme désagréable. Si l'ambiance du bail change sensiblement ou si des réparations sont soudainement refusées : l'ASLOCA de ton canton t'aide à coût modeste à évaluer si c'est pertinent et juridiquement actionnable.

<h3 id="baisse-loyer-garantit-elle-une-baisse-effective">Baisse-loyer garantit-elle une baisse effective ?</h3>

Non. <strong>Baisse-loyer</strong> est un outil, pas un conseil juridique ni une garantie d'obtenir une baisse. Le calcul est prudent et s'appuie sur l'art. 270a Code des obligations CO et l'art. 13 ordonnance sur le bail à loyer OBLF, mais il est indicatif. Ta·ton bailleur·eresse n'est pas tenu·e d'accepter la demande sans discussion. Elle·il peut invoquer des contre-arguments (renchérissement, hausse de coûts, rendement insuffisant, usage local et de quartier). Le droit est évalué au cas par cas, et en cas de litige par l'autorité de conciliation. Les créateurs·trices de <strong>Baisse-loyer</strong> n'assument aucune responsabilité quant à l'issue de ta procédure. Pour des renseignements contraignants, contacte l'association des locataires ou un·e spécialiste.

