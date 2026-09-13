# LeanAngle Moto

Application web mobile pour afficher l'angle d'inclinaison d'une moto à partir des capteurs d'orientation du téléphone.

## Utilisation
1. Héberger le dossier sur un serveur HTTPS (GitHub Pages, Netlify, Vercel, etc.).
2. Ouvrir la page depuis Safari sur iPhone ou Chrome sur Android.
3. Fixer le téléphone au Quad Lock dans sa position définitive.
4. Moto droite et immobile, appuyer sur "Activer les capteurs".
5. Utiliser "Calibrer le zéro" si nécessaire.
6. Les maxima gauche/droite restent affichés jusqu'à leur remise à zéro.

## Important
- L'accès aux capteurs et le Wake Lock nécessitent un contexte HTTPS sur les navigateurs mobiles modernes.
- Sur iPhone/iPad, l'autorisation des capteurs doit être déclenchée par une action utilisateur.
- La mesure est indicative : vibrations, montage, comportement du navigateur et capteurs du téléphone influencent la précision.
- Ne pas manipuler le téléphone pendant la conduite.
