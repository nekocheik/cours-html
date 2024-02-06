## **Balises Auto-fermantes en HTML**

En HTML, certaines balises sont dites "auto-fermantes", c'est-à-dire qu'elles ne nécessitent pas de balise de fermeture explicite. Ces balises sont utilisées pour insérer des éléments qui n'encapsulent pas de texte ou d'autres balises, comme des images, des sauts de ligne, ou encore des inputs de formulaire. Elles jouent un rôle essentiel dans la structuration et la mise en forme des pages web.

### **Caractéristiques des Balises Auto-fermantes**

Contrairement aux balises traditionnelles qui ont une balise d'ouverture et une balise de fermeture, les balises auto-fermantes se terminent immédiatement après leur ouverture. Dans le code HTML, elles peuvent être suivies d'un slash (**`/`**) avant le chevron fermant (**`>`**), bien que cette pratique soit optionnelle en HTML5.

### **Exemples de Balises Auto-fermantes**

Voici quelques exemples de balises auto-fermantes couramment utilisées en HTML :

- **`<br>`** : Insère un saut de ligne. Utile pour la poésie, les adresses, ou partout où un retour à la ligne spécifique est nécessaire sans créer un nouveau paragraphe.
- **`<img src="url" alt="description">`** : Affiche une image. Requiert les attributs **`src`** pour la source de l'image et **`alt`** pour la description textuelle de l'image.
- **`<hr>`** : Crée une ligne horizontale pour séparer le contenu.
- **`<input>`** : Utilisé pour créer un champ de saisie dans un formulaire. Peut avoir différents types spécifiés par l'attribut **`type`** (text, password, submit, etc.).
- **`<link rel="stylesheet" href="style.css">`** : Lie une feuille de style externe à la page HTML.
- **`<meta charset="UTF-8">`** : Spécifie le jeu de caractères utilisé par la page HTML.

### **Utilisation de la Balise `<br>` pour un Poème**

La balise **`<br>`** est particulièrement utile pour formater des textes nécessitant des retours à la ligne spécifiques, comme des poèmes ou des adresses. Voici un exemple d'utilisation de cette balise pour respecter la structure d'un haïku :

```html
<p>Un eau.</p>
<p>Haïku de Bashō</p>

```

### **Conclusion**

Les balises auto-fermantes sont un aspect essentiel du langage HTML, permettant d'ajouter des éléments uniques à une page sans nécessiter une structure de balisage ouverte et fermée. Leur simplicité et leur efficacité dans la mise en forme et l'ajout de fonctionnalités spécifiques à une page web les rendent indispensables pour tout développeur web. En comprenant leur fonctionnement et leur utilisation appropriée, vous pouvez améliorer significativement la structure et l'apparence de vos pages web.